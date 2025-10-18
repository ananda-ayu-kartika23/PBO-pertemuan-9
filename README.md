# 🧾 Tugas Pertemuan 9 — Pembuatan Laporan dengan JasperReports

Proyek ini merupakan implementasi **pembuatan laporan berbasis JasperReports** menggunakan **bahasa pemrograman Java** dengan koneksi ke **database PostgreSQL**.  
Aplikasi dikembangkan menggunakan **NetBeans IDE** dan laporan didesain menggunakan **JasperSoft Studio**, **bukan** plugin bawaan NetBeans.

---

## 📚 Deskripsi Proyek

Aplikasi ini menampilkan data dari tabel **`mata_kuliah`** dan menyediakan fitur:

- Menampilkan data dari database ke **JTable**  
- Melakukan operasi **CRUD (Create, Read, Update, Delete)**  
- Mencetak laporan data menggunakan **JasperReports**

  ## 📋 Fitur Utama

1. **Tampilkan Data Penduduk**  
   Menampilkan semua data dari tabel `penduduk` di database PostgreSQL ke dalam tabel (`JTable`) GUI.

2. **Tambah Data (Simpan)**  
   Membuka form dialog untuk menambahkan data baru ke database.

3. **Perbarui Data**  
   Memungkinkan pengguna untuk memperbarui data penduduk yang dipilih.

4. **Hapus Data**  
   Menghapus data penduduk yang dipilih dari database.

5. **Cetak Laporan**  
   Menggunakan file `ReportPenduduk.jasper` (JasperReports) untuk mencetak atau menampilkan laporan data penduduk dalam format laporan siap cetak.
