# Lab6Web:JavaScript DOM dan Event Handling
# Identitas Praktikum
- Mata kuliah: Pemrograman Web
- Pertemuan: 7
- Topik: JavaScript DOM dan Event Handling
- Nama: \(Alfi Iftihal Nurul Afiat\)
- NIM: \(312510041\)
- Kelas: \(I251D\)
- Repository: Lab6Web
# 1. Tujuan Praktikum
1. Memahami DOM sebagai representasi dokumen HTML yang dapat diakses
   dan dimanipulasi JavaScript.
2. Menggunakan ID dan selector untuk memilih elemen HTML.
3. Mengubah teks, kelas CSS, dan tampilan elemen melalui JavaScript.
4. Menangani interaksi pengguna menggunakan ````addEventListener()````.
5. Membuat validasi form dan menampilkan pesan sesuai kondisi input.
6. Membuat halaman interaktif yang memiliki beberapa fungsi.
# 2. Struktur Folder
````
Lab6Web/
├── index.html
├── style.css
├── script.js
├── README.md
└── ss/
````
# 3. Cara Menjalankan
1. Buka folder ````Lab6Web```` di Visual Studio Code.
2. Pastikan ````index.html````, ````style.css````, dan ````script.js```` berada dalam
   folder yang sama.
3. Pastikan HTML menghubungkan CSS dengan
   ````<link rel="stylesheet" href="style.css">````.
4. Untuk versi akhir, pastikan script menggunakan
   ````<script src="script.js" defer></script>````.
5. Buka ````index.html```` di browser.
6. Untuk melihat error, buka Developer Tools dengan ````F12```` dan pilih tab
   Console.
# 4. Langkah Kerja dan Output
## Latihan 1 --- Mengubah teks dengan DOM
**Langkah:** Memilih elemen ````judul```` dan ````pesan```` menggunakan
````getElementById()````, kemudian mengubah teks memakai ````textContent````.

**Output yang diharapkan:** Judul berubah menjadi "Belajar JavaScript
DOM" dan paragraf menjadi "Konten berhasil diubah oleh JavaScript."
![ss](ss/ft1.png) ![ss](ss/ft2.png)
