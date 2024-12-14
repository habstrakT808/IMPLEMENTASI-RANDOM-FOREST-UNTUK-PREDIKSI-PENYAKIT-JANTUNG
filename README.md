# Random Forest untuk Prediksi Penyakit Jantung

Proyek ini bertujuan untuk membangun model prediksi penyakit jantung menggunakan algoritma **Random Forest Classifier**. Dataset yang digunakan adalah dataset **Cleveland Heart Disease** dari UCI Machine Learning Repository. Model dikembangkan menggunakan Python dan berbagai library populer untuk pembelajaran mesin.

## Fitur Utama
- **Preprocessing Data:**
  - Mengatasi nilai hilang pada dataset.
  - Transformasi variabel kategorikal menjadi variabel dummy.
- **Optimasi Hyperparameter:**
  - Menggunakan GridSearchCV untuk menentukan parameter terbaik pada model Random Forest.
- **Evaluasi Model:**
  - Menghitung akurasi model.
  - Menampilkan laporan klasifikasi.
  - Membuat matriks kebingungan.
  - Membuat kurva ROC untuk setiap kelas target.

## Dataset
Dataset yang digunakan adalah **Cleveland Heart Disease Dataset**, yang tersedia di UCI Machine Learning Repository. Dataset ini memiliki 303 sampel dengan beberapa fitur klinis seperti usia, jenis kelamin, tekanan darah, dan hasil tes klinis lainnya.

- **Sumber:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
- **Fitur-fitur utama:**
  - `age`: Usia pasien
  - `sex`: Jenis kelamin pasien
  - `cp`: Tipe nyeri dada
  - `trestbps`: Tekanan darah istirahat
  - `chol`: Kolesterol serum
  - `thalach`: Detak jantung maksimum
  - `exang`: Angina akibat olahraga
  - `oldpeak`: Depresi ST
  - `target`: Kategori penyakit jantung (0-4)

## Instalasi
1. Clone repository ini:
   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
   ```
2. Pastikan Anda memiliki Python 3.7+ dan pip terinstal.
3. Install semua dependensi:
   ```bash
   pip install -r requirements.txt
   ```

## Struktur Proyek
- `main.py`: Kode utama proyek.
- `requirements.txt`: Daftar dependensi yang diperlukan.

## Cara Penggunaan
1. Jalankan file Python:
   ```bash
   python main.py
   ```
2. Program akan:
   - Membaca dataset.
   - Melakukan preprocessing data.
   - Melatih model Random Forest dengan optimasi hyperparameter.
   - Mengevaluasi model menggunakan akurasi, laporan klasifikasi, matriks kebingungan, dan kurva ROC.

## Hasil Evaluasi
- **Akurasi Model:** Akan dicetak di konsol setelah model dilatih.
- **Laporan Klasifikasi:** Menampilkan metrik seperti precision, recall, dan F1-score untuk setiap kelas.
- **Matriks Kebingungan:** Visualisasi matriks kebingungan menggunakan heatmap.
- **Kurva ROC:** Kurva ROC untuk setiap kelas target dengan nilai AUC.

## Library yang Digunakan
- `pandas`: Untuk manipulasi data.
- `numpy`: Untuk operasi numerik.
- `matplotlib` dan `seaborn`: Untuk visualisasi data.
- `scikit-learn`: Untuk preprocessing, pelatihan model, optimasi hyperparameter, dan evaluasi model.

## Pengembangan
Proyek ini masih dapat dikembangkan lebih lanjut dengan:
- Menggunakan model lain untuk membandingkan performa.
- Menambahkan fitur interpretasi model seperti SHAP atau LIME.
- Menyempurnakan preprocessing, misalnya dengan imputasi data hilang.

## Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE).

## Kontribusi
Kontribusi sangat dihargai! Silakan buka pull request atau buat isu jika Anda memiliki saran atau perbaikan.

## Kontak
Jika Anda memiliki pertanyaan, silakan hubungi:
- Nama: Hafiyan Al Muqaffi Umary
- Email: jhodywiraputra@gmail.com

---
**Catatan:** Pastikan Anda memiliki izin untuk menggunakan dataset ini sesuai dengan kebijakan UCI Machine Learning Repository.
