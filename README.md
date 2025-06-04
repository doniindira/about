
# 📱 My Profile

**Genggamanmu** adalah aplikasi pemesanan makanan dan minuman berbasis mobile yang memudahkan pengguna di Samarinda untuk menemukan dan memesan kuliner favorit mereka secara online. Dengan dukungan layanan antar oleh driver lokal dan standar kualitas yang tinggi, Genggamanmu hadir sebagai solusi kuliner digital masa kini.

---

## 📌 Table of Contents

- [Features](#-features)
<!-- - [Screenshots](#-screenshots) -->
- [📱 My Profile](#-my-profile)
  - [📌 Table of Contents](#-table-of-contents)
  - [✨ Features](#-features)
  - [🧰 Tech Stack](#-tech-stack)
  - [🚀 Getting Started](#-getting-started)
    - [1. Clone Repository](#1-clone-repository)
    - [2. Setup Backend (Laravel)](#2-setup-backend-laravel)
    - [3. Setup Node](#3-setup-node)
  - [📥 Download App](#-download-app)
  - [🧑‍🤝‍🧑 Join Us](#-join-us)
  - [🌐 Contact](#-contact)
  - [📄 License](#-license)
  - [🏫 About](#-about)

---

## ✨ Features

- 🔍 **Easy Ordering**  
  Temukan dan pesan makanan & minuman favorit hanya dalam beberapa klik.

- 🥗 **Healthy & Halal**  
  Semua menu telah melalui verifikasi *Halal* (MUI) & *Health Standard*.

- ⭐ **Taste Guarantee**  
  Kualitas rasa sesuai standar Samarinda Food.

- 🛍️ **Merchant Integration**  
  Merchant bisa mendaftarkan tokonya dan mengelola produk dengan mudah.

- 🛵 **Driver Network**  
  Sistem antar makanan cepat dan efisien oleh mitra driver lokal.

---

<!-- ## 🖼️ Screenshots

> *(Tambahkan tangkapan layar aplikasi di sini jika tersedia)*

--- -->

## 🧰 Tech Stack

| Layer       | Technology                                      |
|-------------|--------------------------------------------------|
| **Frontend**| React Native + Expo                             |
| **Backend** | Laravel                                          |
| **Database**| MySQL / PostgreSQL                              |
| **Auth**    | Firebase Auth / Laravel Sanctum                  |
| **Routing** | [Valhalla](https://github.com/valhalla/valhalla) (Open-source Routing Engine) |

**Routing Note:**  
Kami menggunakan **Valhalla** untuk menghitung rute optimal antar lokasi (merchant → pelanggan) berdasarkan waktu, jarak, dan kondisi lalu lintas. Cocok untuk kendaraan roda dua dengan rute lokal yang efisien.

---

## 🚀 Getting Started

Untuk memulai dengan Genggamanmu, ikuti langkah-langkah di bawah ini:

### 1. Clone Repository

```bash
git clone https://git.umkt.ac.id/genggamanmu/genggamanmu-dashboard.git
cd genggamanmu-dashboard
```

### 2. Setup Backend (Laravel)

```bash
cd genggamanmu-dashboard
cp .env.example .env
composer install
php artisan key:generate
php artisan migrate --seed
php artisan serve
```

### 3. Setup Node

```bash
cd genggamanmu-dashboard
npm install
npm run build
```

> Pastikan Anda sudah menginstal **Node.js**, **Composer**, dan **PHP** secara global sebelum menjalankan langkah-langkah di atas.

---

## 📥 Download App

📲 **Android (APK)**  
[Download via Dokumentasi Kami](https://docs.genggamanmu.com/introduction)

---

## 🧑‍🤝‍🧑 Join Us

Ingin bergabung dengan Genggamanmu?

- **Customer** – Unduh aplikasi dan nikmati kemudahan memesan makanan & minuman.
- **Merchant** – Daftarkan bisnis kuliner Anda untuk menjangkau lebih banyak pelanggan.
- **Driver** – Gabung sebagai mitra pengantar dan dapatkan penghasilan dengan mengantar pesanan.

---

## 🌐 Contact

Kunjungi situs web kami untuk informasi lebih lanjut:

- 🌍 Website: [https://genggamanmu.com](https://genggamanmu.com)
- ✉️ Hubungi Kami: [Formulir Kontak](https://genggamanmu.com/#hubungi-kami)

---

## 📄 License

© 2024 Genggamanmu – Universitas Muhammadiyah Kalimantan Timur (UMKT)  
Lisensi untuk penggunaan internal. Distribusi tanpa izin dilarang.

---

## 🏫 About

Proyek ini dikembangkan oleh **Genggamanmu** dengan kolaborasi dari mahasiswa Universitas Muhammadiyah Kalimantan Timur (UMKT).
