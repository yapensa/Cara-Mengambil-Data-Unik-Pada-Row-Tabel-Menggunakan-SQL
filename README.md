# Cara-Mengambil-Data-Unik-Pada-Row-Tabel-Menggunakan-SQL
Cara Mengambil Data Unik Pada Row Tabel Menggunakan SQL

# Studi Kasus
Misalnya kita ingin mengambil isi kolom "status" dari tabel "order", karena datanya jutaan row kita tidak tahu isi kolom "status" itu apa aja isinya... maka dari itu kita perlu data apa saja tanpa adanya duplikasi....

# Data
link data: https://www.mysqltutorial.org/wp-content/uploads/2018/03/mysqlsampledatabase.zip

![image](https://user-images.githubusercontent.com/8088664/229361954-6dd5cf66-081f-4cde-855a-f209c1525d14.png)

# Struktur Tabel

![image](https://user-images.githubusercontent.com/8088664/229361923-486d6237-f335-45d7-9f24-22a2dc3eef64.png)

# Menampilkan isi kolom status

MariaDB [classicmodels]> 

SELECT status FROM orders;


+------------+
| status     |
+------------+
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Resolved   |
| Shipped    |
| Shipped    |
| Cancelled  |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Cancelled  |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Cancelled  |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Cancelled  |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Cancelled  |
| Shipped    |
| Cancelled  |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Resolved   |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| On Hold    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Resolved   |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Resolved   |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| On Hold    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Disputed   |
| On Hold    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| Shipped    |
| On Hold    |
| Disputed   |
| Shipped    |
| Disputed   |
| Shipped    |
| Shipped    |
| In Process |
| In Process |
| In Process |
| In Process |
| In Process |
| In Process |
+------------+
326 rows in set (0.000 sec)

# Code SQL SELECT DISTINCT
SELECT DISTINCT status FROM orders;

Hasi:

![image](https://user-images.githubusercontent.com/8088664/229362104-e17669b2-d25d-4fb1-8974-868d0484dd01.png)

# Penjelasan Code
Perintah SQL SELECT DISTINCT status FROM orders; digunakan untuk mengambil data dari tabel orders dan menampilkan nilai unik dari kolom status. Dalam hal ini:

- SELECT DISTINCT digunakan untuk memilih nilai unik dari kolom yang diambil.
- status adalah nama kolom yang akan ditampilkan nilai uniknya.
- FROM orders menunjukkan bahwa data akan diambil dari tabel orders.

Jadi, perintah SQL ini akan mengambil semua nilai yang terdapat pada kolom status di tabel orders, kemudian menampilkan hanya nilai unik (tidak ada duplikasi) dari kolom tersebut. Hasilnya adalah daftar nilai unik yang ada di kolom status pada tabel orders.

