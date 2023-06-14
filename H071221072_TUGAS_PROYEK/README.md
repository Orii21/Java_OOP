## Getting Started 
Program saya adalah contoh implementasi CRUD (Create, Read, Update, Delete) sederhana menggunakan Java dan database MySQL. Ini adalah aplikasi sederhana untuk mengelola data produk, di mana pengguna dapat menambahkan, membaca, memperbarui, dan menghapus data produk.

Berikut adalah penjelasan singkat tentang setiap kelas dalam program tersebut:

MyConfig: Kelas ini berisi konfigurasi untuk menghubungkan aplikasi ke database MySQL. Berisi URL database, username, dan password.

DbController: Kelas ini merupakan kelas induk yang mengatur koneksi ke database dan menyediakan metode untuk melakukan operasi CRUD. Metode-metode ini termasuk mendapatkan data produk, mencari produk berdasarkan nama, menyisipkan data produk baru, memperbarui data produk, dan menghapus data produk.

Delete: Kelas ini menangani logika untuk menghapus data produk. Menampilkan daftar produk yang ada di database dan meminta pengguna untuk memilih produk yang ingin dihapus.

Edit: Kelas ini menangani logika untuk mengedit data produk. Menampilkan daftar produk yang ada di database dan meminta pengguna untuk memilih produk yang ingin diedit. Setelah itu, pengguna dapat memilih atribut mana yang ingin diubah (nama, harga, atau jumlah) dan memasukkan nilai baru untuk atribut tersebut.

Insert: Kelas ini menangani logika untuk menambahkan data produk baru. Meminta pengguna untuk memasukkan nama, harga, dan jumlah produk baru yang akan ditambahkan ke database.

Menu: Kelas ini menampilkan menu utama aplikasi dan meminta pengguna untuk memilih opsi. Opsi termasuk membaca data produk, menambahkan data produk baru, mengedit data produk, menghapus data produk, dan keluar dari aplikasi.

Read: Kelas ini menampilkan data produk yang ada di database.

Produk: Kelas ini adalah model untuk objek Produk. Ini memiliki atribut seperti id, nama, harga, dan jumlah, serta metode-metode setter dan getter untuk atribut tersebut.

App: Kelas ini adalah kelas utama yang menjalankan aplikasi. Ini memanggil metode showMenu() dari kelas Menu untuk memulai aplikasi.

Program di atas menggunakan JDBC (Java Database Connectivity) untuk berinteraksi dengan database MySQL. Program ini terdiri dari beberapa kelas yang bekerja sama untuk mengelola data produk. Pengguna dapat memilih opsi melalui menu untuk melakukan operasi CRUD yang sesuai pada data produk.

Harap dicatat bahwa program di atas hanya contoh sederhana dan tidak termasuk perlindungan keamanan atau penanganan kesalahan yang lengkap. Dalam pengembangan aplikasi yang sebenarnya, Anda perlu mempertimbangkan aspek keamanan, validasi input, penanganan kesalahan, dan lainnya.
