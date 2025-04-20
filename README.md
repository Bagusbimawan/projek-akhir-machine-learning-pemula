# Proyek Machine Learning - Analisis Clustering dan Klasifikasi

## Deskripsi Proyek
Proyek ini terdiri dari dua bagian utama:
1. Analisis Clustering untuk segmentasi data retail online
2. Klasifikasi hasil clustering untuk prediksi segmen

## Dataset

### Online Retail Dataset
- File: `Online-Retail.csv`
- Dataset ini berisi transaksi retail online yang mencakup data kategorikal dan numerikal
- Fitur utama meliputi:
  - Quantity: Jumlah item yang dibeli
  - UnitPrice: Harga per unit item
  - Dan fitur kategorikal lainnya

### Dataset Klasifikasi
- File: `dataset_klasifikasi.csv`
- Dataset ini merupakan hasil dari proses clustering yang digunakan untuk klasifikasi
- Berisi fitur-fitur yang sama dengan dataset retail namun sudah memiliki label cluster

## Implementasi

### 1. Clustering
- Menggunakan algoritma K-Means untuk segmentasi pelanggan
- Preprocessing data termasuk:
  - Normalisasi fitur numerik
  - Encoding fitur kategorikal
- Evaluasi menggunakan silhouette score
- Visualisasi distribusi cluster

### 2. Klasifikasi
- Menggunakan hasil clustering sebagai label
- Pembagian data: 80% training, 20% testing
- Implementasi model klasifikasi untuk memprediksi segmen pelanggan
- Evaluasi performa model menggunakan metrik standar

## Struktur Proyek
```
├── [Clustering]_Submission_Akhir_BMLP_Bagus_Bimawan.ipynb   # Notebook implementasi clustering
├── [Klasifikasi]_Submission_Akhir_BMLP_Bagus_Bimawan.ipynb  # Notebook implementasi klasifikasi
├── Online-Retail.csv                                        # Dataset retail original
├── dataset_klasifikasi.csv                                  # Dataset hasil clustering
└── README.md                                               # Dokumentasi proyek
```

## Hasil dan Kesimpulan
- Berhasil melakukan segmentasi pelanggan menggunakan K-Means clustering
- Model klasifikasi dapat memprediksi segmen pelanggan berdasarkan pola pembelian
- Analisis ini dapat membantu dalam pengambilan keputusan bisnis dan strategi pemasaran

## Pengembang
Bagus Bimawan