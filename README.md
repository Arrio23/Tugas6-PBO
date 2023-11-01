# Tugas6-PBO
# Java GUI CRUD dan juga report

## Pengertian

### Java GUI 

GUI adalah tampilan yang didapat user ketika menjalankan atau menggunakan aplikasi

### CRUD adalah perintah umum dalam database yaitu Insert, Update, Delete, Select.

* Insert adalah perintah untuk menambahkan data baru kedalam database
* Update adalah perintah untuk memperbarui data yang sudah ada di dalam database
* Delete adalah perintah untuk menghapus data yang ada di dalam database
* Select adalah perintag untuk menampilkan data yang ada di dalam database

### Report

Report adalah laporan dari data yang ada pada database

## Tujuan

Sebagai bukti dari data yang ada pada database

## Langkah - langkah

* MEMBUAT CLASS MAHASISWA, YANG BERISI DATA DATA YANG AKAN DIGUNAKAN
* KEMUDIAN BUAT CLASS JAVA INTERFACE, BUAT DESAIN SESUAI KEBUTUHAN
* TAMBAHKAN DRIVER
* TAMBAHKAN KONEKSI. DIBAWAH MENU HELP ADA KONEKSI DATABASE. KLIK - NEW - DATABASE JDBC 	CONNECTION - NEXT -BERI NAMA KONEKSI - MASUKKAN USERNAME DAN PASSWORD -TEST (JIKA 	BERHASIL) - SAVE
* PADA CLASS INTERFACE, TAMBAHKAN JASPERREPORTS. YAITU PADA TOOLS - PLUGINS - DOWNLOAD - ADD 	JASPERREPORTS -INSTALL
* PADA LIBRARIES, KLIK KANAN ADD JAR FOLDER, MASUKKAN BEBERAPA KEBUTUHAN. JASPERREPORTS, 	COMMONS LOGGING, COMMONS DIGESTER, COMMONS COLLECTIONS, COMMONS BEANUTILS
* KLIK KANAN PADA PACKAGES, NEW - REPORT WIZARDS - PILIH DESAIN - NEXT - BERI NAMA FILE - 	PILIH CONNECTIONS - ISI QUERY DENGAN PERINTAH SELECT - NEXT - PILIH SEMUA FIELDS 
	- NEXT - FINISH
* PADA NAMA FILE.JRXML AKAN MUNCUL DESAIN, KEMUDIAN EDIT DESAIN
* SELESAI
