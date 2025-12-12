# Project Title: Bike Sales Analysis

## 📌 Deskripsi Singkat
Analisis ini bertujuan untuk memahami pengaruh penjualan sepeda dan pendapatan customer dari berbagai negara, usia dan pendidikan. Yang dimana ini dapat membantu meningkatkan strategi bisnis.

## 🧰 Tools / Teknologi
- Excel

## 📂 Struktur Folder
- File Dataset
- Dashboard

## 📊 Insight Utama
- Pelanggan dengan pendapatan tinggi lebih cenderung membeli sepeda. Ini bisa jadi untuk strategi pricing atau target marketing premium.
- Target utama adalah usia produktif (dewasa). Promosi dan penawaran khusus harus fokus ke segmen ini.
- Sepeda banyak dibeli oleh pelanggan yang tinggal dekat dengan tempat kerja/aktivitas. Segmentasi "short commute" sangat relevan untuk campaign sepeda urban.

## 🔧 Cara Analisis Dilakukan
Jelaskan step-by-step seperti:
1. Menghapus duplikasi data.
2. Data Cleaning
   - Memberi nama pada kolom "Marital Status" menggunakan rumus IF().
   - Memberi nama pada kolom "Gender" menggunakan rumus IF().
   - Mengubah format kolom "Income" menjadi currency.
   - Mengubah value pada kolom "Commute Distance" (+10 Miles) menjadi "More Than 10 Miles" supaya bisa diurutkan didalam pivot table.
   - Membuat kolom baru "Age Brackets" untuk mengelompokkan usia berdasarkan rentang tertentu.
3. Exploratory Data Analysis (Pivot Table)
   - Analisis pembelian sepeda berdasarkan gender.
   - Analisis pembelian sepeda berdasarkan usia.
   - Analisis pembelian sepeda berdasarkan jarak tempuh customer.
4. Visualisasi (dashboard)
   - <img src="Bike Sales Dashboard.jpg" width="800">
5. Kesimpulan
   Pembelian sepeda paling banyak terjadi pada kalangan orang dewasa berpendapatan tinggi yang berkomuter jarak pendek.

## 📁 Dataset
- Sumber dataset: Kaggle
- Jumlah baris: 1000
- Jumlah kolom: 14

## 🧠 Kesimpulan
- Profil Pelanggan yang Membeli Sepeda Lebih Jelas Teridentifikasi
  Analisis menunjukkan bahwa pembeli sepeda umumnya berasal dari kelompok dengan pendapatan lebih tinggi, berusia dewasa (middle age), dan memiliki jarak komuter yang relatif pendek. Informasi ini membantu memahami siapa target pasar utama.
- Pendapatan Memiliki Pengaruh Signifikan terhadap Keputusan Pembelian
  Data memperlihatkan bahwa kelompok pembeli memiliki pendapatan rata-rata lebih tinggi dibandingkan non-pembeli, baik pada kategori pria maupun wanita. Ini menunjukkan bahwa daya beli menjadi faktor penting dalam keputusan membeli sepeda.
- Usia Menjadi Faktor Utama dalam Segmentasi Pembeli
  Konsumen yang berada pada kategori usia dewasa menunjukkan tingkat pembelian tertinggi. Segmentasi ini penting untuk strategi pemasaran yang lebih terarah pada kelompok usia yang paling responsif.
- Kebiasaan Komuter Memberi Gambaran Kebutuhan Pengguna
  Pelanggan yang membeli sepeda mayoritas melakukan perjalanan jarak pendek (0–1 miles). Ini mengindikasikan bahwa sepeda lebih diminati sebagai alat transportasi jarak dekat, bukan perjalanan jauh.
- Dashboard Menyediakan Alat Eksplorasi Demografis
  Meskipun variabel seperti status pernikahan, pendidikan, dan region tidak divisualisasikan secara langsung, dashboard menyediakan filter untuk mengeksplorasi hubungan antara demografi tersebut dan pembelian sepeda.
- 

## 💡 Rekomendasi Bisnis (Opsional)
- Fokus pada kelompok berpendapatan menengah ke atas
- Menargetkan usia dewasa
- Menonjolkan manfaat sepeda untuk komuter jarak dekat
- Mengembangkan campaign berbasis lokasi menggunakan filter region
