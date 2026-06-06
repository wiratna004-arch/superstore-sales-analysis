# Superstore Sales Performance Analysis

## Tujuan
Menganalisis performa penjualan dataset Superstore 2015–2018 mencakup data cleaning, deteksi anomali, dan visualisasi dashboard.

## Tools
- Python (Pandas, NumPy) — data cleaning
- Google Colab — environment
- Looker Studio — dashboard visualisasi

## Dataset
- Sumber: Sample Superstore (Tableau Public)
- 9.800 transaksi | 21 kolom | Periode 2015–2018

## Proses Cleaning
- Deteksi anomali kolom Sales (outlier, nilai nol, negatif)
- Fix Postal Code Burlington, Vermont (11 nilai kosong → 05401)
- Drop kolom Country (tidak informatif, unique = 1)
- Konversi Order Date & Ship Date ke datetime
- Tambah kolom Ship Duration, Order Year, Month, Quarter

## Insight Utama
- Technology menjadi kategori dengan revenue tertinggi ($653.000)
- Phones dan Chairs adalah sub-kategori penyumbang revenue terbesar
- Segmen Consumer mendominasi 51% total penjualan
- Tren penjualan menunjukkan pertumbuhan dari 2015 ke 2018

## Dashboard
https://datastudio.google.com/reporting/6fb1916c-a616-40f3-961d-bc7cc1231dd1
