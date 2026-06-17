# Kalkulator Finansial KBLI

Kalkulator Finansial KBLI adalah aplikasi web interaktif satu halaman (single-page application) yang dirancang untuk membantu surveyor dan pemilik usaha menghitung rekapitulasi pendapatan dan pengeluaran secara bulanan & tahunan. Rincian formulir isian disesuaikan secara otomatis berdasarkan rincian standar pengeluaran dan pendapatan kategori Klasifikasi Baku Lapangan Usaha Indonesia (KBLI).

## Fitur Utama

- **Otomatisasi KBLI**: Formulir pendapatan dan pengeluaran dinamis yang menyesuaikan dengan kategori KBLI yang dipilih.
- **Responsif & Mobile Friendly**: Antarmuka premium menggunakan Tailwind CSS yang optimal di layar HP, tablet, maupun desktop.
- **Deteksi Defisit otomatis**: Dilengkapi dengan notifikasi peringatan jika jumlah pengeluaran melampaui pendapatan.
- **Export PDF**: Fitur cetak laporan langsung ke format PDF standar cetak untuk dokumentasi fisik.
- **Penyimpanan Draft otomatis**: Draft isian disimpan di penyimpanan lokal (*Local Storage* peramban) agar data tidak hilang ketika halaman dimuat ulang.

## Teknologi

- HTML5 (Struktur semantik)
- Vanilla Javascript (Logika perhitungan & autosave)
- Tailwind CSS CDN (Desain premium)
- Google Fonts (Outfit & Plus Jakarta Sans)

## Deployment ke GitHub Pages

Aplikasi ini bersifat statis (hanya satu file `index.html`), sehingga sangat mudah untuk dideploy menggunakan GitHub Pages.

### Cara Menjalankan Lokal

1. Clone repositori ini.
2. Buka file `index.html` secara langsung di browser Anda, atau jalankan menggunakan server lokal:
   ```bash
   # Menggunakan Python
   python -m http.server 8000
   ```
3. Akses di `http://localhost:8000`.
