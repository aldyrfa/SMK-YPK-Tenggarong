# LANGKAH-LANGKAH PEMBUATAN APLIKASI SMK YPK TENGGARONG MENGGUNAKAN LARAVEL #

### Aplikasi CRUD : Data Siswa & Data Kelas ###


<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Download & Instalasi Laravel

Disini saya akan menjelaskan cara melakukan instalasi laravel "menggunakan composser"

1. Yang harus anda siapkan yaitu :

- [Download XAMPP Versi Terbaru](https://www.apachefriends.org/download.html).
- [Download Composser](https://getcomposer.org/Composer-Setup.exe).
- [Template AdminLTE 2.3.11](https://codeload.github.com/almasaeed2010/AdminLTE/zip/v2.3.11).

2. Setelah instalasi XAMPP dan Composer selesai, buka folder htdocs disini saya menyimpannya di (C:\xampp\htdocs),<br> 
kemudian klik kanan pada sembarang tempat di dalam folder htdocs tersebut<br> 
Pilih : Open command windows here untuk membuka command prompt pada folder htdocs.<br>
Pastikan laptop anda terhubung ke internet.<br>
Ketik command berikut : composer create-project --prefer-dist laravel/laravel belajarLaravel "5.7.*"<br>
**Note: belajarLaravel adalah nama folder untuk menyimpan package-package laravel yang akan didownload.**
Composer akan otomatis mendownload laravel  dan akan disimpan di folder belajarLaravel


## Membuat CRUD dengan menggunakan Template AdminLTE

Untuk proses pembuatan Aplikasi ini, anda dapat mengikuti Tutorial yang diberikan oleh **Bapak Ferry Stephanus Suwita, S.Kom**, yaitu sebagai berikut :

- **[Tutorial Laravel 5.7 - Integrate AdminLTE & Make Simple CRUD](https://drive.google.com/file/d/1AmexPu9OEQEz1cHfvVOHHIx3-47ml-Jm/view?usp=sharing)**
- **[Tutorial Laravel - Eloquent Relationship](https://drive.google.com/file/d/1WpHAgdv4zVrgA-nV1u64Mbl31C65LyVC/view?usp=sharing)**
- **[Tutorial Laravel – Login](https://drive.google.com/file/d/1wLjs3QIaYI3o9mIikLBJOluA_7QTm6rQ/view?usp=sharing)**
- **[Tutorial Laravel - Upload File](https://drive.google.com/file/d/1-qb34ta4QJFzmekmiUAK84CzW6Cy7IXR/view?usp=sharing)**

## Cara Push Folder lokal ke Github menggunakan Git

- [Download Git](https://git-scm.com/).
- [Buat akun Github anda](https://github.com/).
- Buat repositories pada akun yang telah anda buat

Setelah proses instalasi selesai klik kanan pada folder yang akan di push ke github (disini saya coba untuk push folder belajarLaravel) kemudian pilih Git Bash Here

**1. Lakukan konfigurasi :** <br>
git config --global user.name "masukkan username github anda" [enter] <br>
git config --global user.email "masukkan email github anda" [enter] <br>

**2. Inisialisasi direktori local sebagai Repository Git.**<br>
git init [enter]

**3. Menambahkan semua isi dari project yang telah dibuat (belajarLaravel).**<br>
git add .

**4. git commit -m "isi", digunakan sebagai penanda jika ada file yang baru di ubah, contohnya** <br>
git commit -m "first commit"

**5. Menambahkan remote didalam repository lokal** <br>
git remote add origin remote repository URL [enter] <br>
Note: remote repository URL didapatkan di repository kita, <br>
dibagian Clone or download maka akan muncul alamat url kemudian copy-paste ke git.

**6. Push dari lokal ke github** <br>
git push origin master --force [enter]



