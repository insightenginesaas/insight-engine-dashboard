# Insight Engine | Harga Kripto 🚀

Insight Engine adalah sebuah *dashboard* berbasis web sederhana untuk memantau pergerakan harga 8 aset kripto utama. Proyek ini merupakan tugas kuliah kelompok yang mengambil sumber data dari **CoinGecko API** dan menyimpannya ke dalam **Google Sheets**, lalu ditampilkan secara *real-time* ke antarmuka web.

## ✨ Fitur Utama

- **Tabel Harga Terkini:** Menampilkan Harga, Perubahan (24 jam), Market Cap, dan Volume (24 jam) untuk 8 koin kripto terpopuler (BTC, ETH, SOL, XRP, DOGE, POL, USDT, LINK).
- **Grafik Interaktif:** Visualisasi pergerakan harga koin dalam bentuk grafik garis yang interaktif.
- **Filter Rentang Waktu:** Pengguna dapat melihat riwayat pergerakan harga dalam 1 hari, 7 hari, 30 hari, atau semua data.
- **Pembaruan Otomatis:** Halaman akan otomatis mengambil data terbaru (*auto-refresh*) setiap 3 menit tanpa perlu me-reload halaman web.
- **Ringan & Responsif:** Dibangun dalam satu file HTML (*Single File*) tanpa *framework* berat, sehingga sangat cepat dimuat.

## 🛠️ Teknologi yang Digunakan

- **Frontend:** HTML5, CSS3, Vanilla JavaScript (DOM & Fetch API)
- **Library Grafik:** [Chart.js](https://www.chartjs.org/) (via CDN)
- **Backend / Database:** Google Apps Script & Google Sheets
- **Sumber Data API:** CoinGecko API

## 📂 Struktur File

Proyek ini sangat sederhana dan seluruh kodenya (HTML, CSS, dan JavaScript) berada di dalam satu file utama:
\`\`\`text
├── index_simple.html  # File utama berisikan antarmuka dan logika program
└── README.md          # Dokumentasi proyek
\`\`\`

## 🚀 Cara Menjalankan Proyek (Local)

Karena proyek ini hanya membutuhkan *client-side rendering* dan mengambil data dari API publik (Google Apps Script), kamu tidak perlu menginstal *dependency* atau menjalankan *local server* yang rumit.

1. *Clone* repositori ini ke komputer lokal kamu:
   \`\`\`bash
   git clone https://github.com/username/insight-engine.git
   \`\`\`
2. Buka folder proyek.
3. Klik ganda pada file `index_simple.html` untuk membukanya langsung di browser (Chrome, Firefox, Safari, dll).
4. Selesai! Data akan otomatis dimuat.

## 🌐 Live Preview / Deployment

Untuk membuat website ini online agar bisa diakses siapa saja, kamu bisa menggunakan layanan *hosting* gratis seperti:
- **GitHub Pages** (Rekomendasi)
- **Vercel**
- **Netlify**

Cukup *deploy* file `index_simple.html` ini pada layanan tersebut.

## 📝 Catatan Penting
* *Endpoint* API pada proyek ini menggunakan URL Google Apps Script yang membaca data dari Google Sheets. Pastikan *script* di Google Apps Script selalu berjalan (*trigger* aktif) agar data tetap *up-to-date*.
* Proyek ini dikembangkan sebagai pemenuhan proyek kelompok mata kuliah.
```eof

File README di atas sudah merangkum fitur, teknologi, dan cara penggunaan dari kode yang ada di `index_simple.html`. Kamu tinggal *copy-paste* teksnya atau mengunduhnya dan meletakkannya di folder yang sama dengan proyekmu sebelum di-*push* ke GitHub. 

Ada bagian yang ingin kamu ubah, misalnya menambahkan nama anggota kelompokmu di dalamnya?
