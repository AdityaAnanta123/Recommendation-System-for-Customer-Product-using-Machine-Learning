# 📦 Recommendation System for Customer Product using Machine Learning

Proyek ini bertujuan untuk membangun sebuah sistem rekomendasi produk yang dapat memberikan saran produk yang relevan kepada pelanggan berdasarkan pola interaksi historis mereka. Dengan menggunakan pendekatan Machine Learning, sistem ini diharapkan dapat meningkatkan pengalaman pelanggan, memperkuat loyalitas, serta mendorong peningkatan penjualan.

## 📊 Tujuan Proyek

- Menganalisis perilaku pembelian pelanggan
- Membuat model sistem rekomendasi berbasis collaborative filtering
- Memberikan rekomendasi produk yang dipersonalisasi bagi setiap pelanggan

---

## ⚙️ Teknologi yang Digunakan

### 1. **Python**
Digunakan sebagai bahasa pemrograman utama karena fleksibilitas dan dukungan pustaka data science dan machine learning yang luas.

### 2. **Pandas & NumPy**
Digunakan untuk manipulasi data, transformasi dataframe, dan operasi numerik.

### 3. **Scikit-learn**
Digunakan untuk preprocessing dan evaluasi dasar. Pustaka ini menyediakan berbagai algoritma machine learning dan alat bantu analisis data.

### 4. **TensorFlow / Keras**
Digunakan untuk membangun dan melatih model neural collaborative filtering. Model ini mempelajari representasi vektor pelanggan dan produk untuk menghasilkan prediksi yang akurat.

### 5. **Jupyter Notebook**
Sebagai lingkungan interaktif untuk eksplorasi data, visualisasi, dan eksperimen dengan model.

---

## 🧠 Pendekatan Model

Proyek ini menggunakan pendekatan **Neural Collaborative Filtering** yang merupakan gabungan dari:

- **Matrix Factorization (MF)**: Mengurangi dimensi dari matriks user-item menjadi representasi vektor laten.
- **Multi-Layer Perceptron (MLP)**: Untuk menangkap interaksi non-linear antara user dan item embedding.

Model dirancang untuk memprediksi kemungkinan seorang pengguna membeli suatu produk berdasarkan data historis.

---

## 📈 Hasil yang Diperoleh

Setelah proses pelatihan dan validasi model, berikut beberapa hasil yang diperoleh:

- **Akurasi Rekomendasi**: Model menunjukkan performa yang baik dalam memprediksi produk yang kemungkinan besar akan disukai oleh pelanggan.
- **Model disimpan** dalam format `.h5` sebagai file `recommender_model.h5`, siap untuk di-deploy atau digunakan untuk inferensi lebih lanjut.
- **Skalabilitas**: Model dapat ditingkatkan lebih lanjut dengan data pelanggan dan produk yang lebih besar.

---

## 🚀 Cara Menjalankan

1. **Clone repository**
   ```bash
   git clone https://github.com/AdityaAnanta123/Recommendation-System-for-Customer-Product-using-Machine-Learning.git
   ```

2. **Buka Notebook**
   Gunakan Jupyter Notebook atau Google Colab untuk membuka file:
   ```
   Recommended_System_For_Bangkit.ipynb
   ```

3. **Jalankan Sel Notebook**
   Ikuti alur preprocessing, pelatihan model, dan prediksi dari awal hingga akhir.
