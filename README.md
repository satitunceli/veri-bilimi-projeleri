# veri-bilimi-projeleri

İnfus Teknoloji ve Danışmanlık A.Ş.'de gerçekleştirdiğim staj sürecinde geliştirdiğim veri analizi ve makine öğrenmesi projeleri. Python, pandas, NumPy, matplotlib, seaborn ve scikit-learn kullanılarak Google Colab ortamında geliştirilmiştir.

## 📊 Projeler

### 1. Restoran Bahşiş Tahmini (`staj1 (1).ipynb`)
Restoran müşterilerine ait 244 kayıtlık veri seti üzerinde veri temizleme, aykırı değer analizi (IQR), keşifsel veri analizi ve görselleştirme çalışmaları yapılmıştır. Linear Regression ve Random Forest Regression modelleri karşılaştırılmıştır.
- **Sonuçlar:** Linear Regression (MAE: 0.62, R²: 0.54) vs Random Forest (MAE: 0.82, R²: 0.19)

### 2. Deneyim Yılına Göre Maaş Tahmini (`deneyime_göre_maaş.ipynb`)
Çalışanların deneyim yılı ile maaşları arasındaki ilişki incelenerek bir Linear Regression modeli geliştirilmiştir.
- **Sonuçlar:** MAE: 6286, R²: 0.90

### 3. SMS Spam Mesaj Sınıflandırması (`spam_mesaj_sınıflandırma.ipynb`)
5.572 kayıtlık bir metin veri setinde, mesajlar TF-IDF yöntemiyle sayısal özelliklere dönüştürülmüş ve Logistic Regression ile spam/ham sınıflandırması yapılmıştır.
- **Sonuçlar:** Accuracy: %96.8, Precision: %99.1, Recall: %76.7, F1-score: %86.5

## 🛠️ Kullanılan Teknolojiler
Python, pandas, NumPy, matplotlib, seaborn, scikit-learn, Google Colab
