# 🚀 Laravel Starter 12

Laravel Starter 12 adalah template awal proyek berbasis **Laravel 12**, dirancang untuk memudahkan pengembangan aplikasi dengan struktur yang rapi dan fitur dasar siap pakai.

---

## ⚙️ Fitur Utama

✅ Laravel 12 (PHP 8.3 compatible)  
✅ Struktur folder modular  
✅ Authentication (Login & Register)  
✅ API-ready (dengan route dan controller contoh)  
✅ Blade template dasar  
✅ Integrasi dengan Vite & Bootstrap  
✅ Dukungan environment `.env` yang mudah dikonfigurasi  

---

## 🧩 Instalasi

Pastikan sudah terpasang **PHP ≥ 8.3**, **Composer**, dan **Node.js**.

```bash
# Clone repository
git clone https://github.com/afrizalcode2/laravel-starter-12.git

# Masuk ke folder
cd laravel-starter-12

# Install dependensi PHP
composer install

# Install dependensi frontend
npm install && npm run build

# Copy file environment
cp .env.example .env

# Generate application key
php artisan key:generate

# Jalankan server
php artisan serve

# Struktur Folder
laravel-starter-12/
├── app/
│   ├── Http/
│   ├── Models/
│   └── ...
├── routes/
│   ├── web.php
│   └── api.php
├── resources/
│   ├── views/
│   └── js/
└── ...

# Untuk mode development:
npm run dev
php artisan serve

🧾 Lisensi

Proyek ini dirilis di bawah lisensi MIT — bebas digunakan untuk kebutuhan pribadi atau komersial.
Dibuat dengan ❤️ oleh Afrizal Marzuki

🌟 Dukungan

Kalau proyek ini membantu kamu, jangan lupa kasih ⭐ di repo ini!
Itu sangat berarti untuk pengembangan selanjutnya 😊
