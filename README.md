# der-n-ogrenme-proje
# 🧠 Brain Tumor Detection with Deep Learning  
**Akbank Derin Öğrenme Bootcamp Projesi**

Bu proje, Kaggle üzerinde yer alan **Brain Tumor MRI Dataset** kullanılarak gerçekleştirilmiştir. Amaç, MRI görüntülerinden beyin tümörlerini tespit eden bir **Convolutional Neural Network (CNN)** modeli geliştirmektir.  

---

## 📂 Dataset
📌 Kullanılan veri seti: [Brain Tumor MRI Dataset (Kaggle)](https://www.kaggle.com/datasets)  

- **Training Set:** 5712 görüntü (4 sınıf)  
- **Testing Set:** 1311 görüntü (4 sınıf)  

🔹 Sınıflar:  
- Glioma  
- Meningioma  
- Pituitary  
- No Tumor  

---

## ⚙️ Model Yapısı
Proje kapsamında sıfırdan bir **CNN modeli** oluşturulmuştur.  

**Model Mimarisi:**
- `Conv2D + MaxPooling` katmanları (özellik çıkarma)  
- `Flatten` katmanı  
- `Dense (512, ReLU)` + `Dropout(0.5)`  
- Çıkış Katmanı: `Dense(4, Softmax)`  

**Model Parametreleri:**  
- Optimizer: `Adam`  
- Loss: `Categorical Crossentropy`  
- Metric: `Accuracy`  

---

## 📊 Eğitim Sonuçları
- **Train Accuracy:** %96–97  
- **Validation Accuracy:** %95 civarı  
- **Test Accuracy (evaluate):** %95.58  

📈 **Eğitim grafikleri:**  
- Accuracy ve Loss eğrileri, modelin başarılı şekilde öğrendiğini göstermektedir.  

🔲 **Confusion Matrix:**  
- Model sınıfları ayırt etmede genel olarak yüksek doğruluk sağlamıştır.  

📑 **Classification Report:**  
- Eğitim sırasında yüksek precision, recall ve f1-score değerleri elde edilmiştir.  

🖼️ **Örnek Görseller:**  
Modelin doğru/yanlış tahmin ettiği test örneklerinden görseller çıkarılmıştır.  

