# Merge PDF — Gabungkan File PDF di Browser

Widget penggabung PDF **single-file** (`mergepdf.html`) yang berjalan sepenuhnya di browser. Tidak ada file yang diunggah ke server — semua proses lokal, jadi tetap **privat & aman**. Cocok dipasang langsung di Blogspot/blog atau halaman HTML mana pun.

![Tema](https://img.shields.io/badge/tema-emerald-059669) ![Tanpa backend](https://img.shields.io/badge/proses-100%25%20lokal-success) ![Lisensi](https://img.shields.io/badge/lisensi-MIT-blue)

## ✨ Fitur

- **Multi-upload** — pilih atau seret beberapa PDF sekaligus.
- **Seret & jatuhkan berkali-kali** — tambahkan file kapan saja, bahkan setelah daftar tampil.
- **Atur urutan** — drag & drop reorder di desktop, tombol **↑ ↓** dan sentuh-tahan-seret di mobile/tablet.
- **Putar 90°** per file, **hapus** per file, atau **hapus semua**.
- **Pratinjau halaman pertama** tiap file (via PDF.js).
- **Responsif** & ramah sentuhan, tema Emerald.
- **Privat** — tidak ada upload ke server.

## 🚀 Cara Pakai

### Lokal
Cukup buka `mergepdf.html` di browser (Chrome/Firefox/Edge/Safari). Tidak perlu install apa pun.

### Pasang di Blogspot / blog
1. Buka editor postingan/halaman, pindah ke mode **HTML**.
2. Salin seluruh isi `mergepdf.html` dan tempel.
3. Publikasikan. Selesai.

> Widget memakai CDN untuk [PDF-LIB](https://pdf-lib.js.org/), [PDF.js](https://mozilla.github.io/pdf.js/), dan Font Awesome, jadi butuh koneksi internet saat dijalankan.

## 🧭 Alur Penggunaan

1. Klik atau seret beberapa **PDF** ke kotak unggah.
2. Atur urutan file (seret pratinjau di desktop, atau tombol ↑↓ / sentuh-tahan-seret di mobile).
3. Putar atau hapus file bila perlu.
4. Klik **Gabungkan PDF**.
5. Klik **Unduh PDF Gabungan**.
6. **Batalkan & Reset** untuk mulai dari awal.

## 🛠️ Teknologi

| Bagian            | Library                                   |
|-------------------|-------------------------------------------|
| Penggabungan PDF  | [pdf-lib](https://github.com/Hopding/pdf-lib) `1.17.1` |
| Render pratinjau  | [pdf.js](https://github.com/mozilla/pdf.js) `2.16.105` |
| Ikon              | Font Awesome `6.4.2`                       |
| Font              | Inter (Google Fonts)                       |

Tanpa build step, tanpa dependency lokal — murni HTML/CSS/JS.

## 🔒 Privasi

Seluruh pembacaan, pratinjau, dan penggabungan PDF dilakukan di dalam browser Anda menggunakan Web API. **Tidak ada data yang dikirim ke server mana pun.**

## 📄 Lisensi

[MIT](LICENSE) © zuseto
