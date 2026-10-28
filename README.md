# 🎂 Website Kejutan Ulang Tahun - Putri Kireina Nastiti

Website kejutan ulang tahun interaktif untuk **Putri Kireina Nastiti (5 November)** dengan tema warna khusus, navigasi berbasis tombol (non-scrollable), musik romantis, kuis kejujuran rumah tangga, kupon gosok staycation di Hotel Horison Ultima Bekasi lengkap dengan peta Google Maps, serta fitur unggah foto kenangan sendiri.

---

## 🎨 Palet Warna yang Digunakan
- `#E0D4E3` (Soft Lilac - Latar Belakang & Aksen Terang)
- `#C2A8C7` (Muted Mauve - Border & Pembatas Kartu)
- `#A47DAB` (Primary Purple - Tombol Unggah & Aksen Utama)
- `#7A5C80` (Deep Plum - Tombol Utama & Judul Elegan)
- `#533D57` (Dark Eggplant - Teks Kontras & Elemen Tegas)

---

## ✨ Fitur-Fitur Utama yang Diterapkan:
1. **Halaman Pertama dengan Foto PNG Transparan**:
   - Inisial nama telah diganti dengan foto PNG tanpa latar belakang (*transparent cutout photo*).
   - Tampilan bersih tanpa tombol teknis/unggah, siap langsung disajikan untuk hadiah.

2. **Navigasi Berbasis Tombol (Non-Scrollable)**:
   - Halaman utama tidak bisa di-scroll bebas (`overflow: hidden`).
   - Pengguna berpindah tahap menggunakan tombol **"Selanjutnya" / "Sebelumnya"** di navigasi bawah atau tombol aksi di setiap kartu slide.
   - Ada indikator progres step di bagian atas (*"Halaman X dari 6"*).
2. **Bahasa Indonesia Penuh**:
   - Seluruh teks, dialog kuis, kupon, pesan cinta, dan notifikasi telah disesuaikan ke Bahasa Indonesia yang romantis dan hangat.
3. **Lagu Latar YouTube Spesial & Autoplay**:
   - Terintegrasi langsung dengan lagu pilihan: [YouTube Video (-wQlUemIRts)](https://www.youtube.com/watch?v=-wQlUemIRts).
   - Dikonfigurasi otomatis memutar (*autoplay*) dan berulang (*looping*).
   - Dilengkapi sistem *instant interaction trigger* untuk melewati batasan autoplay pada browser HP (begitu layar disentuh atau tombol *"Buka Kejutan"* ditekan, lagu langsung otomatis mengalun jernih).
   - Tombol toggle di pojok kanan atas dengan animasi gelombang suara (*sound wave*).
4. **Kuis Interaktif & Tombol Kabur (Dodging Button)**:
   - Pertanyaan 1: *"Siapa pemegang kedaulatan mutlak di rumah kita?"*
     - Jika mencoba klik *"Suamiku Tersayang"*, tombolnya akan menghindar dan berpindah-pindah posisi dengan komentar lucu.
     - Pilihan *"Putri Kireina Nastiti"* lolos dengan taburan confetti!
   - Pertanyaan 2: *"Prestasi terbaik seumur hidup suamimu?"* -> *"Berhasil menikahi Putri Kireina Nastiti"*.
5. **Kupon Gosok Staycation + Embed Peta Hotel**:
   - Kartu gosok interaktif emas-lilac berhadiah **Staycation Romantis di Horison Ultima Bekasi**.
   - Embed Google Maps resmi Horison Ultima Bekasi lengkap dengan link langsung petunjuk arah.
6. **Galeri Polaroid + Fitur Unggah Foto Langsung**:
   - Foto polaroid bisa di-tap untuk berputar 3D dan membaca catatan di baliknya.
   - **Fitur Unggah Foto**: Tekan tombol *"Ganti / Unggah Foto Sendiri"* untuk memilih foto dari galeri HP/laptop. Foto otomatis tersimpan di peramban (`localStorage`) sehingga tidak hilang saat halaman di-refresh.
7. **Surat Cinta Tulus & Tombol Kirim Ciuman**:
   - Surat cinta dari hati seorang suami untuk Putri.
   - Tombol kirim ciuman virtual dengan ledakan emoji 💖, 💋, ✨, dan getaran ponsel.

---

## 🚀 Cara Host Gratis di GitHub Pages (2 Menit)

### Cara 1: Lewat Terminal (Mac)
```bash
cd /Users/fauzy/.gemini/antigravity/scratch/putri-birthday-website
git init
git add .
git commit -m "Selamat Ulang Tahun Putri Kireina Nastiti! ❤️"
git branch -M main
git remote add origin https://github.com/USERNAME_GITHUB_KAMU/NAMA_REPO_KAMU.git
git push -u origin main
```

### Cara 2: Lewat Web GitHub (Drag & Drop)
1. Buat repository baru di [github.com/new](https://github.com/new) (contoh nama: `untuk-putri-tercinta`).
2. Pastikan diset **Public**.
3. Klik **"uploading an existing file"** dan tarik file `index.html` beserta file `song.mp3` ke browser.
4. Klik **Commit changes**.

### Mengaktifkan GitHub Pages:
1. Di repository GitHub Anda, klik menu **Settings** → **Pages** (di menu sebelah kiri).
2. Pada bagian **Branch**, pilih `main` dan folder `/ (root)`, lalu klik **Save**.
3. Tunggu sekitar 1 menit, website akan aktif di URL:
   `https://USERNAME_GITHUB_KAMU.github.io/NAMA_REPO_KAMU/`

---

## 💻 Pratinjau Langsung di Mac Sekarang
Jalankan perintah ini di terminal untuk langsung membukanya di browser:
```bash
open /Users/fauzy/.gemini/antigravity/scratch/putri-birthday-website/index.html
```
