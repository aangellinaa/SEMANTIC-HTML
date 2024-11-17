# SEMANTIC-HTML
   Latihan Praktikum 1 Semantic HTML
   Nama : Angellina
   NIM  : 2205101019


## Analisis Perbedaan SEMANTIC-HTML
 1. **HTML**
   a. Sebelum diperbaiki
       - *Struktur Tidak Lengkap : Tag penting seperti `<html>`, `<head>`, dan `<body>` tidak digunakan, sehingga struktur dokumen HTML 
         belum sesuai standar.*
       - *Kurang Metadata : Tidak ada `<meta>` untuk informasi karakter encoding atau responsivitas.*
       - *Tidak Ada Judul Halaman : Tidak ada tag `<title>`, sehingga halaman tidak memiliki nama saat ditampilkan di tab browser.*
       - *Link ke CSS Eksternal Belum Dihubungkan : Tidak ada cara untuk menghubungkan ke file CSS untuk mendukung desain halaman.*
   b. Setelah diperbaiki
       - *Struktur Lengkap : Tag `<html>`, `<head>`, dan `<body>` ditambahkan untuk memenuhi standar HTML5.*
       - *Metadata Ditambahkan : `<meta charset="UTF-8">` memastikan dukungan karakter internasional. `<meta name="viewport" 
         content="width=device-width, initial-scale=1.0">` membantu agar halaman responsif di berbagai perangkat.*
       - *Judul Halaman : Tag `<title>` ditambahkan untuk menampilkan nama halaman di tab browser.*
       - *CSS Terhubung : File CSS eksternal dihubungkan melalui `<link>` untuk mendukung desain.*
       - *Struktur Lebih Rapi : Elemen-elemen HTML lebih tersusun sehingga mudah dipahami.*
  
2. CSS
   a. Sebelum diperbaiki
       - *Penulisan properti seperti 'text-align' dan 'padding' memiliki spasi tambahan yang tidak perlu, contohnya 'display : grid;' dan 
         'padding: 5px;'.*
       - *Menyertakan 'margin: 10px;' pada elemen 'body', yang membuat elemen grid memiliki jarak dari tepi layar.*
   b. Setelah diperbaiki 
       - *Penulisan properti lebih bersih tanpa adanya spasi yang tidak diperlukan, misalnya 'display: grid;'.*
       - *Properti margin dihapus, sehingga grid memenuhi seluruh tinggi dan lebar viewport '(height: 100vh;)'.*
