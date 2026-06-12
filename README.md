# ANALISIS RISIKO KREDIT PADA HOME EQUITY LOANS MENGGUNAKAN INTEGRASI K-MEANS, LINEAR DISCRIMINANT ANALYSIS, DAN ARTIFICIAL NEURAL NETWORK

Repository ini dibuat untuk memenuhi tugas Ujian Akhir Semester mata kuliah Machine Learning. Proyek ini membahas analisis risiko kredit pada dataset Home Equity Loans atau HMEQ dengan menggunakan pendekatan unsupervised learning dan supervised learning.

## Deskripsi Proyek

Penelitian ini bertujuan untuk menganalisis risiko kredit nasabah berdasarkan data pinjaman Home Equity. Analisis dilakukan melalui beberapa tahap, yaitu eksplorasi data, preprocessing, clustering menggunakan K-Means, klasifikasi menggunakan Linear Discriminant Analysis, klasifikasi menggunakan Artificial Neural Network, serta analisis integrasi dari hasil clustering dan klasifikasi.

## Metode yang Digunakan

Metode yang digunakan dalam proyek ini meliputi:

1. Exploratory Data Analysis
2. Data Preprocessing
3. K-Means Clustering
4. Linear Discriminant Analysis
5. Artificial Neural Network
6. External Cluster Validation
7. Integration Analysis

## Dataset

Dataset yang digunakan adalah HMEQ yang berisi data pinjaman Home Equity. Dataset ini memiliki variabel yang berkaitan dengan karakteristik peminjam, nilai pinjaman, nilai properti, riwayat kredit, dan status risiko kredit.

Target utama dalam dataset ini adalah variabel BAD, yaitu:

- BAD = 0 menunjukkan nasabah yang berhasil melunasi pinjaman
- BAD = 1 menunjukkan nasabah mengalami gagal bayar atau default

## Struktur Repository

```text
uas-machine-learning-hmeq/
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
├── data/
