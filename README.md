<div align="center">

# 🛒 MaPen UMKM

### Manajemen Penjualan UMKM Berbasis Android

![Platform](https://img.shields.io/badge/Platform-Android-success?style=for-the-badge)
![Kotlin](https://img.shields.io/badge/Kotlin-2.0-purple?style=for-the-badge)
![Compose](https://img.shields.io/badge/Jetpack%20Compose-Material3-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge)

Aplikasi modern untuk membantu UMKM mengelola transaksi, produk, stok, dan laporan penjualan secara digital.

</div>

---

## 📌 About Project

> 💡 **MaPen UMKM** adalah aplikasi berbasis Android yang dirancang untuk membantu pelaku Usaha Mikro, Kecil, dan Menengah (UMKM) dalam mengelola transaksi penjualan secara digital, cepat, sederhana, dan efisien.
>
> Aplikasi ini membantu pemilik usaha dalam mencatat transaksi, mengelola produk dan stok, melihat riwayat penjualan, serta memantau laporan penjualan secara berkala.
>
> Selain itu, MaPen UMKM dilengkapi dengan fitur **Smart Business Assistant** berbasis Artificial Intelligence (AI) sederhana yang mampu memberikan ringkasan penjualan, rekomendasi stok, dan insight bisnis yang mudah dipahami.

---

## 👥 Team

<table>
    <tr>
        <th>Nama</th>
        <th>NIM</th>
        <th>Role</th>
        <th>GitHub</th>
    </tr>
    <tr>
        <td>Danar Prayogo</td>
        <td>123140015</td>
        <td>Lead & Android Developer</td>
        <td><a href="https://github.com/danarPrayogo">@danarPrayogo</a></td>
    </tr>
    <tr>
        <td>Exaudi Amin Hitasoit</td>
        <td>123140161</td>
        <td>Backend & AI Developer</td>
        <td><a href="https://github.com/16-123140161-ExaudiAminHutasoit">@ExaudiAminHitasoit</a></td>
    </tr>
</table>

---

## 📝 Description

MaPen UMKM adalah aplikasi manajemen penjualan yang ditujukan untuk membantu pemilik UMKM mengelola aktivitas usaha sehari-hari.

Melalui aplikasi ini, pengguna dapat melakukan pencatatan transaksi penjualan, mengelola data produk, memantau stok barang, melihat riwayat transaksi, serta memperoleh laporan penjualan dengan tampilan yang modern dan mudah digunakan.

Aplikasi ini juga mengintegrasikan fitur AI sederhana melalui **Smart Business Assistant** untuk membantu pengguna memahami kondisi bisnis, seperti produk paling laris, stok yang hampir habis, serta ringkasan laporan penjualan harian maupun bulanan.

---

## ✨ Features

### 🟢 Minimum Features

| Status | Feature |
|---------|----------|
| ⬜ | Login Page |
| ⬜ | Dashboard Penjualan |
| ⬜ | Manajemen Produk |
| ⬜ | Transaksi Penjualan |
| ⬜ | Riwayat & Penyimpanan |
| ⬜ | Laporan Penjualan |

### 🤖 Bonus Features

| Status | Feature |
|---------|----------|
| ⬜ | Analisis Penjualan Otomatis |
| ⬜ | Rekomendasi Produk & Prediksi Stok |
| ⬜ | Ringkasan Laporan Otomatis |
| ⬜ | Smart Search |
| ⬜ | Insight Penjualan |

---

## 📱 Main Screens

| Screen | Deskripsi |
|---------|------------|
| 🔐 Login Screen | Halaman masuk pengguna sebelum mengakses aplikasi |
| 📊 Dashboard Penjualan | Menampilkan ringkasan kondisi bisnis |
| 📦 Manajemen Produk | Mengelola data produk dan stok |
| 🛒 Transaksi Penjualan | Mencatat transaksi dan menghitung total belanja |
| 📜 Riwayat Transaksi | Menampilkan histori transaksi |
| 📈 Laporan Penjualan | Menampilkan laporan berdasarkan periode |
| 🤖 Smart Business Assistant | Menampilkan insight dan rekomendasi bisnis |

---

## 🧭 User Flow

```text
Start
  │
  ▼
Login
  │
  ▼
Dashboard
  │
  ├── Manajemen Produk
  │
  ├── Transaksi Penjualan
  │       │
  │       ▼
  │   Riwayat Transaksi
  │
  ▼
Laporan Penjualan
  │
  ▼
Smart Business Assistant
  │
  ▼
End
```

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white">
  <img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white">
  <img src="https://img.shields.io/badge/Material%20Design%203-6750A4?style=for-the-badge">
  <img src="https://img.shields.io/badge/Koin-FF6B6B?style=for-the-badge">
  <img src="https://img.shields.io/badge/SQLDelight-00C853?style=for-the-badge">
</p>

---

## 📂 Project Structure

```text
composeApp/
└── src/
    └── commonMain/
        └── kotlin/
            └── com.example.mapenumkm/
                ├── core/
                ├── data/
                ├── domain/
                ├── presentation/
                │   ├── components/
                │   ├── navigation/
                │   ├── screens/
                │   │   ├── addnote/
                │   │   ├── ai/
                │   │   ├── detail/
                │   │   ├── home/
                │   │   └── login/
                │   └── theme/
                └── App.kt
```

---

## 🎨 UI/UX Design

> ✨ Modern & Clean Design
>
> - Minimalis dan mudah digunakan
> - Fokus pada kebutuhan UMKM
> - Menggunakan Material Design 3
> - Card Based Layout
> - Rounded Button
> - Search Bar
> - Bottom Navigation
> - Responsive Interface

### 🎨 Color Palette

| Color | Hex Code |
|---------|---------|
| Green Primary | `#16A34A` |
| Green Dark | `#15803D` |
| Green Light | `#DCFCE7` |
| Blue Accent | `#60A5FA` |
| Yellow Accent | `#FACC15` |
| Purple Accent | `#A78BFA` |

---

## 🤖 Smart Business Assistant

Smart Business Assistant merupakan fitur pendukung berbasis AI sederhana yang membantu pengguna memahami kondisi bisnisnya.

### Contoh Ringkasan AI

```text
📊 Ringkasan Penjualan Hari Ini

• Total Pendapatan : Rp250.000
• Total Transaksi : 10
• Produk Terlaris : Es Teh
• Stok Menipis : Kopi Susu (3 pcs)

💡 Rekomendasi:
Segera lakukan restock Kopi Susu untuk menghindari kehabisan stok.
```

Fitur AI pada aplikasi ini dirancang tetap ringan, realistis, dan mudah dikembangkan pada tahap awal pengembangan aplikasi.

---

## 🚀 Installation

### Clone Repository

```bash
git clone <repository-url>
```

### Jalankan Project

```bash
# Buka menggunakan Android Studio

# Tunggu proses Gradle Sync selesai

# Jalankan pada Emulator atau Device Android
```

---

## 🎯 Project Goal

Tujuan utama dari MaPen UMKM adalah membantu pelaku UMKM dalam:

- Mengelola transaksi penjualan
- Mengelola data produk
- Memantau stok barang
- Melihat laporan penjualan
- Mendapatkan insight bisnis sederhana melalui AI

Aplikasi dirancang agar ringan, mudah digunakan, dan tetap modern dengan memanfaatkan Kotlin serta Jetpack Compose.

---

## 📌 Conclusion

MaPen UMKM diharapkan dapat menjadi solusi sederhana bagi pelaku UMKM untuk melakukan pencatatan transaksi, mengelola produk, memantau stok, melihat laporan penjualan, serta memperoleh insight bisnis sederhana melalui bantuan AI.

Dengan fitur yang fokus pada kebutuhan utama UMKM, aplikasi ini realistis untuk dikembangkan sebagai project Android modern berbasis Kotlin dan Jetpack Compose.

---

<div align="center">

Made with ❤️ using Kotlin & Jetpack Compose

</div>
