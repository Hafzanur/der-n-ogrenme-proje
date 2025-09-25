# der-n-ogrenme-proje

# 🧠 Brain Tumor Detection with Deep Learning  
**Akbank Derin Öğrenme Bootcamp Projesi**

---

## 📖 Giriş
Bu projede Kaggle üzerinde yer alan **Brain Tumor MRI Dataset** kullanılarak, MRI görüntülerinden beyin tümörlerini sınıflandırmak için bir **Convolutional Neural Network (CNN)** modeli geliştirilmiştir.  

- Kullanılan veri seti: [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets)  
- Sınıflar: **Glioma, Meningioma, Pituitary, No Tumor**  
- Amaç: Derin öğrenme yöntemleri ile MRI görüntülerinde tümör tespiti yapmak.  

---

## ⚙️ Proje Teknik Detaylar
Proje, **Kaggle Notebook** ortamında geliştirilmiştir.  
Eğitim sürecinde:  
- **Data Augmentation** (çevirme, kaydırma, döndürme, zoom)  
- **CNN modeli** (Conv2D, MaxPooling, Flatten, Dense, Dropout)  
- **Adam optimizer + categorical crossentropy loss**  

kullanılmıştır.  

Notebook içerisinde markdown hücreleri ile proje adımları açıklanmıştır.  
🔹 Eğitim çıktıları: Accuracy & Loss grafiklerinin görselleştirilmesi  
🔹 Confusion Matrix ve Classification Report ile model performansı  

---

📊 Metrikler
Eğitim sonucunda elde edilen metrikler:

Eğitim Doğruluğu (accuracy): son epoch’ta 0.9684

Doğrulama Doğruluğu (val_accuracy): son epoch’ta 0.9558

Eğitim Kaybı (loss): 0.0975

Doğrulama Kaybı (val_loss): 0.1453

📈 Grafikler: Eğitim ve doğrulama sürecinde loss ve accuracy eğrileri başarıyla çizdirilmiştir.

🔲 Confusion Matrix: Modelin sınıflar arasında karışıklıklar yaşadığını fakat genel doğruluğun yüksek olduğunu göstermektedir.

📑 Classification Report: Her sınıf için precision, recall ve f1-score çıktıları alınmış, modelin genel doğruluk oranı %95.58 olarak bulunmuştur.

---

## 📎 Ekler
Bu proje kapsamında:  
- **GPU üzerinde eğitim (Tesla T4)**  
- **Model kaydetme (`.h5`)**  
- **Rastgele test görsellerinde tahmin**  

ekstra olarak gerçekleştirilmiştir.  

Gelecekte yapılabilecek eklemeler:  
- Transfer Learning (VGG16, ResNet vb.)  
- Streamlit ile web arayüzü  
- Mobil entegrasyon  

---

## 📌 Sonuç ve Gelecek Çalışmalar
Bu proje, derin öğrenme ile sağlık verilerinin işlenmesinin potansiyelini göstermektedir.  

📌 Gelecek için planlanan adımlar:  
- Daha büyük veri setleri ile modelin yeniden eğitilmesi  
- Klinik kullanım için gerçek zamanlı tahmin sistemi  
- Kullanıcı dostu arayüzler (web & mobil)  

---

## 🔗 Linkler
- 📓 Proje Kaggle Notebook: [Derin Öğrenme Proje - Hafzanur Köse](https://www.kaggle.com/code/hafzanurkose/derin-ogrenme-proje)  
