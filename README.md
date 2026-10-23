# TradeFlow — Trading Journal

Aplikasi single-page untuk mencatat P&L trading dalam IDR, melihat estimasi USD, modal awal, equity, ROI, statistik, grafik, foto profil, dan ekspor CSV.

## Menjalankan
Buka `index.html` di browser. Internet diperlukan untuk memuat Tailwind CSS, Chart.js, dan fitur kurs online. Data jurnal disimpan di localStorage browser.

## Publikasi GitHub Pages
1. Buat repository baru bernama `tradeflow-journal` di GitHub.
2. Upload `index.html` dan `README.md` ke root repository, lalu Commit changes.
3. Buka Settings → Pages.
4. Pada Build and deployment pilih Deploy from a branch, branch `main`, folder `/(root)`, lalu Save.
5. Tunggu deployment; situs biasanya tersedia di `https://USERNAME.github.io/tradeflow-journal/`.

## Catatan
- Data tersimpan lokal di browser, tidak otomatis tersinkron antarperangkat. Ekspor CSV untuk cadangan.
- P&L diinput manual; aplikasi tidak terhubung ke broker dan tidak mengeksekusi transaksi.
- ROI kumulatif dihitung dari net P&L dibagi modal awal. Satu catatan per tanggal dipakai agar statistik harian konsisten.
