# UAS_SistemTerdistribusi
# Chatting App UAS Sistem Terdistribusi
Deskripsi : Aplikasi chatting menggunakan arsitektur rest API yang dijalankan menggunakan framework django
Cara Pakai : download aplikasi, pastikan anda mempunyai django framework yang dapat diinstal dengan menggunakan pip install django di cmd, dan python juga terinstall.
sebelum memulai install requirements di powershell dengan memasukkan command "pip install -r requirements.txt"
Untuk menjalankan aplikasi, di cmd ketik : python manage.py runserver 0.0.0.0:8000
8000 merupakan  port, dan 0.0.0.0 untuk dapat dijalankan secara local network.
Credential Admin adalah :
Username : Admin
Password : Password123
untuk user, dapat dibuat credential terlebih dahulu lewat register.
Untuk memulai chat, pilih user yang ada di interface, dan mulailah mengetik.

database yang digunakan adalah : sqlite.
Untuk mengatur credential dapat diakses dengan url : 127.0.0.1/admin/
Setelah server telah di run, client dapat mengakses aplikasi dengan memasukkan IP address dan port
contoh : 192.168.0.8:8000, di mana port yang dipakai adalah port 8000, dan IP address contohnya adalah 192.168.0.8
atau 127.0.0.1:8000
