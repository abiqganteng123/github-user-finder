# GitHub User Finder

**GitHub User Finder** adalah aplikasi web interaktif untuk mencari dan menampilkan informasi profil pengguna GitHub berdasarkan *username*. Dibangun menggunakan **React**, **Material-UI**, dan **Axios**, aplikasi ini mengusung desain **Material 3 Dark** dengan antarmuka responsif, animasi halus, dan pengalaman pengguna modern.

![Pratinjau Website](https://i.postimg.cc/nzxfQB9F/Screenshot-2025-06-06-03-18-43-877-mark-via-gp.jpg)  
*Pratinjau website dengan tema gelap dan hasil pencarian pengguna.*

## Ringkasan Proyek

Aplikasi ini memungkinkan pengguna untuk:
- Mencari profil GitHub dengan memasukkan *username*.
- Menampilkan detail seperti nama, bio, lokasi, jumlah repositori publik, pengikut (*followers*), dan yang diikuti (*following*).
- Melihat avatar pengguna dan mengakses profil GitHub melalui tombol tautan.
- Menikmati antarmuka responsif dengan animasi menarik dan tema gelap modern.

## Fitur Utama

- **Pencarian Pengguna**: Cari profil GitHub dengan cepat menggunakan *username*.
- **Tampilan Profil**: Menampilkan informasi lengkap seperti nama, bio, lokasi, dan statistik pengguna.
- **Desain Responsif**: Antarmuka yang menyesuaikan dengan berbagai ukuran layar.
- **Tema Gelap**: Desain berbasis Material 3 dengan estetika modern dan nyaman untuk mata.
- **Integrasi API**: Menggunakan GitHub API untuk mengambil data pengguna secara real-time.

## Teknologi yang Digunakan

- **React**: Library JavaScript untuk membangun antarmuka pengguna.
- **Material-UI**: Komponen UI untuk desain Material 3 yang konsisten.
- **Axios**: Untuk melakukan permintaan HTTP ke GitHub API.
- **CSS**: Styling kustom untuk animasi dan responsivitas.

## Struktur Direktori

```plaintext
github-user-finder/
├── public/
│   └── index.html       # File utama untuk aplikasi
├── src/
│   ├── components/      # Komponen React
│   ├── styles/         # File CSS untuk styling
│   ├── App.js          # Komponen utama aplikasi
│   └── index.js        # Entry point aplikasi
├── info.md             # Dokumentasi proyek (file ini)
├── package.json        # Konfigurasi dependensi dan skrip
└── README.md           # Dokumentasi utama proyek