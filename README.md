## 🚀 **Get Started**

1. Download & Install software-software yang diperlukan mulai dari
   - [XAMPP](https://www.apachefriends.org/download.html).
   - [Git Version Control](https://git-scm.com/downloads).
   - Dan code editor, kalau untuk saya menggunakan [Visual Studio Code](https://code.visualstudio.com/download).

2. Cek installasi
   - Untuk XAMPP, kalian dapat membuka softwarenya dan jalankan `start` pada `Apache` & `MySQL`. Lalu, buka web browser anda dan ketik.
     ```shell
     http://localhost
     ```
     Jika kalian masuk ke halaman **XAMPP** Apache + MariaDB + PHP + Perl, maka dapat dipastikan installasi kalian berjalan dengan lancar.
     
     Masuk ke folder htdocs pada xampp, contoh folder saya `C:\xampp\htdocs`. Lalu buat folder baru `pem-web2021` dan didalamnya terserah mau diberi apa. Untuk mengeceknya, masukkan file html `index.html` lalu masukkan kode
     ```html
     <!DOCTYPE html>
     <html lang="en">
         <head>
              <meta charset="UTF-8">
              <meta name="viewport" content="width=device-width, initial-scale=1.0">
              <meta http-equiv="X-UA-Compatible" content="ie=edge">
              <title>Hello World</title>
         </head>
         <body>
              <h2>Web minggu pertama.</h2>
         </body>
     </html>
     ```
     Lalu pada web browser ketik `http://localhost/pem-web2021/index.html`. Maka kalian akan membuka file html yang anda buat barusan.

   - Untuk Git, kalian bisa mengetikkan pada command prompt
     ```shell
     git --version
     ```
     Example output `git version 2.33.0.windows.2`

## 💻 **Create Github Repository**

1. Masuk ke website [Github](https://github.com/), lalu daftar / login.
2. Lalu buat repository baru tekan tombol hijau `New` dengan icon buku dikanan atas, beri nama `pem-web2021`
3. Kembali ke folder `pem-web2021` pada `htdocs`. buka `cmd` pada folder tersebut.
   > Ketik saja cmd di tab folder atas
4. Lalu ikuti saja instruksi yang tersedia pada git.

