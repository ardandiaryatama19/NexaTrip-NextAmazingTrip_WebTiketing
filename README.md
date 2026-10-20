# 🚀 NexaTrip — Platform Pemesanan Tiket & Travel

> **Proyek Akademik Mata Kuliah Struktur Data & Algoritma**  
> _Universitas / Program Studi: Pendidikan Teknologi Informasi_

---

## 📌 Deskripsi Proyek

**NexaTrip** adalah platform pemesanan tiket perjalanan modern berbasis web yang dikembangkan untuk memenuhi tugas UTS mata kuliah **Struktur Data dan Algoritma**. Aplikasi ini mengintegrasikan konsep-konsep dasar struktur data dan algoritma ke dalam antarmuka interaktif yang realistis (dilengkapi simulasi pembayaran OTP/QRIS, keranjang tiket belum dibayar, serta animasi koper).

---

## 🛠️ Implementasi Struktur Data & Algoritma

Proyek ini secara eksplisit mengimplementasikan komponen-komponen wajib berikut:

### 1. 🏗️ Struct (ES6 Class)

Menggunakan paradigma _Object-Oriented Programming_ melalui ES6 Class untuk mendefinisikan struktur data entitas utama:

- `Ticket`: Model untuk data tiket perjalanan (ID, Maskapai/Hotel, Asal, Tujuan, Harga, Kategori).
- `CartItem`: Model untuk item keranjang pembayaran tertunda (_Pending Payment_).

### 2. 📊 Array Master & Dinamis

- **Array Master (`TICKET_DATABASE`)**: Menyimpan seluruh koleksi data tiket master.
- **Array Keranjang (`pendingCart`)**: Mengelola daftar transaksi tiket yang belum dibayar secara dinamis.

### 3. 🔗 Pointer & Memory Reference

- Menggunakan referensi memori objek JavaScript untuk melakukan pembaruan status transaksi (_Unpaid_ $\rightarrow$ _Paid_) secara _in-place_ tanpa menduplikasi data di memori.

### 4. 🔄 Sorting Algorithm: Bubble Sort

- **Algoritma**: Bubble Sort diimplementasikan untuk mengurutkan daftar tiket berdasarkan **Harga Terendah** atau **Harga Tertinggi**.
- **Visualisasi Log**: Dilengkapi dengan **Terminal Log Real-time** pada antarmuka web untuk menampilkan setiap iterasi, pertukaran indeks (_swapping_), dan status komparasi data.

### 5. 🔍 Searching Algorithm: Linear Search

- **Algoritma**: Linear Search digunakan untuk pencarian tiket berdasarkan kata kunci (nama maskapai, kota tujuan, atau atraksi).
- **Visualisasi Log**: Pencarian mencatat dan menampilkan log eksekusi pencarian langkah-demi-langkah pada terminal interaktif.

---

## 🚀 Fitur Unggulan Antarmuka

- **Animate Zipper Opening**: Animasi koper membelah secara vertikal saat halaman pertama kali dimuat.
- **Simulasi Pembayaran Interaktif**: Fitur konfirmasi OTP dan batas waktu bayar QRIS.
- **Live Algorithm Terminal**: Panel terminal bawaan untuk memantau eksekusi algoritma di latar belakang.

---

## 👤 Pengembang

- **Nama**: Ardandi Ilham Aryatama
- **NIM / ID**: _(Isi NIM Anda di sini)_
- **Mata Kuliah**: Struktur Data dan Algoritma
