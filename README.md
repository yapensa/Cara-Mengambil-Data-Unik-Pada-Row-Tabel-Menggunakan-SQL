# Cara-Mengambil-Data-Unik-Pada-Row-Tabel-Menggunakan-SQL
Cara Mengambil Data Unik Pada Row Tabel Menggunakan SQL

#Studi Kasus
Misalnya kita ingin mengambil isi dari kolom "status" dari tabel "order", karena datanya jutaan row kita tidak tahu isi kolom "status" itu apa aja isinya...

# Data
link data: https://www.mysqltutorial.org/wp-content/uploads/2018/03/mysqlsampledatabase.zip

# Struktur Tabel
+----------------+-------------+------+-----+---------+-------+
| Field          | Type        | Null | Key | Default | Extra | 
+----------------+-------------+------+-----+---------+-------+
| orderNumber    | int(11)     | NO   | PRI | NULL    |       |
| orderDate      | date        | NO   |     | NULL    |       |
| requiredDate   | date        | NO   |     | NULL    |       |
| shippedDate    | date        | YES  |     | NULL    |       |
| status         | varchar(15) | NO   |     | NULL    |       |
| comments       | text        | YES  |     | NULL    |       |
| customerNumber | int(11)     | NO   | MUL | NULL    |       |
+----------------+-------------+------+-----+---------+-------+
7 rows in set (0.008 sec)

# Code SQL
SELECT DISTINCT status FROM orders;

# Penjelasan Code
Perintah SQL SELECT DISTINCT status FROM orders; digunakan untuk mengambil data dari tabel orders dan menampilkan nilai unik dari kolom status. Dalam hal ini:

SELECT DISTINCT digunakan untuk memilih nilai unik dari kolom yang diambil.
status adalah nama kolom yang akan ditampilkan nilai uniknya.
FROM orders menunjukkan bahwa data akan diambil dari tabel orders.
Jadi, perintah SQL ini akan mengambil semua nilai yang terdapat pada kolom status di tabel orders, kemudian menampilkan hanya nilai unik (tidak ada duplikasi) dari kolom tersebut. Hasilnya adalah daftar nilai unik yang ada di kolom status pada tabel orders.
