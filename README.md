# Analysis-Retail-Data


📌 Deskripsi:

Melakukan analisis mendalam terhadap dataset transaksi ritel online dari perusahaan e-commerce yang berbasis di Inggris (UK) untuk periode Desember 2010 hingga Desember 2011. Analisis ini dirancang untuk mengevaluasi kesehatan bisnis, memahami pola perilaku konsumen, dan mengidentifikasi risiko operasional melalui data.

📊 Studi Kasus:

Perusahaan ingin mengoptimalkan strategi tahun depan dengan mempelajari histori transaksi. Fokus utama mencakup pemetaan tren musiman, identifikasi produk "bintang" vs produk yang tidak laku, serta pelacakan anomali transaksi (pembatalan dan pesanan partai besar).

⚙️ Metodologi & Fitur Kode :

Analisis dibagi menjadi 4 tahapan utama yang direpresentasikan dalam blok kode terpisah:
1. Data Preparation & Cleaning: Menangani missing values, memformat tanggal ke standar "Nama Bulan-Tahun", serta menciptakan metrik Revenue (Quantity*Price).
2. Monthly Sales Trend: Visualisasi fluktuasi pendapatan bulanan untuk melihat pengaruh musim (seasonality).
3. Product Performance Analysis: Visualisasi menggunakan grafik dinamis untuk Produk Terlaris tiap bulan dan Grafik khusus untuk Produk dengan Penjualan Terendah guna evaluasi stok gudang.
4. Anomaly & Outlier Detection: Analisis transaksi negatif (Retur/Pembatalan).Deteksi Outlier menggunakan Scatter Plot untuk mengidentifikasi pembeli VIP atau pesanan partai besar.

💡 Temuan Utama (Key Insights):

- Peak Season: Penjualan mencapai puncak tertinggi pada November 2011 akibat persiapan liburan akhir tahun.
- Data Cut-off Anomaly: Penurunan drastis pada Desember 2011 diidentifikasi sebagai anomali data (perekaman data terhenti pada tanggal 9), bukan karena penurunan performa bisnis.
- Return Impact: Adanya tren retur barang yang konsisten yang memerlukan evaluasi Quality Control.

🛠️ Teknologi yang Digunakan

- Python 3.x
- Pandas : Untuk manipulasi dan pembersihan data.
- Matplotlib : Untuk visualisasi data grafik garis, batang, dan scatter plot.
- Google Colab : Sebagai lingkungan pengembangan.
