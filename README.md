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

## Tentang Proyek
Kopku adalah rancangan aplikasi web kasir dan pengelolaan stok sederhana untuk kedai kopi kecil. Aplikasi direncanakan untuk membantu pencatatan transaksi, pengelolaan produk, pemantauan stok, dan penyajian ringkasan penjualan.

**Status Milestone 1:** fokus pada dokumentasi kebutuhan, rancangan antarmuka yang sudah tersedia, struktur awal repository, dan kolaborasi Git. Fitur yang tercantum di bawah ini masih merupakan rencana, bukan klaim bahwa implementasinya sudah selesai.

## Latar Belakang
Pencatatan penjualan dan stok secara manual berisiko menyebabkan data sulit ditelusuri, perbedaan stok catatan dan stok aktual, serta kesalahan penghitungan pendapatan. Pemilik kedai juga dapat mengalami kesulitan memantau penjualan ketika tidak berada di lokasi.

## Target Pengguna
| Pengguna | Kebutuhan utama |
|---|---|
| Admin/Kasir | Mengelola kategori dan produk, memperbarui stok, mencatat penjualan, melihat riwayat transaksi. |
| Pemilik | Memantau ringkasan penjualan dan stok dengan akses baca sesuai rancangan hak akses. |

## Rencana Fitur
- Login, logout, dan sesi pengguna.
- Dashboard ringkasan produk, stok, transaksi harian, dan penjualan.
- Pengelolaan kategori produk.
- Pengelolaan produk dan jumlah stok.
- Pencatatan transaksi dan detail item transaksi.
- Perhitungan subtotal dan total transaksi.
- Pengurangan stok setelah transaksi berhasil disimpan.
- Form tambah/edit dan konfirmasi penghapusan.
- Pencarian/filter dan pagination menggunakan jQuery AJAX.
- Penayangan tanggal dan waktu.
- Fitur opsional tahap berikutnya: peringatan stok menipis dan cetak struk.

## Batasan Ruang Lingkup
- Fokus awal pada produk yang dijual per unit, seperti minuman jadi, pastry, atau produk kemasan.
- Pengelolaan bahan baku berbasis resep tidak termasuk ruang lingkup awal.
- Pengerjaan mengikuti milestone perkuliahan. Milestone 1 memprioritaskan perencanaan dan dokumentasi.

## Rancangan Antarmuka
Desain Figma kelompok yang sudah ada **tetap digunakan dan tidak dibuat ulang**.

[**Buka desain Kopku di Figma**](https://www.figma.com/design/JMX0XHg22baBGuoNv5gIRY/Kopku-POS---all-design?node-id=0-1&p=f&t=dVEkT8cJKUEWqHR0-0)

Lihat [docs/wireframe.md](docs/wireframe.md) untuk pemetaan desain yang ada terhadap kebutuhan Milestone 1.

## Teknologi yang Direncanakan
HTML, CSS, JavaScript, PHP Native, MySQL/MariaDB, jQuery AJAX, Git, dan GitHub. Stack aktual perlu diverifikasi saat implementasi.

## Struktur Repository
```text
Kopku/
├── assets/images/wireframes/  # Screenshot desain yang sudah ada
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

## Checklist Milestone 1
- [x] Ide proyek ditentukan.
- [x] Latar belakang dan target pengguna didokumentasikan.
- [x] Rencana fitur dan batasan ditulis.
- [x] Menggunakan Figma kelompok yang sudah tersedia.
- [ ] Memastikan struktur awal dan semua file dokumentasi ada di repository.
- [ ] Memastikan minimal tiga commit bermakna sesuai ketentuan tugas.
- [ ] Meninjau hasil bersama seluruh anggota.

## Tim
1. Tajuddin Achmad
2. Keyla Azzahra Mefia
3. Cantik Indah Lestari

Tambahkan identitas akademik dan pembagian tugas sesuai format yang diwajibkan dosen.

## Menyalin Repository
```bash
git clone https://github.com/tajuddinachmad/Kopku.git
cd Kopku
```

Cara menjalankan aplikasi akan ditambahkan setelah implementasi dan kebutuhan server ditentukan.

## Catatan Penggunaan AI
Catat penggunaan AI secara jujur sesuai format tugas. Anggota kelompok tetap perlu memahami, meninjau, dan menguji hasil sebelum menggabungkannya.
