# Analisa Pengaruh Recency, Frequency, dan Monetary dalam Mengklaster Pelanggan Menggunakan Python

## Deskripsi Proyek
Proyek ini bertujuan untuk mengelompokkan pelanggan berdasarkan perilaku transaksi mereka menggunakan metode **RFM** (Recency, Frequency, Monetary) dengan Python. Analisis RFM memungkinkan perusahaan memahami lebih dalam kebutuhan pelanggan dan membantu dalam menyusun strategi pemasaran yang lebih tepat sasaran.

## Tujuan
1. Mengidentifikasi kelompok pelanggan berdasarkan karakteristik transaksi mereka menggunakan metode RFM.
2. Membantu perusahaan dalam menyusun strategi pemasaran yang efektif.
3. Memanfaatkan Python sebagai alat untuk pengolahan dan analisis data.

## Dataset
Dataset yang digunakan dalam analisis ini diambil dari [Kaggle - Transaction Data](https://www.kaggle.com/datasets/vipin20/transaction-data). Dataset ini berisi informasi transaksi pelanggan yang mencakup detail waktu, frekuensi, dan nilai pembelian.

## Metodologi
1. **Data Preprocessing**: Pemrosesan awal data, termasuk pengecekan tipe data dan menangani nilai yang hilang.
2. **Penghitungan Nilai RFM**:
   - **Recency**: Menghitung waktu sejak transaksi terakhir setiap pelanggan.
   - **Frequency**: Menghitung jumlah transaksi pelanggan.
   - **Monetary**: Menghitung total nilai transaksi yang dihabiskan oleh pelanggan.
3. **Skor RFM**: Mengonversi nilai RFM ke dalam skor komparatif untuk mengidentifikasi segmen pelanggan.
4. **Klasterisasi Pelanggan**: Membagi pelanggan ke dalam beberapa klaster (Champions, Loyal Customers, Potential Customers, At Risk, Lost, Promising, Uncategorize).
5. **Visualisasi**: Menyediakan grafik untuk menggambarkan distribusi nilai Recency, Frequency, Monetary, dan klasterisasi.

## Instalasi
1. Clone repositori ini:
   ```bash
   git clone https://github.com/Nilaisfyhana1/Analisa-RFM-Dalam-Mengklaster-pelanggan-menggunakan-python.git
