# CENTIL — Landing Page Cenil Tradisional

Website statis HTML, CSS, dan JavaScript. Siap dipublikasikan melalui GitHub Pages.

## Sebelum upload
1. Buka `index.html` dengan editor teks atau VS Code.
2. Cari `const WHATSAPP_NUMBER = "6285229343096";` dan pastikan nomornya benar. Gunakan format internasional tanpa `+`, spasi, atau strip.
3. Harga masih ditandai sebagai contoh. Periksa bagian `const MENU`; setelah harga benar, ubah `PRICE_IS_SAMPLE = true` menjadi `false`.
4. Foto produk bisa ditambahkan ke folder `assets/images/` dengan nama:
   - `hero.jpg` — foto utama
   - `about.jpg` — foto bagian Cerita Kami
   - `original.jpg`, `rainbow.jpg`, `mix.jpg` — foto produk
   - `galeri1.jpg`, `galeri2.jpg`, `galeri3.jpg` — foto galeri
5. Foto sebaiknya JPG/WebP, ukuran file dikompres agar cepat dimuat. Jika foto belum ada, website tetap menampilkan ilustrasi cenil sebagai pengganti.

## Publikasi GitHub Pages
1. Buat repository baru di https://github.com/new (pilih **Public** bila link perlu diakses dosen).
2. Upload `index.html`, `README.md`, dan folder `assets` beserta foto-fotonya ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu klik **Save**.
6. Tunggu deployment selesai. Gunakan URL yang benar-benar ditampilkan GitHub Pages, biasanya berbentuk `https://USERNAME.github.io/NAMA-REPOSITORY/`.

## Catatan WhatsApp
Tautan `https://wa.me/` adalah tautan universal. Di HP biasanya membuka aplikasi WhatsApp bila tersedia; pada komputer dapat membuka WhatsApp Web atau aplikasi desktop sesuai pengaturan browser/perangkat.
