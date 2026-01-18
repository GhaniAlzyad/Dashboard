# Proyek Analisis Data: E-Commerce Public Dataset

## 📌 Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis data penjualan dari E-Commerce Public Dataset. Dashboard interaktif ini dibuat menggunakan **Streamlit** untuk memvisualisasikan hasil analisis data, yang meliputi:

1.  **Tren Penjualan Harian**: Memantau jumlah pesanan dan total pendapatan harian.
2.  **Kinerja Produk**: Mengidentifikasi produk terlaris (Best Performing) dan produk yang kurang diminati.
3.  **Demografi Pelanggan**: Melihat sebaran pelanggan berdasarkan lokasi geografis.
4.  **Analisis RFM**: Segmentasi pelanggan menggunakan metode *Recency, Frequency, dan Monetary* untuk mengidentifikasi pelanggan terbaik.

🚀 Cara Menjalankan Dashboard
Ikuti langkah-langkah di bawah ini untuk menjalankan dashboard di komputer lokal atau lingkungan pengembangan (seperti VS Code / GitHub Codespaces).

1. Persiapan Lingkungan (Environment)
Pastikan Anda sudah menginstal Python. Disarankan menggunakan Virtual Environment agar tidak mengganggu instalasi Python global.

Bash

# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
2. Instalasi Library
Install semua library yang dibutuhkan dengan menjalankan perintah berikut di terminal:

Bash

pip install -r requirements.txt
3. Menjalankan Aplikasi Streamlit
Masuk ke folder dashboard terlebih dahulu, lalu jalankan perintah streamlit run:

Bash

cd dashboard
streamlit run dashboard.py
4. Akses Dashboard
Setelah perintah di atas dijalankan, dashboard akan otomatis terbuka di browser Anda. Jika tidak, buka browser dan akses alamat berikut: http://localhost:----

Catatan: File main_data.csv yang berada di dalam folder dashboard adalah hasil olahan data yang telah dikompresi/dibersihkan untuk mempercepat proses loading dashboard.
