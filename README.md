# AM Finance — Panduan instalasi Android

Paket ini adalah **PWA (Progressive Web App)**, bukan APK native. Agar bisa dipasang dari Chrome Android seperti aplikasi, file harus diterbitkan di alamat HTTPS (contohnya GitHub Pages).

## Instalasi lewat GitHub Pages (bisa dari browser HP)
1. Download ZIP dan ekstrak. Hasilnya folder `am-finance-app`.
2. Buka GitHub dan buat repository baru bernama `am-finance` (Public).
3. Masuk repository → **Add file → Upload files**.
4. Buka folder `am-finance-app` hasil ekstrak di pengelola file HP, lalu unggah **isi foldernya** (index.html, manifest.webmanifest, sw.js, README.md, dan folder assets). Jangan unggah ZIP mentah saja.
5. Tekan **Commit changes**.
6. Di repository buka **Settings → Pages**.
7. Pada **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/(root)`, lalu tekan **Save**.
8. Tunggu sampai alamat GitHub Pages tampil, biasanya `https://USERNAME.github.io/am-finance/`.
9. Buka alamat tersebut di Chrome Android. Tekan menu ⋮ → **Install app** atau **Tambahkan ke layar utama**.
10. Jalankan AM Finance dari ikon yang muncul di layar utama.

## Fitur
- Saldo total, Cash, dan Mobile Banking.
- Catat pemasukan dan pengeluaran manual.
- Grafik, analitik harian/mingguan/bulanan.
- Kategori pengeluaran, pencarian transaksi, tagihan.
- AI Coach lokal berbasis aturan sederhana.
- Cetak / simpan laporan PDF melalui dialog cetak browser.
- Backup dan restore JSON, penyimpanan lokal, cache offline.

## Catatan
- Ini bukan APK dan tidak dapat dipasang dengan membuka ZIP. PWA dipasang dari situs HTTPS melalui Chrome.
- Tidak ada koneksi otomatis ke rekening bank. Saldo harus diinput sendiri.
- Data disimpan pada browser di perangkat. Backup berkala melalui Pengaturan.
- AI Coach adalah analisis lokal berbasis aturan, bukan layanan AI cloud.
- Animasi aplikasi berlangsung saat dibuka dan berpindah halaman. Animasi saat aplikasi ditutup oleh sistem dikendalikan Android.
