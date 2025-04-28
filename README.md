# Capstone Project Module 2: AWS SaaS Sales Loss Analysis
Proyek ini bertujuan untuk menganalisis penyebab kerugian pada penjualan layanan AWS berbasis SaaS. Meskipun tidak semua transaksi merugi, nilai kerugian tersebut cukup signifikan untuk berdampak pada keseluruhan profitabilitas perusahaan. Sebagai seorang data analyst, tugas utama dalam proyek ini adalah memahami faktor-faktor penyebab kerugian berdasarkan data historis, mengidentifikasi pola, dan memberikan rekomendasi berbasis data.

## Problem Statement
AWS mengalami sejumlah transaksi dengan profit negatif yang dapat menggerus total margin keuntungan perusahaan.
Pertanyaan-pertanyaan yang ingin dijawab:
- Faktor apa saja yang menyebabkan kerugian?
- Produk, kota, segmen pelanggan, atau wilayah mana yang mendominasi kerugian?
- Apakah ada hubungan antara diskon yang diberikan dengan margin profit?
  
Sebagai seorang data analyst, kita akan mencoba menjawab pertanyaan-pertanyaan tersebut.

## Objectives
- Menganalisis distribusi profit dan margin profit.
- Menghitung proporsi transaksi menguntungkan vs merugi.
- Mengidentifikasi produk, wilayah, dan segmen dengan kontribusi kerugian terbesar.
- Menganalisis hubungan antara diskon dan profit margin.

## Methodology
1. Data Preparation
  - Menghapus kolom tidak relevan.
  - Menangani outlier untuk Sales, Discount, dan Profit.
  - Mengecek konsistensi data.
2. Exploratory Data Analysis (EDA)
  - Visualisasi distribusi profit dan margin profit.
  - Analisis proporsi transaksi untung vs rugi.
  - Breakdown kerugian berdasarkan segmentasi pelanggan, produk, kota, dan wilayah.
3. Statistical Testing
  - Melakukan uji hipotesis korelasi antara diskon dan margin profit.
4. Trend Analysis
  - Analisis tren diskon dan transaksi rugi secara bulanan.
5. Conclusions and Recommendations
  - Menyusun kesimpulan utama dan actionable recommendation.

## Key Findings
- Diskon tinggi berhubungan signifikan dengan margin profit negatif. Hasil uji hipotesis menunjukkan bahwa semakin besar diskon, semakin rendah margin profit.
- Paris merupakan kota dengan kerugian tertinggi di wilayah EMEA.
- Produk-produk tertentu berulang kali menyumbang kerugian signifikan.
- Segmen pelanggan Strategic lebih rentan mengalami kerugian dibandingkan segmen lain.

## Conclusions and Recommendations
**Conclusions**
- Kerugian cukup terkonsentrasi pada wilayah dan produk tertentu.
- Diskon besar cenderung menggerus margin profit.
- Segmen pelanggan tertentu memerlukan pendekatan khusus dalam pemberian diskon.
  
**Recommendations**
- Evaluasi skema diskon, terutama untuk kota-kota dan produk dengan tingkat kerugian tinggi.
- Sesuaikan strategi penjualan untuk segmen pelanggan Strategic.
- Rutin monitoring dan update tren transaksi untuk mendeteksi pola kerugian.


