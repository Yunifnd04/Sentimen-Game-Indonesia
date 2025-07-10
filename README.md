# 🎮 Sentiment Analysis of Indonesian Simulator Game Reviews

Proyek ini bertujuan untuk melakukan analisis sentimen terhadap ulasan pengguna dari Game simulator buatan Indonesia yang tersedia di Google Play Store. Analisis dilakukan menggunakan algoritma **Naive Bayes** dengan pendekatan supervised learning pada bahasa Indonesia.

## Game yang Dianalisis
4. **Angkot The Game** (`angkot_bagus.py`)

---

## Tools & Teknologi
- Python (Google Colab)
- `scikit-learn`
- `pandas`, `numpy`
- `Sastrawi` (untuk stemming Bahasa Indonesia)
- `matplotlib` & `seaborn` (visualisasi)

---

## Alur Analisis
1. **Data Collection**  
   Ulasan game diambil dari Google Play Store secara manual (CSV).
   
2. **Preprocessing Teks**  
   - Case folding  
   - Tokenizing  
   - Stopword removal  
   - Stemming (Sastrawi)
   
3. **Ekstraksi Fitur**  
   Menggunakan metode **TF-IDF** untuk mengubah teks menjadi vektor numerik.

4. **Klasifikasi**  
   Menggunakan **Multinomial Naive Bayes** untuk memprediksi sentimen (positif/negatif).

5. **Evaluasi Model**  
   - Confusion Matrix  
   - Accuracy  
   - Precision  
   - Recall  
   - F1-Score

---

## ▶️ Cara Menjalankan
Pastikan memiliki Python/google colab dan pustaka yang diperlukan:

```bash
pip install scikit-learn pandas numpy Sastrawi matplotlib seaborn
