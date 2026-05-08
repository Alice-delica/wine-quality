# Wine Quality Prediction Analysis

Proyek ini bertujuan untuk membangun model klasifikasi machine learning yang mampu memprediksi kualitas anggur (*wine quality*) berdasarkan karakteristik fisikokimia. Analisis ini menggunakan dataset yang mencakup berbagai fitur kimiawi seperti tingkat keasaman, kandungan gula, kadar alkohol, dan pH.

## 📌 Gambaran Umum
Prediksi kualitas anggur merupakan tantangan dalam industri karena penilaian subjektif manusia seringkali bervariasi. Proyek ini mencoba mendekati penilaian kualitas melalui data objektif menggunakan pendekatan statistik dan algoritma pembelajaran mesin.

## 🛠️ Metodologi & Alur Kerja

1. **Eksplorasi Data (EDA):** Menganalisis distribusi fitur dan korelasi antar variabel untuk memahami karakteristik dataset.
2. **Pra-pemrosesan Data:**
   - Penanganan nilai yang hilang menggunakan **Imputasi Median** untuk menjaga stabilitas data terhadap *outlier*.
   - **Feature Scaling** menggunakan `StandardScaler` untuk menyamakan skala fitur sehingga model tidak terbiaskan oleh variabel dengan rentang nilai besar.
3. **Validasi Internal:** Membagi data menjadi *Training Set* (80%) dan *Validation Set* (20%) untuk menguji keandalan model sebelum diaplikasikan pada data uji sesungguhnya.
4. **Pemodelan:** Menggunakan algoritma **Random Forest Classifier** karena kemampuannya dalam menangani hubungan non-linear yang kompleks dan ketangguhannya terhadap *overfitting*.

## 📊 Hasil Evaluasi
Model akhir memberikan performa yang stabil pada data validasi. Metrik yang digunakan untuk mengukur keberhasilan model adalah:
- **Akurasi:** (Masukkan angka akurasi kamu di sini, misal: 0.82 atau 82%)
- **Confusion Matrix:** Digunakan untuk melihat seberapa tepat model mengklasifikasikan setiap level kualitas.

## 📂 Struktur Repositori
- `notebooks/`: Berisi file `.ipynb` dengan penjelasan langkah demi langkah.
- `data/`: Dataset training dan testing yang digunakan.
- `output/`: Hasil prediksi final dalam format CSV.

## 🚀 Cara Menjalankan
1. Clone repositori ini.
2. Pastikan Anda memiliki library yang diperlukan: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, dan `seaborn`.
3. Jalankan notebook di folder `notebooks/`.

---
*Proyek ini dikembangkan sebagai bagian dari studi Analisis Data dan Sains Data.*
