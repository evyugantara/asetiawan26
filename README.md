# Angga Setiawan - Professional Personal Portfolio

Website personal portfolio profesional untuk **Angga Setiawan**, lulusan S1 Teknik Informatika Universitas Suryakancana. Website ini dirancang dengan konsep **Modern Minimalist – Elegant Professional Portfolio** untuk kebutuhan rekrutmen oleh HRD, recruiter, dan kolaborasi industri.

---

## 🌟 Fitur & Keunggulan Desain

- **Desain Modern Minimalis & Elegan**: Mengutamakan tipografi tajam, ruang kosong (*whitespace*) proporsional, dan tata letak simetris.
- **Bebas Library Ikon Generik**: Tanpa Font Awesome, Lucide, atau ikon AI generik. Menggunakan tipografi, garis aksen, dan bentuk geometris CSS murni.
- **Foto Profil Terintegrasi**: Menggunakan foto asli profesional pada Hero Section dengan bingkai geometris elegan.
- **Responsif Penuh**: Dioptimalkan khusus untuk layar desktop besar (1920px), laptop (1366px), tablet (768px), hingga smartphone (430px, 390px, 375px).
- **Interaksi Halus (Vanilla JS)**:
  - Sticky navbar dengan backdrop blur dan active state otomatis saat scroll.
  - Hamburger menu interaktif untuk perangkat mobile.
  - Scroll reveal animation menggunakan `IntersectionObserver`.
  - Tombol aksi cepat untuk kirim Email dan salin surel ke clipboard.
  - Tombol kembali ke atas (*Back to Top*).
  - Mendukung preferensi aksesibilitas `prefers-reduced-motion`.

---

## 🎨 Palet Warna

| Elemen | Kode HEX | Kegunaan |
| :--- | :--- | :--- |
| **Deep Navy** | `#14243A` | Warna dominan, judul utama, tombol primer, logo |
| **Dark Blue** | `#203A5B` | Sub-heading, hover status, aksen garis |
| **White** | `#FFFFFF` | Background utama, kartu konten |
| **Light Gray** | `#F5F6F8` | Background selang-seling section, badge |
| **Soft Gray** | `#E5E7EB` | Garis pembatas, border kartu halus |
| **Text Dark** | `#252B36` | Teks isi (*body copy*) |

---

## 📁 Struktur Direktori

```text
portfolio-angga/
│
├── index.html              # Struktur semantic HTML5 halaman tunggal
│
├── css/
│   └── style.css           # Styling CSS3 modern (Grid, Flexbox, Media Queries)
│
├── js/
│   └── script.js           # Vanilla JavaScript interaksi & animasi
│
├── assets/
│   ├── images/
│   │   └── profile.jpg     # Foto profil asli Angga Setiawan
│   └── documents/          # Direktori untuk berkas pendukung (CV PDF dll.)
│
└── README.md               # Dokumentasi lengkap proyek
```

---

## 🚀 Cara Menjalankan Secara Lokal

Website ini dibangun murni menggunakan **HTML5, CSS3, dan Vanilla JavaScript** tanpa memerlukan dependensi Node.js atau instalasi build tool tambahan.

### Cara 1: Langsung Buka File
1. Buka folder `portfolio-angga`.
2. Klik dua kali pada file `index.html` untuk langsung membukanya di browser favorit Anda (Google Chrome, Edge, Firefox, Safari).

### Cara 2: Menggunakan Live Server (VS Code / Antigravity)
1. Buka folder `portfolio-angga` di VS Code / Antigravity IDE.
2. Klik kanan pada `index.html` dan pilih **Open with Live Server**.
3. Akses via browser pada alamat `http://127.0.0.1:5500/`.

---

## 🌐 Panduan Deploy

### Deploy ke GitHub Pages:
1. Buat repositori baru di GitHub dengan nama misalnya `portfolio-angga`.
2. Inisialisasi git dan push kode:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Angga Setiawan Portfolio"
   git branch -M main
   git remote add origin https://github.com/<username>/portfolio-angga.git
   git push -u origin main
   ```
3. Di GitHub, buka menu **Settings > Pages**.
4. Pada **Build and deployment > Branch**, pilih branch `main` dan folder `/ (root)`.
5. Klik **Save**. Website Anda akan langsung online dalam beberapa detik!

### Deploy ke Vercel:
1. Login ke [vercel.com](https://vercel.com).
2. Klik **Add New... > Project**.
3. Impor repositori GitHub Anda.
4. Pada bagian **Root Directory**, pilih folder jika berada di subfolder, atau langsung deploy jika file `index.html` ada di root.
5. Klik **Deploy**.

---

## 👤 Informasi Profil

- **Nama**: Angga Setiawan
- **Pendidikan**: S1 Teknik Informatika, Universitas Suryakancana (2022 – 2026, IPK: 2.85)
- **Minat & Fokus**: Sistem Informasi, Analisis & Perancangan Sistem, Pengolahan Data, UI/UX Design
- **Surel**: [agastwn32@gmail.com](mailto:agastwn32@gmail.com)
- **Lokasi**: Kabupaten Cianjur, Jawa Barat, Indonesia

---
&copy; 2026 Angga Setiawan. All Rights Reserved.
