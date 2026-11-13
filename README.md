# Kalkulator HPP & Harga Jual Jeans

Aplikasi kalkulator biaya produksi jeans untuk menghitung HPP per pcs dan per batch, simulasi harga jual, pajak, serta laba.

## Fitur dari aplikasi
- Rincian biaya kain, jahit, aksesori, cucian, finishing, dan biaya lainnya.
- Perhitungan biaya per pcs dan total batch.
- Mode harga jual manual atau berdasarkan target laba.
- Perhitungan pajak dan laba bersih.
- Muat contoh data, kosongkan formulir, cetak/simpan PDF, dan salin ringkasan untuk WhatsApp.
- Penyimpanan otomatis lokal di perangkat/browser.

## Build APK Android
Setiap push ke branch `main` yang mengubah file aplikasi akan menjalankan GitHub Actions untuk membangun APK debug. Jalankan manual melalui tab **Actions → Build Kalkulator HPP Jeans APK → Run workflow** bila diperlukan.

Setelah workflow selesai, buka hasil run dan unduh artifact **Kalkulator-HPP-Jeans-Android-APK**. Ekstrak ZIP lalu instal file `app-debug.apk` di Android. Android mungkin meminta izin **Install unknown apps** untuk browser atau file manager yang digunakan.

## GitHub Pages
Workflow `.github/workflows/pages.yml` menerbitkan aplikasi web ke GitHub Pages. Aktifkan **Settings → Pages → Source: GitHub Actions** jika belum aktif.

## Catatan
Data kalkulasi disimpan di penyimpanan lokal perangkat/browser. Menghapus data aplikasi/browser dapat menghapus data tersimpan. APK debug ditandatangani untuk pengujian/pemasangan langsung, bukan rilis Play Store.
