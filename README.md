# 🏢 PT Maju Jaya Management System

Sistem informasi manajemen yang dirancang untuk membantu operasional PT Maju Jaya secara lebih efektif, terstruktur, dan terintegrasi.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![PHP](https://img.shields.io/badge/PHP-8.x-777BB4?logo=php)
![CodeIgniter](https://img.shields.io/badge/CodeIgniter-3.x-EF4223?logo=codeigniter)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql)
![Status](https://img.shields.io/badge/status-active-success)

---

## 📖 Tentang Project

PT Maju Jaya Management System merupakan aplikasi berbasis web yang digunakan untuk membantu pengelolaan data perusahaan, mulai dari proses administrasi, manajemen pengguna, hingga pelaporan data secara real-time.

Aplikasi ini dibangun dengan fokus pada:

- ⚡ Kemudahan penggunaan
- 🔒 Keamanan data
- 📊 Monitoring dan pelaporan
- 📱 Tampilan responsif
- 🚀 Performa yang optimal

---

## ✨ Fitur Utama

- 👤 Manajemen Pengguna
- 🔐 Login & Hak Akses
- 📋 Pengelolaan Data
- 📊 Dashboard Statistik
- 📄 Laporan Data
- 🔍 Pencarian Data Cepat
- 📱 Responsive Design
- 📨 Notifikasi Sistem

---

## 🛠️ Teknologi yang Digunakan

### Backend
- PHP
- CodeIgniter 3
- MySQL

### Frontend
- HTML5
- CSS3
- Bootstrap
- JavaScript
- jQuery

### Tools
- Git
- GitHub
- XAMPP / Laragon

---

## 📂 Struktur Project

```bash
pt_majujaya/
│
├── application/
│   ├── controllers/
│   ├── models/
│   ├── views/
│
├── assets/
│   ├── css/
│   ├── js/
│   ├── images/
│
├── system/
│
├── database/
│
└── index.php
```

---

## 🚀 Instalasi

### 1. Clone Repository

```bash
git clone https://github.com/fachrurhannan/pt_majujaya.git
```

### 2. Masuk ke Folder Project

```bash
cd pt_majujaya
```

### 3. Konfigurasi Database

Buat database baru di MySQL:

```sql
CREATE DATABASE pt_majujaya;
```

Import file database yang tersedia pada project.

### 4. Atur Koneksi Database

Edit file:

```php
application/config/database.php
```

Sesuaikan:

```php
'hostname' => 'localhost',
'username' => 'root',
'password' => '',
'database' => 'pt_majujaya',
```

### 5. Jalankan Project

Jika menggunakan XAMPP:

```bash
http://localhost/pt_majujaya
```

---

## 📸 Screenshot

### Dashboard

<p align="center">
  <img width="958" height="435" alt="image" src="https://github.com/user-attachments/assets/0f5039ff-3614-4e47-9466-44a652a67e40" />
</p>

### Manajemen Data

<p align="center">
 <img width="946" height="438" alt="image" src="https://github.com/user-attachments/assets/178fbd15-557c-4c55-87a4-19f5defaf7ad" />
<img width="959" height="440" alt="image" src="https://github.com/user-attachments/assets/5ea3e533-9ebc-4494-88f6-6366b5ddbeb4" />
</p>

---

## 🎯 Tujuan Project

Project ini dibuat untuk:

- Mempermudah proses administrasi perusahaan
- Mengurangi kesalahan pencatatan data
- Meningkatkan efisiensi kerja
- Menyediakan laporan yang cepat dan akurat

---

## 👨‍💻 Developer

**Fachrur Hannan**

- GitHub: https://github.com/fachrurhannan

---

## 🤝 Kontribusi

Kontribusi sangat terbuka.

Langkah kontribusi:

1. Fork repository
2. Buat branch baru

```bash
git checkout -b feature/nama-fitur
```

3. Commit perubahan

```bash
git commit -m "Menambahkan fitur baru"
```

4. Push ke branch

```bash
git push origin feature/nama-fitur
```

5. Buat Pull Request

---

## ⭐ Dukungan

Jika project ini membantu, jangan lupa berikan ⭐ pada repository ini.

---

## 📜 License

Project ini menggunakan lisensi MIT.

© 2026 PT Maju Jaya Management System
