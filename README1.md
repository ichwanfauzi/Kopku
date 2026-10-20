# Kopku

**Simple Point of Sale & Inventory Management — Project Planning**

[![Project](https://img.shields.io/badge/Project-PjBL%20PBW-6F4E37)](#)
[![Stage](https://img.shields.io/badge/Stage-Milestone%201-F59E0B)](docs/proposal.md)
[![Status](https://img.shields.io/badge/Status-Planning%20%26%20Wireframe-64748B)](#)
[![PHP Native](https://img.shields.io/badge/Backend-PHP%20Native-777BB4?logo=php&logoColor=white)](https://www.php.net/)
[![MySQL](https://img.shields.io/badge/Database-MySQL%2FMariaDB-4479A1?logo=mysql&logoColor=white)](https://www.mysql.com/)
[![HTML5](https://img.shields.io/badge/Frontend-HTML5%20%7C%20CSS3%20%7C%20JS-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/)
[![License](https://img.shields.io/badge/License-TBD-lightgrey)](#)

---

## 🧾 Overview

**Kopku** adalah rancangan aplikasi web kasir dan manajemen stok sederhana untuk membantu kedai kopi kecil mengelola produk, persediaan, dan pencatatan penjualan secara lebih teratur.

Pencatatan manual dapat membuat pencarian data, pemantauan stok, dan rekap penjualan membutuhkan waktu lebih lama. Kopku direncanakan untuk membantu proses tersebut melalui alur antarmuka yang mudah dipahami oleh admin/kasir serta ringkasan informasi untuk pemilik.

> **Project scope:** Repository ini berfokus pada **Milestone 1 — Perencanaan Proyek dan Persiapan Lingkungan Kerja**.

## 🎯 Project Goals

- Merancang aplikasi web sederhana untuk kebutuhan kasir dan stok kedai kopi.
- Menentukan masalah, target pengguna, dan kebutuhan fitur utama.
- Mendokumentasikan wireframe yang sudah dibuat oleh kelompok.
- Menyiapkan struktur repository dan dokumentasi awal.
- Mengerjakan proyek secara bertahap sesuai milestone mata kuliah PBW.

## ✨ Planned Features

### 📦 Product & Inventory

- Rencana pengelolaan kategori produk.
- Rencana pencatatan nama produk, harga, dan jumlah stok.
- Pencarian atau filter produk.
- Indikator stok menipis sebagai fitur yang direncanakan.

### 🛒 Sales Transaction

- Rencana pencatatan transaksi penjualan.
- Rencana detail transaksi berupa produk, jumlah, harga satuan, dan subtotal.
- Perencanaan pengurangan stok setelah transaksi berhasil disimpan.

### 📊 Dashboard & Reports

- Ringkasan jumlah produk dan stok.
- Ringkasan transaksi dan penjualan harian.
- Riwayat transaksi atau laporan sederhana sesuai ruang lingkup pengembangan berikutnya.

### 🔐 Access & Usability

- Rencana login, logout, dan session.
- Rencana form tambah/edit dan konfirmasi penghapusan data.
- Rencana pencarian/filter dan pagination dengan jQuery AJAX.
- Tampilan tanggal dan waktu serta validasi formulir.

## 👥 Target Users

| Pengguna | Kebutuhan yang direncanakan |
|---|---|
| **Admin/Kasir** | Mengelola produk, kategori, stok, pencatatan penjualan, dan riwayat transaksi sesuai hak akses. |
| **Pemilik usaha** | Memantau ringkasan penjualan dan stok dengan akses baca sesuai rancangan. |

## 🧰 Planned Tech Stack

Teknologi yang direncanakan mengikuti panduan PjBL Pemrograman Berbasis Web.

| Teknologi | Rencana penggunaan |
|---|---|
| HTML5 | Struktur halaman |
| CSS3 | Tata letak dan responsivitas |
| JavaScript | Interaksi dasar serta tanggal/waktu |
| PHP Native | Logika aplikasi, form, session, dan CRUD |
| MySQL / MariaDB | Penyimpanan data |
| jQuery + AJAX | Pagination atau pemuatan daftar data tanpa reload penuh |
| Git + GitHub | Version control dan kolaborasi |
| Web hosting | Publikasi pada tahap akhir |


## 🖼️ Initial Wireframes

**Tautan Figma:** figma.com/make/WRgAqIMfwf1VYrMWDuww2E/Redesign-Kopku-POS-Interface?code-node-id=0-6&t=KvXBsolCyCpWkiq4-0&fullscreen=1

Wireframe awal perlu mencakup atau dapat dipetakan ke empat halaman inti Milestone 1:

1. **Login** — formulir username/email dan password.
2. **Dashboard** — ringkasan informasi utama kedai.
3. **Daftar Produk** — daftar produk, harga, stok, dan pencarian/filter bila dirancang.
4. **Form Produk** — form tambah atau edit produk.

Lihat [`docs/wireframe.md`](docs/wireframe.md) untuk pemetaan kebutuhan ke desain yang sudah tersedia.

## 🗂️ Project Structure

```text
Kopku/
├── assets/
│   └── images/
│       └── wireframes/       # Aset/screenshot desain yang sudah tersedia
├── css/
├── docs/
│   ├── proposal.md
│   ├── wireframe.md
│   └── collaboration.md
├── js/
├── index.html
├── .gitignore
└── README.md
```

Struktur ini menjelaskan struktur awal dan dokumentasi yang direncanakan.

## 🚀 Getting Started

### Current milestone

Untuk meninjau proyek:

1. Buka `README.md` untuk ringkasan proyek.
2. Baca [`docs/proposal.md`](docs/proposal.md) untuk latar belakang, tujuan, pengguna, dan ruang lingkup.
3. Baca [`docs/wireframe.md`](docs/wireframe.md) untuk referensi desain Figma yang sudah ada.
4. Baca [`docs/collaboration.md`](docs/collaboration.md) untuk panduan kolaborasi Git.

Untuk mengunduh repository:

```bash
git clone https://github.com/tajuddinachmad/Kopku.git
cd Kopku
```

Instruksi menjalankan aplikasi akan ditambahkan setelah implementasi tersedia dan cara menjalankannya telah diverifikasi.

## 🧭 Milestone 1 Checklist

- [x] Menentukan ide proyek Kopku.
- [x] Menjelaskan latar belakang dan target pengguna pada dokumentasi proyek.
- [x] Menyusun rencana fitur utama dan batasan awal.
- [x] Menggunakan desain Figma yang sudah dimiliki kelompok.
- [x] Memastikan proposal dan README sesuai dengan panduan tugas.
- [x] Memastikan struktur awal dan dokumentasi tersedia di repository.
- [x] Memastikan akses tautan Figma dapat digunakan anggota kelompok/dosen.
- [x] Membuat minimal tiga commit bermakna sesuai ketentuan tugas.
- [x] Meninjau hasil akhir bersama anggota kelompok.


## 📝 Planned Git Commits

Contoh urutan commit untuk perubahan yang benar-benar dilakukan:

```text
docs: improve Kopku project README
docs: add project proposal and user requirements
docs: document existing wireframes and collaboration workflow
```

Commit harus dibuat secara bertahap. Jangan menggunakan pesan tersebut sebelum perubahan terkait benar-benar ada pada repository.

## 📚 Documentation

- [Project Proposal](docs/proposal.md) — latar belakang, rumusan masalah, tujuan, pengguna, dan ruang lingkup.
- [Wireframe Reference](docs/wireframe.md) — pemetaan kebutuhan ke desain Figma yang sudah ada.
- [Collaboration Guide](docs/collaboration.md) — usulan alur kerja branch, commit, dan pull request.


## 👤 Project Information

- **Project:** Kopku
- **Course:** Pemrograman Berbasis Web (PBW)
- **Author/team:**
  1. Tajuddin Achmad
  2. Keyla Azzahra Mefia
  3. Cantik Indah Lestari

---

<p align="center">
  <strong>Kopku</strong><br>
  <sub>Brew better workflows. Track every product. Build incrementally.</sub>
</p>
