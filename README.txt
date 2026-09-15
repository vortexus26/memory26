VORTEXUS 26 — LENGKAP + FILTER JURUSAN + GITHUB PAGES
========================================================

VERSI INI SUDAH MEMILIKI:
- Login pilihan jurusan/kelas.
- Filter kategori dan jurusan.
- Pencarian galeri.
- Acak kenangan + spotlight.
- Preview foto/video sebelum upload.
- Lightbox foto.
- Statistik total foto/video.
- Panel admin.
- Tampilan mobile/desktop.
- Versi GitHub Pages (index.html/login.html/admin.html).
- Versi PHP + MySQL tetap dipertahankan (index.php, login.php, upload.php, admin/).

PENTING: GITHUB PAGES
---------------------
GitHub Pages hanya menjalankan file statis HTML/CSS/JS. PHP dan MySQL TIDAK dijalankan.
Karena itu, index.html memakai IndexedDB untuk demo upload lokal: data hanya tersimpan di browser/perangkat yang dipakai.
Login pada versi GitHub Pages juga hanya simulasi client-side, bukan keamanan server.

CARA HOSTING DI GITHUB PAGES
----------------------------
1. Buat repository baru di GitHub.
2. Upload ISI folder VORTEXUS26_LENGKAP ke repository.
   Jangan mengubah nama file/folder assets.
3. Pastikan index.html ada di root repository.
4. Buka Settings -> Pages.
5. Pada Build and deployment pilih Deploy from a branch.
6. Pilih branch utama (biasanya main) dan folder / (root), lalu Save.
7. Tunggu proses deployment. URL akan diberikan GitHub pada halaman Pages.

CATATAN:
- .nojekyll sudah disediakan.
- Jangan menghapus assets/images, assets/css, atau assets/js.
- Untuk GitHub Pages, halaman utama menggunakan index.html.

JIKA MAU UPLOAD BISA DILIHAT SEMUA ORANG
----------------------------------------
Gunakan versi PHP + MySQL yang juga ada di folder ini.
File penting:
- index.php
- login.php
- auth.php
- config.php
- upload.php
- admin/
- database/vortexus26.sql

Hosting yang diperlukan harus mendukung PHP + MySQL, misalnya cPanel/shared hosting.
Import database/vortexus26.sql melalui phpMyAdmin, lalu sesuaikan config.php dengan database hosting.

PASSWORD LOGIN AWAL
-------------------
PPLDG26     -> PPLDG26
OTOMOTIF26  -> OTOMOTIF26
ATPH26      -> ATPH26
BUSANA26    -> BUSANA26

KEAMANAN
--------
Versi PHP adalah versi yang tepat untuk data bersama karena login, upload, approval, dan database berada di server.
Versi GitHub Pages cocok untuk demo/landing page atau arsip statis. Jangan menganggap login JS sebagai perlindungan data rahasia.
