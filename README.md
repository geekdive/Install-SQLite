# Install-SQLite
Cara Menginstall SQLite di Ubuntu 16.04.03 LTS

Pertama Install dulu paket SQLitenya dengan mengetik command seperti berikut:
## apt -y install sqlite3 libsqlite3-dev

Jika sudah selesai kemudian akses SQLite dengan 
## sqlite3 > tekan Enter
root@x:/home/rpl# sqlite3 
SQLite version 3.11.0 2016-02-15 17:29:24
Enter ".help" for usage hints.
Connected to a transient in-memory database.
Use ".open FILENAME" to reopen on a persistent database.
sqlite>

Untuk keluar dari program
## sqlite> .quit
root@x:/home/rpl# 

