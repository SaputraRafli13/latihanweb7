Berikut langkah-langkah membuat program PHP dasar seperti itu:

# Langkah 1: Menjalankan Web Server
Pastikan web server lokal (seperti XAMPP, Laragon, atau WAMP) telah diaktifkan. Jika Anda menggunakan XAMPP, buka XAMPP Control Panel dan jalankan Apache.

# Langkah 2: Membuat Folder Proyek
Buat folder proyek di dalam direktori web server.
Jika menggunakan XAMPP, letakkan di C:\xampp\htdocs\.
Jika menggunakan Laragon, letakkan di C:\laragon\www\.
Contoh: Buat folder bernama lab7_php_dasar untuk proyek ini, sehingga path-nya menjadi C:\xampp\htdocs\lab7_php_dasar atau C:\laragon\www\lab7_php_dasar.

# Langkah 3: Membuat File PHP
Di dalam folder lab7_php_dasar, buat file PHP baru dengan nama php_dasar.php.

# Tambahkan kode berikut di dalam file tersebut:

php
Salin kode
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PHP Dasar</title>
</head>
<body>
    <h1>Belajar PHP Dasar</h1>
    <?php
        echo "Hello World";
    ?>
</body>
</html>

# Penjelasan Kode
HTML Structure: Struktur HTML dasar berisi <head> untuk judul halaman dan <body> untuk konten halaman.
PHP Code: Di dalam tag <?php ... ?>, terdapat perintah echo "Hello World"; yang akan menampilkan teks "Hello World" pada halaman.

# Langkah 4: Mengakses File di Browser
Buka browser dan akses file tersebut dengan URL berikut:
http://localhost/lab7_php_dasar/php_dasar.php

# Hasil 
![Screenshot (241)](https://github.com/user-attachments/assets/0ec574f6-168e-4e85-88df-59c6ceb7e9e3)
