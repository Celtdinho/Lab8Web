# Nama : Muhammad Hafiyainul Yakin Wahid
# NIM  : 312410164
# Kelas : TI.24.A1


```
Praktikum 8 – PHP dan Database MySQL

Repository ini berisi hasil praktikum membuat aplikasi CRUD (Create, Read, Update, Delete) sederhana menggunakan PHP dan MySQL.

📌 Struktur Folder
lab8_php_database/
│
├── index.php       # Menampilkan data barang (Read)
├── tambah.php      # Menambah barang baru (Create)
├── ubah.php        # Mengubah data barang (Update)
├── hapus.php       # Menghapus data barang (Delete)
├── koneksi.php     # Koneksi ke database MySQL
├── style.css       # CSS sederhana
└── gambar/         # Folder upload gambar

📌 Langkah Praktikum

Buat database baru di phpMyAdmin:

CREATE DATABASE latihan1;


Buat tabel data_barang:

CREATE TABLE data_barang (
  id_barang int(10) auto_increment PRIMARY KEY,
  kategori varchar(30),
  nama varchar(30),
  gambar varchar(100),
  harga_beli decimal(10,0),
  harga_jual decimal(10,0),
  stok int(4)
);


Import data contoh (opsional):

INSERT INTO data_barang (kategori, nama, gambar, harga_beli, harga_jual, stok)
VALUES 
('Elektronik', 'HP Samsung Android', 'hp_samsung.jpg', 2000000, 2400000, 5);


Letakkan folder lab8_php_database ke dalam:

htdocs (Windows)
atau
/opt/lampp/htdocs (Linux)


Akses aplikasi melalui browser:

http://localhost/lab8_php_database/

📌 Fitur Aplikasi

Menampilkan seluruh data barang

Menambahkan barang baru

Mengedit data barang

Menghapus barang

Upload gambar barang

Tampilan sederhana menggunakan CSS
