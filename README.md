# Proyek Klasifikasi Gambar: [Plant Village Dataset : Detection Plant Disease]
- **Nama:** Reynaldo Arya Budi Trisna
- **Email:** reynaldstar@gmail.com
- **ID Dicoding:** reynaldoabt

---

## Deskripsi Proyek
Proyek ini adalah sistem klasifikasi gambar berbasis Deep Learning menggunakan TensorFlow. Proyek ini dirancang untuk melatih model pada dataset [Plant Village Dataset : Detection Plant Disease] dan mampu mengklasifikasikan gambar ke dalam beberapa kelas yang telah ditentukan.

---

## Fitur Proyek
1. **Data Preparation**
   - Mengunduh dan mempersiapkan dataset dari Kaggle.
   - Menampilkan informasi tentang dataset, termasuk jumlah gambar dan resolusi unik.
   - Preprocessing data dengan augmentasi gambar.
   - Dataset : https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset

2. **Modeling**
   - Membangun model CNN menggunakan TensorFlow.
   - Training model dengan EarlyStopping dan ReduceLROnPlateau untuk optimasi.

3. **Evaluation & Visualization**
   - Menampilkan kurva akurasi dan loss dari model selama proses training.
   - Menampilkan akurasi akhir dari dataset training dan validasi.

4. **Model Deployment**
   - Menyimpan model dalam format SavedModel, TensorFlow Lite, dan TensorFlow.js untuk deployment.
   - Membuat file `requirements.txt` untuk dependensi proyek.

5. **Inference**
   - Membuat fungsi prediksi untuk mengklasifikasikan gambar baru dan menampilkan hasil prediksi beserta confidence score.

---

## Langkah-Langkah Penggunaan

### 1. **Setup Lingkungan**
Jalankan perintah berikut untuk menginstal semua dependensi yang diperlukan:
```bash
pip install tensorflow tensorflowjs
```
### 2. **Unduh Dataset**
Dataset diunduh secara otomatis menggunakan API Kaggle. Pastikan untuk memiliki file kaggle.json yang valid untuk autentikasi.

### 3. Jalankan Proyek
Jalankan skrip berikut di Google Colab atau lingkungan Python lainnya:

### 4. Data Preprocessing
Dataset akan diproses secara otomatis dengan augmentasi gambar untuk dataset training.

### 5. Model Training
Latih model dengan menjalankan sel yang berisi kode model training. Hasil akhir akan divisualisasikan.

### 6. Model Deployment
Model disimpan dalam format berikut:
```
TensorFlow SavedModel (/content/drive/MyDrive/submission/saved_model)
TensorFlow Lite (/content/drive/MyDrive/submission/tflite_model/model.tflite)
TensorFlow.js (/content/drive/MyDrive/submission/tfjs_model)
```

7. Inference
Gunakan fungsi predict_image untuk melakukan klasifikasi pada gambar baru.

