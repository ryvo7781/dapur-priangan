# Dapur Priangan — Website restoran Sunda

Website statis siap diunggah ke hosting statis, dibuat dengan HTML/CSS/JavaScript tanpa backend.

## Mulai
1. Buka `index.html` di browser untuk melihat demo.
2. Edit `CONFIG.whatsapp` di bagian bawah `index.html` dengan nomor WhatsApp bisnis yang benar (contoh format: `6281234567890`). Nomor sengaja kosong untuk mencegah pesanan salah alamat.
3. Ubah data `ITEMS` (menu, harga, deskripsi) sesuai menu yang benar-benar tersedia.
4. Ubah nama brand, alamat, jam buka, teks deskripsi, dan kontak di `index.html`.
5. Unggah `index.html` ke Netlify, Cloudflare Pages, GitHub Pages, atau hosting statis lain. Aktifkan HTTPS (biasanya disediakan oleh hosting).

## Fitur
- Responsive desktop & mobile
- Menu 9 contoh hidangan, filter kategori
- Keranjang interaktif dan kontrol kuantitas
- Ringkasan pesanan dan WhatsApp checkout (baru aktif setelah nomor bisnis diatur)
- Tidak ada pembayaran online, login, atau penyimpanan data pelanggan
- Keranjang hanya berada di memori browser; isi tidak bertahan setelah halaman dimuat ulang

## Catatan produksi
Konten menu dan harga saat ini contoh; gambar menu menggunakan foto referensi hidangan dari Wikimedia Commons (bukan foto produk restoran). Kredit dan lisensi tersedia di bagian menu dan assets/menu/credits.json. Unggah folder assets bersama index.html agar seluruh foto tampil. Google Fonts memerlukan koneksi internet, tetapi font fallback tetap tersedia. Jika membutuhkan order management, checkout pembayaran, inventori, panel admin, atau data pelanggan, perlu backend aman, validasi sisi server, autentikasi, kebijakan privasi, dan pengujian keamanan sebelum production.
