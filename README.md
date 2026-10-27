# Tugas UTS Web Programming - Rekap Nilai Mahasiswa

Project web sederhana untuk rekap nilai mahasiswa. Dibuat pakai PHP Native dengan template AdminLTE 4 (Bootstrap 5).

## Fitur Aplikasi

* **Foto & Nama**: Tampilan foto profil mahasiswa bersanding dengan nama lengkap di dalam satu kolom tabel.

* **Cari & Filter**:

  * Cari mahasiswa berdasarkan nama.

  * Filter data berdasarkan predikat kelulusan.

* **Sorting**: Bisa urutkan data (A-Z / Z-A & nilai terendah/tertinggi) untuk kolom NIM, Nama, dan Nilai.

* **Pagination**: Pilihan limit data per halaman (5, 10, 15) lengkap dengan nav halaman.

* **CRUD (Modal)**: Tambah, edit, dan hapus data mahasiswa langsung via Modal Bootstrap tanpa reload pindah halaman.

## Stack yang Dipakai

* PHP 8

* MySQL / MariaDB

* AdminLTE 4 & Bootstrap 5

* Bootstrap Icons

## Struktur Folder

```
├── css/              # stylesheet AdminLTE / custom
├── js/               # script javascript
├── img/              # folder foto mahasiswa & defaultphoto.jpg
├── koneksi.php       # koneksi ke database
├── index.php         # halaman utama tabel & filter
├── inputnilai.php    # proses simpan data baru & upload foto
├── editnilai.php     # proses update data & foto
└── hapusnilai.php    # proses hapus data
```
