# KasirKu

**Simple Point of Sale & Inventory Management — Project Planning**

[![Project](https://img.shields.io/badge/Project-PjBL%20PBW-2563EB)](.)
[![Stage](https://img.shields.io/badge/Stage-Milestone%201-F59E0B)](docs/proposal.md)
[![Status](https://img.shields.io/badge/Status-Planning%20%26%20Wireframe-64748B)](.)
[![PHP Native](https://img.shields.io/badge/Backend-PHP%20Native-777BB4?logo=php&logoColor=white)](https://www.php.net/)
[![MySQL](https://img.shields.io/badge/Database-MySQL%2FMariaDB-4479A1?logo=mysql&logoColor=white)](https://www.mysql.com/)
[![HTML5](https://img.shields.io/badge/Frontend-HTML5%20%7C%20CSS3%20%7C%20JS-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/)
[![License](https://img.shields.io/badge/License-TBD-lightgrey)](.)

---

## 🧾 Overview

**KasirKu** adalah rancangan aplikasi web kasir dan manajemen stok sederhana untuk membantu toko kecil, kantin, atau koperasi merencanakan pengelolaan produk, persediaan, dan pencatatan penjualan secara lebih teratur.

Pencatatan manual dapat membuat pencarian data, pemantauan stok, dan rekap penjualan membutuhkan waktu lebih lama. KasirKu dirancang sebagai solusi sederhana dengan alur yang mudah dipahami oleh admin atau kasir.

> **Project scope:** Repository ini saat ini berfokus pada **Milestone 1 — Perencanaan Proyek dan Persiapan Lingkungan Kerja**. Fitur yang disebutkan merupakan rencana kebutuhan dan belum diklaim telah diimplementasikan.

## 🎯 Project Goals

- Merancang aplikasi web sederhana untuk kebutuhan kasir dan stok.
- Menentukan masalah, target pengguna, dan kebutuhan fitur.
- Menyusun wireframe halaman inti sebelum pengembangan.
- Menyiapkan struktur repository dan dokumentasi awal.
- Membangun proyek bertahap mengikuti milestone mata kuliah PBW.

## ✨ Planned Features

Fitur berikut masih berada pada tahap perencanaan.

### 📦 Product & Inventory
- Pengelolaan kategori produk.
- Rencana pencatatan nama produk, harga, dan jumlah stok.
- Pencarian produk dan peringatan stok menipis sebagai pengembangan yang direncanakan.

### 🛒 Sales Transaction
- Rencana pencatatan transaksi penjualan.
- Detail transaksi berisi produk, jumlah, harga satuan, dan subtotal.
- Perencanaan pengurangan stok setelah transaksi tersimpan.

### 📊 Dashboard & Reports
- Ringkasan jumlah produk dan stok.
- Ringkasan transaksi serta penjualan harian.
- Rencana riwayat transaksi dan laporan sederhana.

### 🔐 Access & Usability
- Rencana login, logout, dan session.
- Rencana pencarian/filter dan pagination daftar data.
- Tampilan tanggal dan waktu serta validasi formulir.

## 👥 Target Users

| Pengguna | Kebutuhan yang direncanakan |
|---|---|
| **Admin/Kasir** | Mengelola produk, kategori, stok, dan pencatatan penjualan. |
| **Pemilik usaha (opsional)** | Melihat ringkasan stok dan penjualan. |

## 🧰 Planned Tech Stack

Teknologi yang direncanakan mengikuti panduan PjBL Pemrograman Berbasis Web.

| Teknologi | Rencana penggunaan |
|---|---|
| HTML5 | Struktur halaman |
| CSS3 | Tata letak dan responsivitas |
| JavaScript | Interaksi dasar serta tanggal/waktu |
| PHP Native | Logika aplikasi, form, session, dan CRUD |
| MySQL / MariaDB | Penyimpanan data |
| jQuery + AJAX | Pagination daftar data |
| Git + GitHub | Version control |
| Web hosting | Publikasi pada tahap akhir |

> Framework PHP seperti Laravel tidak direncanakan sebagai inti proyek karena panduan menekankan pemahaman PHP native.

## 🖼️ Initial Wireframes

Wireframe awal direncanakan untuk empat halaman inti:

1. **Login** — formulir username dan password.
2. **Dashboard** — ringkasan informasi utama.
3. **Daftar Produk** — tabel produk, pencarian, dan navigasi halaman.
4. **Form Produk** — formulir tambah/edit produk.

Lihat [`docs/wireframe.md`](docs/wireframe.md).

## 🗂️ Project Structure

```text
KasirKu/
├── assets/
│   └── .gitkeep
├── docs/
│   ├── proposal.md
│   └── wireframe.md
├── .gitignore
└── README.md
```

Struktur ini merupakan struktur awal untuk Milestone 1. Folder implementasi dapat ditambahkan pada milestone berikutnya sesuai kebutuhan dan arahan dosen.

## 🚀 Getting Started

### Current milestone

Pada tahap ini belum ada aplikasi yang dapat dijalankan. Untuk meninjau dokumen:

1. Buka `README.md` untuk ringkasan proyek.
2. Baca [`docs/proposal.md`](docs/proposal.md) untuk latar belakang, tujuan, dan kebutuhan pengguna.
3. Baca [`docs/wireframe.md`](docs/wireframe.md) untuk sketsa halaman.

Instruksi menjalankan aplikasi akan ditambahkan setelah kode tersedia.

## 🧭 Milestone 1 Checklist

- [ ] Menetapkan latar belakang masalah.
- [ ] Menentukan target pengguna.
- [ ] Menyusun daftar kebutuhan fitur utama.
- [ ] Menyiapkan wireframe login, dashboard, daftar data, dan form.
- [ ] Membuat repository Git.
- [ ] Menyiapkan struktur folder awal dan README.
- [ ] Membuat minimal tiga commit bermakna.

## 📝 Planned Git Commits

Contoh urutan commit untuk perubahan yang benar-benar dilakukan:

```text
docs: add project README and initial description
docs: add project proposal and user requirements
docs: add initial page wireframes
```

Commit harus dibuat secara bertahap. Jangan menggunakan pesan tersebut sebelum perubahan terkait benar-benar ada pada repository.

## 📚 Documentation

- [Project Proposal](docs/proposal.md) — latar belakang, masalah, tujuan, pengguna, dan ruang lingkup.
- [Initial Wireframes](docs/wireframe.md) — rancangan awal halaman inti.

## 🔒 Scope & Notes

- Repository ini masih berada pada tahap perencanaan.
- Belum tersedia autentikasi, database, CRUD, transaksi nyata, atau pagination AJAX.
- Fitur lanjutan hanya akan dikerjakan sesuai milestone berikutnya.
- Isi dokumen perlu ditinjau dan disesuaikan anggota proyek sebelum dikumpulkan.

## 👤 Project Information

- **Project:** KasirKu
- **Course:** Pemrograman Berbasis Web (PBW)
- **Institution:** [Isi nama institusi]
- **Author/team:** [Isi nama anggota]
- **Class:** [Isi kelas]
- **Year:** 2026

---

<p align="center">
  <strong>KasirKu</strong><br>
  <sub>Plan clearly. Build incrementally. Understand every line of code.</sub>
</p>
