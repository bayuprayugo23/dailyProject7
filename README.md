# SIPADU

## Sistem Informasi Pengaduan Fasilitas Kampus

---

## Pengertian SIPADU

SIPADU (Sistem Informasi Pengaduan Fasilitas Kampus) adalah sebuah aplikasi berbasis web yang dirancang untuk mempermudah civitas akademika dalam melaporkan, memantau, dan mengelola kerusakan fasilitas kampus secara terpusat dan transparan.

Sistem ini memungkinkan pengguna untuk menyampaikan keluhan atau laporan terkait fasilitas seperti listrik, air, AC, WiFi, ruang kelas, dan lainnya, serta memantau status penanganannya secara real-time.

---

## Fitur Sistem

Berikut adalah fitur-fitur yang tersedia dalam website SIPADU:

### 1. Autentikasi Pengguna

* Registrasi akun pengguna
* Login ke sistem
* Menampilkan identitas pengguna yang sedang aktif

---

### 2. Pembuatan Laporan

* Input judul laporan
* Pemilihan kategori fasilitas
* Input lokasi kejadian
* Penulisan deskripsi masalah
* Penentuan tingkat prioritas (rendah, sedang, tinggi, darurat)
* Input koordinat GPS (opsional)
* Upload foto kerusakan (opsional)

---

### 3. Manajemen Data Laporan

* Data laporan tersimpan ke database Supabase
* Setiap laporan terhubung dengan user melalui user_id
* Menyimpan waktu pembuatan laporan

---

### 4. Tracking Status Laporan

* Status laporan terdiri dari:

  * dikirim
  * diproses
  * diperbaiki
  * selesai
* Status dapat diperbarui sesuai proses perbaikan

---

### 5. Laporan Saya

* Menampilkan laporan berdasarkan user yang login
* Data difilter menggunakan user_id
* Memudahkan pengguna memantau laporan pribadi

---

### 6. Semua Laporan

* Menampilkan seluruh laporan dari semua pengguna
* Data ditampilkan secara global
* Mendukung transparansi sistem

---

### 7. Dashboard Statistik

* Menampilkan jumlah total laporan
* Menampilkan jumlah laporan yang sedang diproses
* Menampilkan jumlah laporan yang telah selesai

---

### 8. Realtime Update

* Data laporan dan statistik diperbarui secara otomatis
* Tidak memerlukan refresh halaman
* Menggunakan fitur realtime dari Supabase

---

### 9. Sistem Prioritas

* Laporan memiliki tingkat prioritas:

  * rendah
  * sedang
  * tinggi
  * darurat
* Digunakan untuk menentukan tingkat urgensi penanganan

---

### 10. Voting Laporan

* Pengguna dapat memberikan dukungan pada laporan
* Laporan dengan dukungan lebih tinggi dapat diprioritaskan

---

### 11. Integrasi QR Code

* Mendukung scan QR untuk input lokasi otomatis
* Mempercepat proses pembuatan laporan

---

### 12. Tracking Alur Perbaikan

* Visualisasi tahapan perbaikan:

  * dikirim → diverifikasi → diproses → diperbaiki → selesai

---

## Teknologi yang Digunakan

* HTML
* CSS
* JavaScript
* Supabase (Authentication, Database, Realtime)
* GitHub Pages (Hosting)

---

## Penutup

SIPADU merupakan solusi digital untuk meningkatkan efisiensi pelaporan fasilitas kampus. Dengan sistem ini, proses pelaporan menjadi lebih cepat, transparan, dan terorganisir sehingga dapat meningkatkan kualitas layanan fasilitas di lingkungan kampus.
