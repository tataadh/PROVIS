# PROVIS

pada tugas prak 1 terdapat OOP dan Asynchronous.

OOP :
Pada baris ke 2 sampai 8 ada kelas 'Pedagang' yang memiliki Properti 'nama' dan 'menu'.
Konstruktor didefinisikan pada baris 10 sampai 12 untuk membuat objek 'Pedagang' dengan memberi nilai awal pada properti 'nama' dan 'menu'.
'tampilanMenu()' pada baris 15 sampai 22 digunakan untuk menampilkan menu pedagang dengan menggunakan perulangan untuk mencetak setiap item dalam menu.
kode utama berupa 'main()' menggunakan kelas 'Pedagang'.

Asynchronous :
Pada baris 26 sampai 30 mengguanakan method 'takeOrder()' untuk menerima pesanan. hal ini ditandai dengan kata kunci 'async' dan mengembalikan objek 'Future<void>', yang berarti method ini bersifat asynchronous dan tidak mengembalikan nilai.
Pada method 'takeOrder()' terdapat pemanggilan 'await future.delayed(Duration(seconds: 5))' ini mensimulasikan proses pembuatan makanan dan minuman dengan menunda eksekusi selama 5 detik.
Pada 'main()' menggunakan 'await' untuk menunggu hasil dari method 'takeorder()' sebelum melanjutkan ke langkah selanjutnya.
Dengan melakukan pesanan secara asynchronous, program dapat melanjutkan eksekusi tanpa harus menunggu proses pembuatan makanan selesai.
