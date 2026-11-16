# 🧭 Personal Tracker v1.0

![Version](https://img.shields.io/badge/version-1.0.0-6366f1?style=flat-square)
![Tech](https://img.shields.io/badge/stack-HTML5%20%7C%20CSS3%20%7C%20Vanilla%20JS-10b981?style=flat-square)
![Storage](https://img.shields.io/badge/storage-LocalStorage%20(Offline--First)-f59e0b?style=flat-square)
![UI](https://img.shields.io/badge/design-Glassmorphism-ec4899?style=flat-square)

**Personal Tracker** adalah aplikasi web pelacak produktivitas, kebiasaan, keuangan, kesehatan, dan gaya hidup serba ada (*all-in-one*) yang berjalan sepenuhnya di browser dalam satu berkas HTML mandiri (*single-file architecture*) tanpa memerlukan backend, database eksternal, ataupun koneksi internet.

---

## ✨ Fitur Utama

### 🏠 1. Beranda & Relaksasi (*Satisfy*)
* **Ringkasan KPI Harian:** Pantau sekilas waktu tercatat, persentase progres, kebiasaan selesai, level energi terakhir, halaman buku terbaca, pengeluaran bulanan, sesi olahraga, dan skor BMI.
* **Monitor Kebiasaan Hari Ini:** Centang langsung atau tambah hitungan harian (`+1`/`-1`) tanpa berpindah tab.
* **Sticky Notes:** Catatan tempel warna-warni dengan fitur *pin* (sematkan) dan stempel waktu pembaruan.
* **Modul Relaksasi Interaktif (*Satisfy*):**
  * 🎹 **Piano:** 2 oktaf interaktif (Grand Piano, Electric Piano, Synth Pad, Music Box, Marimba) mendukung sentuhan layar maupun keyboard PC (`A–V` & `W–P`).
  * ♟ **Catur:** Papan catur lengkap dengan mode lawan AI sederhana atau 2 pemain.
  * 🫧 **Squishy:** Mainan virtual elastis (Mochi, Spons, Stroberi, Jeruk, Pisang) dengan efek tarik-lepas dan suara.
  * 🌊 **Air Laut:** Simulasi riak air berbasis *HTML5 Canvas* dengan efek pantulan cahaya dan suara percikan air.

### ⏱ 2. Pelacak Waktu (*Time Tracker*) & Pomodoro
* **Live Timer & Multi-Tracking:** Catat durasi aktivitas hingga hitungan detik secara bersamaan atau tunggal, dilengkapi pencatatan waktu kosong (*idle time*).
* **Preset & Input Manual:** 14+ preset aktivitas siap pakai, target durasi harian, serta editor riwayat waktu detail.
* **Timer Pomodoro Ringkas:** Mode Fokus, Istirahat Pendek, dan Istirahat Panjang dengan durasi yang dapat dikustomisasi.

### 📈 3. Progres Terukur & Manajemen Task
* **Progres Terukur:** Pelacakan target berbasis **Angka** (dengan langkah `+`/`−`) maupun **Checklist Bertingkat** (sub-tugas bersarang) lengkap dengan log riwayat perubahan.
* **Manajemen Task:**
  * Kategori daftar kustom, penanda **Favorit (`★`)**, serta sub-task dengan tanggal & jam jatuh tempo.
  * **Task Rutinitas (`🔁`):** Otomatis muncul kembali setiap periode (harian, mingguan, bulanan, atau tiap *N* hari) lengkap dengan penghitung statistik penyelesaian & terlewat.
  * Pengurutan fleksibel (tenggat waktu, abjad, favorit, atau *drag-and-drop* manual).

### ✅ 4. Pelacak Kebiasaan (*Habit Tracker*)
* **Dua Model Pelacakan:** Model Centang (`✓` Berhasil, `✗` Gagal, `−` Lewati) dan Model Hitungan Angka harian.
* **Frekuensi Target Fleksibel:** Target setiap hari, minimal/maksimal *X* kali seminggu, atau minimal *X* kali sebulan dengan pengisian status otomatis saat target periode tercapai.
* **Kalender & Pengingat:** Riwayat visual 60 hari ke belakang, catatan per tanggal, grafik capaian, kategori, pengurutan manual, serta pengingat notifikasi browser.

### ⚡ 5. Pelacak Energi
* Pencatatan tingkat energi harian (5 level emosi/stamina) dengan analisis rata-rata harian, pola berdasarkan waktu (dini hari hingga malam), serta kartu tips mengelola ritme sirkadian.

### 📚 6. Pelacak Buku & Bacaan
* Manajemen koleksi buku lengkap (ISBN, penerbit, genre, status kepemilikan/pinjaman, tanggal batas pengembalian, harga).
* Progres halaman dengan log bacaan otomatis, statistik halaman terbaca (harian hingga tahunan), dan rating bintang.

### 💰 7. Manajemen Keuangan
* **Multi-Dompet:** Kelola saldo Cash/Tunai, Rekening Bank, E-Wallet, Kartu Kredit, dan transfer antar dompet (dengan proteksi saldo anti-minus khusus dompet tunai).
* **Hutang & Piutang:** Pencatatan cicilan bayar, tambah pinjaman, bunga, dan riwayat transaksi yang terintegrasi otomatis dengan saldo dompet.
* **Anggaran & Tujuan:** Batas anggaran bulanan total maupun per kategori, target tabungan (*financial goals*), serta **Analisis Perilaku Keuangan** untuk mendeteksi potensi belanja impulsif.

### 🏋 8. Olahraga, Pernapasan & Musik
* **Latihan di Rumah:** 4 program latihan (Full Body, Core & Perut, HIIT Kardio, Tubuh Bawah) dengan 3 tingkat kesulitan dan **peragaan animasi SVG** di setiap gerakan.
* **Timer Interval Lari-Jalan:** Pengatur interval lari/jalan dengan panduan program pemula 8 minggu, serta perhitungan otomatis *pace* (menit/km), kecepatan, dan estimasi kalori terbakar.
* **Latihan Pernapasan:** Visualisasi gelombang napas interaktif dengan pola *Box Breathing*, *4-7-8*, *Power*, *Harmony*, *Anti-Stress*, maupun rasio kustom.
* **Mini Player SoundCloud:** Pemutar musik mengambang dengan daftar putar bawaan, *shuffle*, *repeat*, dan dukungan tautan SoundCloud kustom.

### ⚖ 9. Tubuh & Kalkulator Kalori
* **Kalkulator BMI, BMR & TDEE:** Menghitung berat badan ideal, metabolisme basal, dan kebutuhan kalori harian berdasarkan profil usia, gender, tinggi badan, dan tingkat aktivitas.
* **Log Makanan & Makronutrisi:** Database makanan lokal Indonesia siap pakai + input makanan kustom untuk memantau asupan **Kalori, Protein, Karbohidrat, dan Lemak** harian.

### 🎨 10. Kustomisasi UI & Cadangan Data
* **Tema Glassmorphism Dinamis:** Mode Terang/Gelap/Otomatis, warna aksen kustom, dua warna gradasi latar belakang, serta pengatur tingkat *blur* dan transparansi kaca.
* **Ekspor & Impor JSON:** Cadangkan atau pindahkan seluruh data antar perangkat dengan mudah melalui berkas `.json` maupun salin-tempel teks.

---
## Screenshot

---

## 🚀 Cara Menjalankan

Karena aplikasi ini dibangun tanpa dependensi eksternal (*zero-dependency*), Anda tidak perlu melakukan instalasi apa pun:

1. **Clone** repositori ini atau unduh berkas `personal_tracker_v1_0_p.html`:
   ```bash
   git clone [https://github.com/username-anda/personal-tracker.git](https://github.com/username-anda/personal-tracker.git)

2. Buka berkas personal_tracker_v1_0_p.html langsung menggunakan browser modern (Chrome, Edge, Firefox, Safari, atau browser mobile).

3. (Opsional) Tambahkan halaman ke layar utama (Add to Home Screen) di ponsel untuk pengalaman layaknya aplikasi native.

🔒 Privasi & Penyimpanan Data
100% Lokal: Seluruh data pengguna disimpan secara eksklusif di dalam localStorage browser perangkat Anda (key: pt_v2). Tidak ada data yang dikirim ke server pihak ketiga.

Audio Sintesis: Efek suara piano, timer, squishy, dan riak air dihasilkan secara langsung menggunakan Web Audio API bawaan browser.

👤 Kredit & Developer
Developer: Chamim Rasidin

Kolaborasi Pengembangan: Claude AI & Gemini

Versi: 1.0.0
