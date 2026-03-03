# Pemrograman Web - Week 2

## Deskripsi

Proyek ini adalah aplikasi web sederhana yang dikembangkan sebagai bagian dari kursus Pemrograman Web, tugas Minggu 2. Ini menampilkan halaman login dan tabel nilai siswa dengan gaya yang sangat mewah, termasuk gradien animasi, efek glowing, dan elemen interaktif. Aplikasi menggunakan JavaScript sisi klien untuk autentikasi dasar dan pengalihan halaman.

## Fitur

- **Otentikasi Pengguna**: Formulir login sederhana dengan validasi nama pengguna dan kata sandi.
- **Tabel Nilai**: Menampilkan nama siswa, skor di Kimia, Fisika, Biologi, dan skor rata-rata.
- **Desain Responsif**: Menggunakan Flexbox untuk pemusatan dan tata letak responsif.
- **UI Animasi**: Termasuk gradien animasi, teks glowing, efek hover pada baris tabel, dan animasi fade-in formulir.
- **Kontrol Akses**: Tabel nilai hanya dapat diakses setelah login berhasil, diberlakukan melalui sessionStorage.
- **Gaya Modern**: Menggunakan fitur CSS3 seperti gradien, keyframes, backdrop-filter, dan box-shadow untuk antarmuka yang menarik secara visual.

## Cara Menjalankan

1. Pastikan Anda memiliki Python terinstal di sistem Anda.
2. Navigasikan ke direktori proyek di terminal Anda.
3. Jalankan perintah berikut untuk memulai server HTTP lokal:
   ```
   python3 -m http.server 8000
   ```
4. Buka browser web Anda dan buka `http://localhost:8000/login.html`.
5. Login dengan nama pengguna: `admin` dan kata sandi: `password`.
6. Setelah login berhasil, Anda akan diarahkan ke halaman tabel nilai.

## Tangkapan Layar

### Halaman Login

![Halaman Login](screenshots/login.png)

### Tabel Nilai

![Tabel Nilai](screenshots/table.png)

## Teknologi yang Digunakan

- **HTML5**: Struktur halaman web.
- **CSS3**: Styling, animasi, dan desain responsif.
- **JavaScript**: Logika sisi klien untuk validasi login dan pengalihan.
- **Google Fonts**: Font Poppins untuk tipografi.

## Struktur Proyek

- `login.html`: Halaman login dengan formulir autentikasi.
- `tabel.html`: Halaman tabel nilai, hanya dapat diakses setelah login.
- `README.md`: File dokumentasi ini.

## Penulis

Dikembangkan oleh Ustu Bina Syahdiba (5054241001) untuk tugas Pemrograman Web Minggu 2.
