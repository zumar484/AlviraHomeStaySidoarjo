# Alvira Homestay 1 & 2 Sidoarjo — Website Starter

## Isi project
- Website lama: beranda, kamar, galeri, tentang, kontak (dipertahankan).
- `booking.html`: formulir permintaan booking dan kalkulasi otomatis.
- `check-booking.html`: pencarian permintaan pada browser lokal.
- `booking.css`, `booking.js`: tampilan dan interaksi booking.

## Cara menjalankan
1. Ekstrak folder.
2. Buka folder menggunakan VS Code.
3. Jalankan dengan ekstensi Live Server atau server statis lokal.
4. Buka `index.html` atau `booking.html`.

## Data operasional yang digunakan
- Paket kedua unit bersama: Rp600.000/malam.
- Maksimal 8 tamu.
- Check-in 14.00 WIB; check-out 12.00 WIB.
- Uang jaminan Rp100.000, dikembalikan saat check-out.
- Nomor WhatsApp mengikuti nomor yang tercantum di website lama: 0812-3164-6523.

## Batasan penting versi ini
Ini adalah **prototype frontend**, bukan sistem booking multi-pengguna yang siap menerima transaksi publik. Permintaan booking diteruskan ke WhatsApp. Penyimpanan kode permintaan menggunakan localStorage browser, sehingga tidak tersinkron antar perangkat dan bukan bukti reservasi terkonfirmasi. Belum ada backend/database, kalender ketersediaan real-time, login admin, penguncian tanggal, QRIS dinamis, webhook, atau rekonsiliasi pembayaran.

Sebelum dipakai untuk bisnis secara live, tambahkan backend + database, autentikasi admin, validasi ketersediaan atomik, dan payment gateway QRIS. Jangan mengaktifkan pembayaran nyata sebelum kredensial gateway dan webhook diuji. Pastikan juga folder `images/` dari project asli ikut disertakan; folder tersebut tidak ada di enam file yang tersedia saat pembuatan paket ini, sementara beberapa halaman lama mereferensikan gambar di dalamnya.
