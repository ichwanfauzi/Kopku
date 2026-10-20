<div align="center">

# ☕ Kopku
### Aplikasi Kasir dan Stok Sederhana untuk Kedai Kopi

![Project](https://img.shields.io/badge/Project-PBL%20PBW-4F46E5?style=for-the-badge)
![Milestone](https://img.shields.io/badge/Progress-Milestone%201-F59E0B?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Perencanaan-64748B?style=for-the-badge)

**Digitalisasi pencatatan penjualan dan stok untuk membantu operasional kedai kopi kecil.**

[Proposal](docs/proposal.md) · [Wireframe](docs/wireframe.md) · [Panduan Git](docs/collaboration.md)

</div>

---

## 👤 Project Information

- **Project:** Kopku
- **Course:** Pemrograman Berbasis Web (PBW)
- Repositori tautan: tajuddinachmad/Kopku
- **Author/team:**
  1. Tajuddin Achmad - (A11.2025.1658)
  2. Keyla Azzahra Mefia - (A11.2025.16533)
  3. Cantik Indah Lestari - (A11.2025.16139)

## 🧾 Overview
Kopku adalah rancangan aplikasi web kasir dan pengelolaan stok sederhana untuk kedai kopi kecil. Aplikasi direncanakan untuk membantu pencatatan transaksi, pengelolaan produk, pemantauan stok, dan penyajian ringkasan penjualan.

**Status Milestone 1:** fokus pada dokumentasi kebutuhan, rancangan antarmuka yang sudah tersedia, struktur awal repository, dan kolaborasi Git. Fitur yang tercantum di bawah ini masih merupakan rencana, bukan klaim bahwa implementasinya sudah selesai.

## Latar Belakang
Pencatatan penjualan dan stok secara manual berisiko menyebabkan data sulit ditelusuri, perbedaan stok catatan dan stok aktual, serta kesalahan penghitungan pendapatan. Pemilik kedai juga dapat mengalami kesulitan memantau penjualan ketika tidak berada di lokasi.

## 🎯 Project Goals

- Merancang aplikasi web sederhana untuk kebutuhan kasir dan stok kedai kopi.
- Menentukan masalah, target pengguna, dan kebutuhan fitur utama.
- Mendokumentasikan wireframe yang sudah dibuat oleh kelompok.
- Menyiapkan struktur repository dan dokumentasi awal.
- Mengerjakan proyek secara bertahap sesuai milestone mata kuliah PBW.

## 👥 Target Users

| Pengguna | Kebutuhan yang direncanakan |
|---|---|
| **Admin/Kasir** | Mengelola produk, kategori, stok, pencatatan penjualan, dan riwayat transaksi sesuai hak akses. |
| **Pemilik usaha** | Memantau ringkasan penjualan dan stok dengan akses baca sesuai rancangan. |

# ✨ Planned Features

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

**Tautan Figma:** (figma.com/make/WRgAqIMfwf1VYrMWDuww2E/Redesign-Kopku-POS-Interface?code-node-id=0-6&t=KvXBsolCyCpWkiq4-0&fullscreen=1)

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
│       └── wireframes/       
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

---

### Preview Wireframe

**Login**

![Wireframe Login](assets/wireframe/Login.png)

**Dashboard, Daftar Data, dan Form**

![Wireframe Dashboard, Daftar Data, dan Form](assets/wireframe/Dashboard.jpg)
![Dashboard Kopku](assets/images/wireframes/DaftarProduk.png)

---

## Pengembangan Opsional

1. **Peringatan stok menipis:** menjawab masalah barang habis saat ramai.
2. **Cetak struk sederhana:** memberi bukti pembayaran untuk pelanggan.

---

## Log Penggunaan AI

| Tanggal | Tujuan | Prompt | Bagian yang Dibantu | Penjelasan Mandiri | Hasil Pengujian |
|---|---|---|---|---|---|
| 19 Okt 2026 | ... | "..." | ... | ... | ... |

<p align="center">
  <strong>Kopku</strong><br>
  <sub>Brew better workflows. Track every product. Build incrementally.</sub>
</p>
