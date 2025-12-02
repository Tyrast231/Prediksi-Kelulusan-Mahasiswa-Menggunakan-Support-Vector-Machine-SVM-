
# Analisis Prediksi Kelulusan Mahasiswa Menggunakan SVM

Proyek ini bertujuan untuk membangun model Machine Learning menggunakan algoritma **Support Vector Machine (SVM)** untuk memprediksi ketepatan waktu kelulusan mahasiswa.

## Deskripsi Dataset
- **Nama File:** `datakelulusanmahasiswa.xlsx - Sheet1.csv`
- **Fitur:** IPS 1-8, IPK, Umur, Jenis Kelamin, Status Nikah, Status Mahasiswa.
- **Target:** STATUS KELULUSAN (TEPAT vs TERLAMBAT).

##  Pengerjaan
1. **Setup:** Load library & dataset.
2. **EDA:** Cek distribusi IPK & korelasi fitur.
3. **Preprocessing:** Cleaning, Imputasi, Encoding, Scaling, Split Data.
4. **Modeling:** SVM Linear & RBF dengan Hyperparameter Tuning.
5. **Evaluasi:** Akurasi, Confusion Matrix, Classification Report.

## Hasil Evaluasi
- **Model Terbaik:** SVM Kernel Linear.
- **Akurasi:** ~83%.
- **Insight:** Status mahasiswa (Bekerja) adalah faktor dominan keterlambatan.

## Identitas Pembuat
- **Mata Kuliah:** Machine Learning
