README kamu sudah cukup bagus, tapi masih bisa dibuat **lebih rapi, formal, dan “nilai A”** 😄
Aku bantu revisi versi yang lebih profesional dan siap langsung kamu pakai di GitHub:

---

# 📚 UTS Pemrograman Web 2

## Sistem Manajemen Kategori Buku

## 👤 Data Diri

* **Nama**: Anis Nadhirotul Mustafida
* **NIM**: 60324043

---

## 📖 Deskripsi Aplikasi

Aplikasi ini merupakan sistem berbasis web yang digunakan untuk mengelola data kategori buku pada perpustakaan.
Sistem ini dibangun menggunakan **PHP** dan **MySQL**, serta menerapkan konsep **CRUD (Create, Read, Update, Delete)**.

Melalui aplikasi ini, pengguna dapat:

* Menambahkan kategori buku
* Melihat daftar kategori
* Mengubah data kategori
* Menghapus kategori

---

## ⚙️ Fitur Utama

* ✅ Tambah Data Kategori
* ✅ Tampilkan Data Kategori
* ✅ Edit Data Kategori
* ✅ Hapus Data Kategori
* ✅ Validasi input sederhana

---

## 🚀 Cara Menjalankan Project

1. Import database:

   * Buka **phpMyAdmin**
   * Import file `database_backup.sql`

2. Jalankan server:

   * Gunakan XAMPP / Laragon

3. Letakkan project:

   * Simpan folder ke dalam `htdocs`

4. Akses aplikasi:

```
http://localhost/uts_60324043
```

---

## 🗂️ Struktur Project

```
├── config/
│   └── koneksi.php
├── create.php
├── edit.php
├── delete.php
├── index.php
└── database_backup.sql
```

---

## 🔄 Alur Sistem

1. User membuka halaman utama (`index.php`)
2. Sistem menampilkan data kategori dari database
3. User dapat:

   * Menambah data → `create.php`
   * Mengedit data → `edit.php`
   * Menghapus data → `delete.php`
4. Setelah proses, sistem kembali ke halaman utama

---

## ⚠️ Catatan

* Pastikan database sudah terhubung dengan benar
* Error seperti **"ID tidak valid"** terjadi jika parameter `id` tidak ditemukan pada URL

---

## 🔗 Repository

[https://github.com/username/uts-pemrograman-web-2-60324043](https://github.com/username/uts-pemrograman-web-2-60324043)

---

Kalau kamu mau lebih maksimal lagi, aku bisa bantu:

* Tambahin **screenshot aplikasi (biar keren di GitHub)**
* Atau buatkan **desain UI sederhana biar tampilannya lebih menarik** 👍
