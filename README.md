# Gudang Retur Marketplace

Aplikasi PWA untuk mencocokkan paket retur marketplace dengan data Pixel.

## Fitur
- Database awal berisi 37 Order ID unik dari data Pixel.
- Pencocokan nomor pesanan atau resi melalui input manual dan kamera barcode.
- Impor Excel/CSV dengan kolom Order ID dan Tracking ID/resi.
- Riwayat retur, status selesai, pencarian, dan ekspor CSV.
- Penyimpanan lokal pada browser dan cache offline dasar.

## Publikasi
Workflow GitHub Actions pada `.github/workflows/pages.yml` menerbitkan aplikasi ke GitHub Pages setiap ada push ke branch `main`.

Di GitHub buka **Settings → Pages**, lalu pilih **GitHub Actions** sebagai Source bila diminta. Setelah workflow berhasil, buka `https://pasartanjung025-lang.github.io/Neoma-returan-/` melalui Chrome Android, lalu pilih **Tambahkan ke layar utama / Instal aplikasi**.

## Catatan
Aplikasi ini PWA yang dipasang dari Chrome, bukan APK native. Kamera memerlukan HTTPS dan izin dari pengguna. Impor Excel menggunakan SheetJS CDN sehingga membutuhkan internet saat mengunggah Excel. Data tersimpan lokal di browser/perangkat.
