Cara instalasi web crud:
1.	Copy semua folder ke C:/xampp/htdocs
2.	Buka command line (start + R, ketik “cmd”) untuk Windows, buka terminal untuk linux
3.	Masuk ke direktori web crudmulia. Contoh : “cd C:\xampp\htdocs\crudmulia”
 
4.	Jalankan “php artisan config:cache” dan “composer dump-autoload”
5.	Selesai

Cara instalasi API:
1.	Sama seperti web crud, hanya beda nama foldernya saja.	

Cara menjalankan migrate dan seeding database:
1.	Pertama harus buat database dulu bernama “db_mulia” di phpmyadmin (buka localhost/phpmyadmin, di sebelah kiri klik “New” lalu Create database “db_mulia”)
 
2.	Buka command line (start + R, ketik cmd) untuk Windows, buka terminal untuk linux
3.	Masuk ke direktori web crudmulia ATAU apimulia. Contoh : “cd C:\xampp\htdocs\crudmulia”
 
4.	Jalankan “php artisan migrate”
5.	Jalankan “php artisan db:seed”

Lalu akan masuk pada halaman Login
Masukkan Email dan Password sebagai berikut
Email : admin@mulia.com
Password : mulia123
