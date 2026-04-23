# SIPADU

## Sistem Informasi Pengaduan Fasilitas Kampus

---

## Pengertian SIPADU

| Aspek       | Penjelasan                                                                   |
| ----------- | ---------------------------------------------------------------------------- |
| Nama Sistem | SIPADU (Sistem Informasi Pengaduan Fasilitas Kampus)                         |
| Deskripsi   | Sistem berbasis web untuk melaporkan dan memantau kerusakan fasilitas kampus |
| Tujuan      | Mempermudah pelaporan, meningkatkan transparansi, dan monitoring perbaikan   |
| Pengguna    | Mahasiswa, dosen, dan civitas kampus                                         |

---

## Fitur Sistem

| No | Fitur             | Deskripsi                                               |
| -- | ----------------- | ------------------------------------------------------- |
| 1  | Login & Register  | Pengguna dapat membuat akun dan masuk ke sistem         |
| 2  | Pembuatan Laporan | Input judul, kategori, lokasi, deskripsi, dan prioritas |
| 3  | Tracking Status   | Status laporan: dikirim, diproses, diperbaiki, selesai  |
| 4  | Laporan Saya      | Menampilkan laporan milik user login                    |
| 5  | Semua Laporan     | Menampilkan seluruh laporan dari semua user             |
| 6  | Dashboard         | Menampilkan statistik laporan                           |
| 7  | Realtime Update   | Data update otomatis tanpa refresh                      |
| 8  | Voting Laporan    | User dapat memberi dukungan pada laporan                |
| 9  | GPS Lokasi        | Input koordinat lokasi                                  |
| 10 | Upload Foto       | Menambahkan bukti foto kerusakan                        |
| 11 | QR Code           | Scan untuk isi lokasi otomatis                          |
| 12 | Prioritas         | Tingkat urgensi laporan (rendah–darurat)                |

---

## Teknologi yang Digunakan

| Teknologi    | Fungsi                             |
| ------------ | ---------------------------------- |
| HTML         | Struktur halaman                   |
| CSS          | Desain tampilan                    |
| JavaScript   | Logika aplikasi                    |
| Supabase     | Backend (Auth, Database, Realtime) |
| GitHub Pages | Hosting website                    |

---

## Struktur Database

| Kolom        | Tipe      | Keterangan        |
| ------------ | --------- | ----------------- |
| id           | uuid      | ID laporan        |
| user_id      | uuid      | ID user           |
| nama_pelapor | text      | Nama pelapor      |
| judul        | text      | Judul laporan     |
| kategori     | text      | Jenis fasilitas   |
| lokasi       | text      | Lokasi kejadian   |
| deskripsi    | text      | Detail masalah    |
| prioritas    | text      | Tingkat prioritas |
| status       | text      | Status laporan    |
| created_at   | timestamp | Waktu dibuat      |

---

## Alur Sistem

| Tahap | Keterangan                |
| ----- | ------------------------- |
| 1     | User login/register       |
| 2     | User membuat laporan      |
| 3     | Data disimpan ke database |
| 4     | Laporan ditampilkan       |
| 5     | Status diperbarui         |
| 6     | User memantau hasil       |

---

## Deployment

| Platform | Detail                                         |
| -------- | ---------------------------------------------- |
| Hosting  | GitHub Pages                                   |
| URL      | https://bayuprayugo23.github.io/dailyProject7/ |
| Backend  | Supabase                                       |

---

## Penutup

| Kesimpulan                                                                                                             |
| ---------------------------------------------------------------------------------------------------------------------- |
| SIPADU merupakan sistem digital yang mempermudah pelaporan fasilitas kampus secara cepat, transparan, dan terintegrasi |
