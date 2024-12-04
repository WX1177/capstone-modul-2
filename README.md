# Supermarket Customer Analysis

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis data pelanggan supermarket guna mengidentifikasi pola pembelian dan segmentasi pelanggan. Dengan menganalisis berbagai aspek seperti demografi pelanggan, pembelian produk, serta efektivitas kampanye pemasaran, proyek ini memberikan wawasan yang dapat digunakan untuk mengoptimalkan strategi penjualan dan pemasaran.

### Tujuan Analisis:
1. **Menganalisis Kinerja Produk dan Layanan**: Mengidentifikasi produk mana yang paling banyak dibeli dan potensi penjualan lainnya.
2. **Memeriksa Segmentasi Pelanggan Berdasarkan Pembelian Produk**: Menganalisis segmen pelanggan berdasarkan demografi dan pembelian produk untuk memahami pola perilaku konsumen.
3. **Menilai Efektivitas Kampanye Supermarket**: Menganalisis dampak kampanye pemasaran terhadap penjualan dan respons pelanggan.
4. **Menentukan Lokasi Optimal untuk Penjualan Produk**: Menganalisis pembelian produk melalui web, katalog, dan toko fisik untuk menentukan saluran penjualan yang paling efektif.

## Dataset
Dataset ini berisi data pelanggan supermarket, yang mencakup informasi demografis, transaksi pembelian, kampanye yang diikuti, dan banyak lagi. Kolom-kolom penting dalam dataset meliputi:
- **ID**: ID unik untuk setiap pelanggan
- **Age**: Umur pelanggan
- **Education**: Tingkat pendidikan pelanggan
- **Income**: Pendapatan tahunan pelanggan
- **NumWebPurchases**: Jumlah pembelian melalui website
- **NumCatalogPurchases**: Jumlah pembelian melalui katalog
- **NumStorePurchases**: Jumlah pembelian di toko fisik
- **AcceptedCmp1, AcceptedCmp2, ...**: Kampanye yang diikuti pelanggan
- **MntWines, MntFruits, ...**: Pengeluaran untuk kategori produk tertentu
- **Response**: Apakah pelanggan merespons kampanye (1 untuk ya, 0 untuk tidak)

## Teknik yang Digunakan
- **Python**: Digunakan untuk eksplorasi data, pembersihan, dan analisis.
  - **Pandas**: Untuk manipulasi data dan analisis statistik.
  - **Matplotlib/Seaborn**: Untuk visualisasi data (grafik bar, heatmap, pie chart).
  - **Scikit-learn**: Untuk segmentasi pelanggan dan analisis clustering.
- **Tableau**: Digunakan untuk membuat dashboard interaktif dan visualisasi data lebih lanjut.

## Instalasi dan Persiapan
Untuk menjalankan analisis ini, Anda perlu memiliki Python yang terinstal beserta beberapa pustaka yang digunakan dalam proyek ini. Ikuti langkah-langkah di bawah untuk mempersiapkan lingkungan Anda.

### Langkah-langkah:
1. **Clone repository ini**:
   ```bash
   git clone https://github.com/WX1177/supermarket-customer-analysis.git
   cd supermarket-customer-analysis
