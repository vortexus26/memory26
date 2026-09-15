VORTEXUS 26 — GITHUB PAGES
===========================

VERSI REVISI: LOGIN WAJIB SEBELUM UPLOAD

Fitur utama:
- Website VORTEXUS 26 SMK Negeri 1 Patokbeusi
- Foto & video archive
- Filter kategori
- Filter jurusan: PPLDG 26, OTOMOTIF 26, ATPH 26, BUSANA 26, Lainnya
- Pencarian & acak kenangan
- Login kelas/jurusan
- Upload TERKUNCI untuk tamu
- Tamu yang klik area upload diarahkan untuk login
- Form upload tetap memverifikasi session saat submit
- Jurusan upload otomatis mengikuti akun yang sedang login
- Upload disimpan sebagai pending dan baru tampil setelah disetujui Admin Lokal
- Responsive HP/desktop
- GitHub Pages compatible (mode static menggunakan IndexedDB + localStorage)

LOGIN DEMO:
PPLDG26 / PPLDG26
OTOMOTIF26 / OTOMOTIF26
ATPH26 / ATPH26
BUSANA26 / BUSANA26

PENTING GITHUB PAGES:
1. Buka folder VORTEXUS26_LENGKAP hasil ekstrak ZIP.
2. Copy SEMUA ISI folder tersebut ke ROOT repository GitHub.
3. Pastikan index.html langsung berada di root repository.
4. Folder assets wajib ikut dicopy.
5. GitHub Pages: Settings > Pages > Deploy from branch > main > /(root).
6. Tunggu beberapa menit lalu hard refresh (Ctrl+Shift+R).

CATATAN:
GitHub Pages tidak menjalankan PHP/MySQL. Fitur upload pada versi ini adalah demo per-browser (IndexedDB), jadi file yang diupload dari satu perangkat tidak otomatis terlihat di perangkat lain. Untuk upload bersama yang benar-benar tersimpan di server, gunakan hosting yang mendukung PHP + MySQL dan file PHP yang sudah disertakan.
