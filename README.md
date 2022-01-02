# mysql-periodic-backup
Membuat backup data MySQL secara periodik dan mengirimkan hasil backup via Email

Ini adalah script cron jobs dan script PHP untuk melakukan backup file database, dan hasil backup tersebut dikirim ke alamat email tertentu. Perlu diperhatikan bahwa script-script ini digunakan untuk Anda yang menempatkan data di shared hosting melalui cPanel. Untuk yang tidak melalui cPanel, silakan disesuaikan.

Ada 2 script cron dan 1 script php. Pastikan semua parameternya disesuaikan dengan punya Anda. Pastikan pula script untuk membuat backup filenya dilakukan lebih dulu sebelum script untuk kirim email.

Script php yang digunakan untuk kirim email menggunakan library PHPMailer, silakan download sendiri.

Disclaimer:
Segala akibat dari pemakaian script ini, diluar tanggungjawab kami.
