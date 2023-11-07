# PraktikumPEMIN-A_Tugas8
1. Pastikan terdapat tabel users yang dibuat menggunakan migration pada bab 󾠰
Basic Routing dan Migration . Berikut informasi kolom yang harus ada
2. Pastikan terdapat model User.php yang digunakan pada bab 󾠲 Model, Controller
dan Request-Response Handler. Berikut baris kode yang harus ada![Screenshot 2023-11-07 200730](https://github.com/askenas/PraktikumPEMIN-A_Tugas8/assets/134838656/52008781-d37f-4273-a5ad-5dfb6d5ca8ae)
3. Buatlah file AuthController.php dan isilah dengan baris kode berikut
4.Tambahkan baris berikut pada routes/web.php
   ![Screenshot 2023-11-07 200931](https://github.com/askenas/PraktikumPEMIN-A_Tugas8/assets/134838656/621bfc17-4c4d-41e5-8c2a-a73ed48c1621)

# Authentication
1. Buatlah fungsi login(Request $request) pada file AuthController.php
   ![Screenshot 2023-11-07 201456](https://github.com/askenas/PraktikumPEMIN-A_Tugas8/assets/134838656/8d26af62-93e7-4341-8735-75453d679c3c)
2. Tambahkan baris berikut pada routes/web.php
   ![Screenshot 2023-11-07 201557](https://github.com/askenas/PraktikumPEMIN-A_Tugas8/assets/134838656/4efe6b86-a843-405a-8535-ee925fe9a8e7)
# Token
1. Jalankan perintah berikut untuk membuat migrasi baru
   php artisan make:migration add_column_token_to_users
2. Tambahkan baris berikut pada migration yang baru terbuat
   ![Screenshot 2023-11-07 201833](https://github.com/askenas/PraktikumPEMIN-A_Tugas8/assets/134838656/c16a3492-56ee-4ec3-b736-d6ad2bb2b3cc)
3. Tambahkan atribut token di $fillable pada User.php
   ![Screenshot 2023-11-07 201905](https://github.com/askenas/PraktikumPEMIN-A_Tugas8/assets/134838656/e655a939-2b14-4152-a91e-d0ca35c169a1)
4. Tambahkan baris berikut pada file AuthController.php
   ![Screenshot 2023-11-07 202116](https://github.com/askenas/PraktikumPEMIN-A_Tugas8/assets/134838656/a48617ec-b5d2-4a40-a381-b717a81e160f)

