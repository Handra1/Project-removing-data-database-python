# Project-removing-data-database-python
This project about removing data from database in python(In Indonesia)

Removing Data From Database:
- Menggunakan perintah delete()
- Perintah delete () akan mengambil tabel yang memuat data sebagai argumen.
- Klausa where () digunakan untuk memilih baris mana yang akan dihapus.
- Harap berhati-hati dalam menghapus data.

Deleting Specific Rows:
Untuk menghapus baris secara spesifik kita dapat menggunakan klausa where(). Seperti contoh berikut dimana kita akan menghapus baris dengan kondisi dimana nilai kolom id = 3. Kita import fungsi delete dari SQLAlchemy terlebih dahulu
Deleting all Data from a Table:
Disini kita akan menghapus records dari tabel employees.
Variabel stmt akan menghitung total records dari kolom id yang berjumlah 2.
Sedangkan varibel delete_stmt menghapus 2 records dari tabel employees.
Dropping a Table:
Untuk menghapus tabel kita dapat menggunakan perintah drop(engine).
Dropping all the Tables:
Sedangkan untuk menghapus semua table kita dapat menggunakan perintah drop_all(engine) 
