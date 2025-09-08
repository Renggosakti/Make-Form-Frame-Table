# Latihan Web Interaktif

Website ini dibuat sebagai latihan pengembangan web interaktif menggunakan HTML, CSS, dan JavaScript. Fitur utama meliputi:

- **Tabel Mahasiswa:** Menampilkan daftar mahasiswa beserta nilai ETS dan EAS.
- **Form Registrasi:** Menambahkan data mahasiswa baru ke tabel secara dinamis.
- **LocalStorage:** Data mahasiswa tersimpan sehingga tetap ada saat halaman di-refresh.
- **Frame Layout:** Menampilkan iframe untuk konten eksternal.
- **Pemutar Musik:** Memutar file audio MP3 langsung di halaman.

---

## Cara Mengakses

1. Buka `index.html` untuk halaman utama secara lokal.
2. Data default sudah tersedia untuk 2 mahasiswa.
3. Tambah data baru melalui form registrasi, data otomatis tersimpan di browser.
4. Semua perubahan data tersimpan di localStorage, sehingga saat halaman di-refresh data tetap ada.

---

## Struktur File

latihan-web-interaktif/
│
├── index.html -> Halaman utama yang menampilkan tabel, form, iframe, dan pemutar musik.
├── style.css -> File CSS terpisah (opsional) untuk styling.
├── script.js -> File JavaScript terpisah (opsional) untuk interaksi form dan tabel.
├── lagu.mp3 -> File audio untuk pemutar musik.
├── assets/ -> Folder untuk menyimpan gambar, ikon, atau media tambahan.
│ ├── logo.png
│ └── background.jpg
├── README.md -> Dokumentasi proyek ini.
└── LICENSE -> Lisensi proyek (opsional).

---

## Fitur

1. **Tabel Dinamis:** Tabel otomatis menampilkan data default dan menambahkan data baru dari form.
2. **Form Validasi:** Form memeriksa kesamaan password sebelum menambahkan data.
3. **Penyimpanan Permanen:** Data tersimpan menggunakan `localStorage` sehingga tidak hilang saat reload.
4. **Navigasi Sidebar & Header:** Memudahkan berpindah antar bagian halaman.
5. **Iframe & Musik:** Mendukung konten eksternal dan pemutaran audio langsung.

---


- Folder `assets/` bersifat opsional, bisa digunakan untuk gambar atau media lain agar proyek tetap rapi.
- Pastikan browser mendukung `localStorage` agar data mahasiswa tetap tersimpan.
