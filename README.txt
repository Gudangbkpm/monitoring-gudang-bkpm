MONITORING GUDANG BKPM — PWA

ISI PAKET
- index.html: halaman utama dengan menu Upload AST dan Cek AST
- style.css: tampilan responsif untuk HP
- manifest.webmanifest: identitas aplikasi saat dipasang
- service-worker.js: cache halaman utama agar shell aplikasi dapat dibuka offline
- icons/: ikon aplikasi

CARA HOSTING GRATIS DENGAN GITHUB PAGES
1. Buat akun di https://github.com
2. Buat repository baru bernama: monitoring-gudang-bkpm
3. Pilih Public, lalu Create repository.
4. Upload semua ISI folder ini (bukan folder luarnya) ke root repository.
5. Buka Settings > Pages.
6. Pada Build and deployment, pilih Deploy from a branch.
7. Pilih branch main dan folder /(root), lalu Save.
8. Tunggu hingga GitHub Pages menampilkan alamat website.

CARA PASANG DI IPHONE
1. Buka alamat GitHub Pages di Safari.
2. Tekan tombol Share.
3. Pilih Add to Home Screen / Tambahkan ke Layar Utama.
4. Tekan Add.

CARA PASANG DI ANDROID
1. Buka alamat GitHub Pages di Chrome.
2. Buka menu titik tiga.
3. Pilih Install app atau Add to Home screen.

CATATAN
- Halaman utama dan asetnya dapat di-cache untuk dibuka offline setelah pertama kali dimuat.
- Tombol Upload AST dan Cek AST membuka Google Apps Script yang sudah digunakan. Upload, login, dan pemeriksaan data tetap membutuhkan internet.
- Untuk memperbarui aplikasi, ganti file di GitHub. Cache akan diperbarui ketika service worker versi baru terpasang.
- Link Apps Script yang tertanam adalah deployment yang diberikan untuk proyek MONITORING GUDANG BKPM.
