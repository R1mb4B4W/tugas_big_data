1. Buka Google Colab:
Kunjungi colab.research.google.com.
2. Upload Notebook:
Klik tab Upload -> Pilih file app.ipynb yang sudah Anda download.
3. Upload Data (PENTING):
Setelah notebook terbuka, lihat menu di sebelah kiri, klik ikon Folder (Files).
Klik ikon upload (kertas dengan panah ke atas) dan upload file Coffe_sales.csv dan Coffe_sales.xlsx.
Tunggu sampai proses upload selesai.
4. Sesuaikan Path (Jika Perlu):
Cek kode bagian pd.read_csv(...) atau pd.read_excel(...). Pastikan nama filenya sesuai dengan yang Anda upload.
Contoh: df = pd.read_csv('Coffe_sales.csv')
5. Jalankan:
Klik menu Runtime > Run all (atau Ctrl + F9).
