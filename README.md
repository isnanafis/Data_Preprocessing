# 🥗 Food Waste Data Preprocessing

## 📌 Deskripsi
Repositori ini berisi *pipeline* prapemrosesan data operasional dapur komersial. Tujuannya adalah membersihkan data mentah agar siap digunakan untuk pemodelan prediksi limbah makanan. 

## ⚙️ Alur Pemrosesan (Pipeline)
1. Pembersihan struktur dan standardisasi nama kolom.
2. Penyesuaian tipe data dan format teks.
3. Penanganan data kosong (*Missing Values*) dengan Imputasi & *Forward/Backward Fill*.
4. *Feature Engineering* (Ekstraksi waktu).
5. *Encoding* kategori dan *Scaling* (Normalisasi) angka.

## 🚀 Cara Menjalankan
1. Pastikan Python terinstal beserta library: `pandas`, `numpy`, dan `scikit-learn`.
2. Letakkan file dataset `food_waste_dataset.csv` yang bisa didownload di [Messy Food Waste Prediction Dataset (Kaggle)](https://www.kaggle.com/competitions/messy-food-waste-prediction-dataset/data?select=train.csv) di folder yang sama dengan notebook.
3. Jalankan file `preprocessing_pipeline.ipynb` dari atas ke bawah.
