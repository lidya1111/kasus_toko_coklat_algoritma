🍫 USER MANUAL – APLIKASI INVENTORI TOKO COKELAT
---
📌 1. Deskripsi Program

Aplikasi ini adalah program berbasis Python untuk mengelola data stok cokelat di toko. Program ini dirancang untuk menyimpan, memperbarui, dan menampilkan data cokelat berdasarkan jenis, berat, dan stok. Semua data akan disimpan dalam file inventori_coklat.json.

---

💻 2. Persyaratan Sistem
Python versi 3.6 atau lebih tinggi
Dapat dijalankan melalui:
Terminal / VS Code (Windows/macOS/Linux)
Google Colab

---

📂 3. Struktur File
Nama File	Keterangan
inventori_coklat.py	File utama berisi seluruh kode program
inventori_coklat.json	File penyimpanan data cokelat dalam format JSON
user_manual.md	Dokumentasi panduan penggunaan program

---

▶️ 4. Cara Menjalankan Program
💻 Via Terminal / VS Code
python inventori_coklat.py
☁️ Via Google Colab
1. Upload file inventori_coklat.py
2. Jalankan sel program
3. File inventori_coklat.json akan otomatis dibuat

---

🧾 5. Panduan Menu Program
=== Menu Inventori Toko Cokelat ===
1. Tambah Cokelat
2. Lihat Semua Cokelat
3. Edit Stok
4. Hapus Cokelat
5. Laporan Stok
6. Simpan & Keluar
   
No	Menu	Deskripsi
1	Tambah Cokelat	Memasukkan data cokelat baru: kode, nama, jenis (dark/milk/white), berat, stok
2	Lihat Semua	Menampilkan semua data cokelat dan jumlah stok masing-masing
3	Edit Stok	Mengubah jumlah stok cokelat berdasarkan kode
4	Hapus Cokelat	Menghapus data cokelat berdasarkan kode
5	Laporan Stok	Menampilkan daftar cokelat dari stok terbanyak ke terkecil
6	Simpan & Keluar	Menyimpan data ke file JSON dan keluar dari program

---

📥 6. Format Input
Field	Format	Contoh
Kode	String tanpa spasi	CKT001
Nama	String bebas	Choco Crunch
Jenis	Pilihan (dark/milk/white)	dark
Berat	String dengan satuan gram	100
Stok	Bilangan bulat positif (int)	25

---

⚙️ 7. Fitur Optimasi & Validasi
✅ Simpan data menggunakan JSON
✅ Komentar kode lengkap
✅ Validasi kode unik (tidak bisa dobel)
✅ Optimasi waktu eksekusi pakai time.time()
✅ Struktur data fleksibel (list of dictionaries)
✅ Modular, mudah dikembangkan ke database

---

📝 8. Catatan Tambahan
File inventori_coklat.json otomatis terupdate saat memilih Simpan & Keluar
Jika file JSON belum tersedia, akan dibuat otomatis
Jangan edit file .json secara manual

---

🚀 9. Saran Pengembangan (Opsional)
Filter berdasarkan jenis cokelat
Ekspor laporan stok ke .csv
Tambahkan validasi input berat agar hanya angka
Tambah sistem kategori harga atau diskon
