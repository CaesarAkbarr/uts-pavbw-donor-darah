# Pusat Informasi Kegiatan Donor Darah (Studi Kasus B)

Repositori ini berisi proyek Ujian Tengah Semester (UTS) mata kuliah **Pengembangan Aplikasi Visual Berbasis Web (PAVBW)**, Program Studi D3 Sistem Informasi, Fakultas Sains & Teknologi, Universitas Teknologi Yogyakarta.

Aplikasi web ini dibangun murni menggunakan **HTML5 semantik** tanpa dependensi framework CSS/JS eksternal untuk menyajikan portal terpusat kegiatan donor darah relawan.

---

## Identitas Mahasiswa

- **Nama:** Caesar Akbar Hazimul Fikri
- **NIM:** 3253111006
- **Program Studi:** D3 Sistem Informasi
- **Fakultas:** Sains & Teknologi
- **Perguruan Tinggi:** Universitas Teknologi Yogyakarta (UTY)

---

## Fitur Utama

1. **Halaman Beranda (`index.html`)**
   - Header semantik berisi judul portal dan menu navigasi.
   - Ringkasan tujuan website informasi donor darah.
   - Dokumentasi foto kegiatan sebelumnya menggunakan elemen `<figure>` dan `<figcaption>`.
   - Media edukasi pemutaran video lokal donor darah (`<video controls>`).

2. **Halaman Informasi & Jadwal (`info.html`)**
   - Daftar syarat fisik pendonor menggunakan unordered list (`<ul>`).
   - Alur 4 tahap proses donor darah menggunakan ordered list (`<ol>`).
   - Tabel jadwal pelaksanaan donor darah mencakup tanggal, waktu, lokasi, dan target kantong.
   - Sematan peta interaktif lokasi kegiatan (Kampus 1 UTY) via `<iframe>` Google Maps.

3. **Halaman Formulir Pendaftaran (`daftar.html`)**
   - Dikelompokkan ke dalam 3 bagian menggunakan `<fieldset>` dan `<legend>` (Data Diri, Jadwal & Riwayat Medis, serta Persetujuan).
   - Validasi input formulir client-side native (`required`, tipe email/tel/number, batas min/max).
   - Pilihan eksklusif jenis kelamin via radio button dengan atribut `name` yang sama.
   - Kotak centang persetujuan syarat kesehatan (`checkbox`).
   - Tombol pengiriman data (`Submit`) metode GET serta tombol reset pembersih formulir.

---

## Struktur Berkas

```text
UTS/
├── asset/
│   ├── edukasi-donor.mp4       # Video edukasi donor darah lokal
│   └── kegiatan-donor.jpg      # Foto dokumentasi kegiatan
├── daftar.html                 # Halaman form pendaftaran calon pendonor
├── index.html                  # Halaman beranda utama portal
├── info.html                   # Halaman jadwal, alur, syarat, dan peta
└── README.md                   # Dokumentasi proyek
```

---

## Cara Menjalankan Proyek

1. **Kloning Repositori:**
   ```bash
   git clone https://github.com/CaesarAkbarr/uts-pavbw-donor-darah.git
   cd uts-pavbw-donor-darah
   ```

2. **Membuka di Browser:**
   - Cukup buka file `index.html` langsung menggunakan browser modern pilihan Anda (Google Chrome, Microsoft Edge, Mozilla Firefox, dll).
   - Tidak memerlukan web server lokal (seperti Apache/Nginx) atau dependensi package manager (npm/pip).

---

## Pratinjau Langsung (Live Demo)

Website ini dapat diakses langsung secara online melalui GitHub Pages pada tautan berikut:
`https://caesarakbarr.github.io/uts-pavbw-donor-darah/` *(opsional jika GitHub Pages telah diaktifkan)*
