# Memberikan Kemudahan bagi ingin melakukan koneksi ke google storage tanpa ribet dan pussing mikirin konfigurasinya
silahkan yang butuh mengkonesikan ke google storage bisa memakai ini

## Requirment
 -!!! hanya untuk laravel versi 10 !!!, kalau versi coba aja dulu 🥑

# Pertama Buat Project laravelnya
## 1. Run composer create project laravel:
- seperti biasanya buat project laravel 10
```bash
composer create-project laravel/laravel <yYOUR NAME PROJECT>
```
## 2. buat Controller <terserah namamu> pakai yang diatas juga boleh :v 
- perintah unutk membuat project
```bash
php artisan make:controller <bebas namanya / pakai yang diata boleh>
```
## 3. jalankan libary composer ini 
- ini akan memduahkan kita terhubung dengan cloud storage
 ```bash
composer require league/flysystem-google-cloud-storage
``` 

## 4. copy codingan diatas semuanya ke controller ada 
- copy semua  yang ada didalam

## 4. setelah semua siap lanjutnya untuk mengubah kypath file sama bucketnya sesuai dengan nama bucketmu 
- $keyFile = {ALAMAT LENGKAP CREDENSIAL.JSON} // TOLONG UNTUK INI SETELA TUTRIAL BUAT BUCKET DI GOOGLE CLOUD
- $bucket = {GANTI DENGAN NAMA BUCKET}  // TOLONG UNTUK INI SETELA TUTRIAL BUAT BUCKET DI GOOGLE CLOUD

##Tutorial Untuk buat bucket Google Cloud Storage

