Cara menjalankan Aplikasi : 
- Simpan Project di /htdocs (kalau pake xampp)
- import database (crowdfunding.sql)
- buka folder project, copykan .env.example, menjadi .env
- isi DB_DATABASE, DB_USERNAME, DB_PASSWORD, sesuaikan dengan settingan database kamu
- di dalam directory project buka terminal, ketikan "php artisan key:generate"
- di dalam directory project buka terminal, ketikan "php artisan serve"
- buka browser, ketikan url "localhost:8000"

	Cara membuat akun baru: 
	Akun User:
		- Pilih menu daftar di nav-bar
		- Isi data seperti biasa
	Akun Admin:
		- Pilih menu daftar di nav-bar
		- Isi data seperti biasa
		- Di database, di tabel user ada field "role", valuenya ubah jadi 1


















