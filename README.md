# Function-FPB-KPK
1.	Fungsi hitung_fpb(a, b)
•	Mengambil dua argumen bilangan bulat a dan b.
•	Mengembalikan nilai FPB dari a dan b.
•	Fungsi ini menggunakan algoritma Euclidean yang merupakan algoritma rekursif untuk menghitung FPB.
•	Jika b sama dengan 0, maka fungsi mengembalikan nilai a, jika tidak, fungsi memanggil dirinya sendiri dengan argumen b dan a % b.

2.	Fungsi hitung_kpk(a, b)
•	Mengambil dua argumen bilangan bulat a dan b.
•	Mengembalikan nilai KPK dari a dan b.
•	Fungsi ini menggunakan perulangan while untuk mencari nilai KPK dengan mengiterasi nilai kpk dari nilai maksimum antara a dan b.
•	Jika kpk dapat dibagi habis oleh a dan b, maka fungsi mengembalikan nilai kpk, jika tidak, nilai kpk ditambah 1.

3.	Perulangan while
•	Program memiliki perulangan while yang akan terus berjalan sampai pengguna memilih opsi 3 untuk keluar dari program.
•	Saat perulangan dijalankan, program akan menampilkan tiga pilihan, yaitu menghitung FPB, menghitung KPK, atau keluar dari program.
•	Pengguna diminta untuk memilih salah satu pilihan dengan memasukkan angka sesuai dengan pilihan.
•	Jika pengguna memilih pilihan 1 atau 2, program akan meminta pengguna memasukkan dua bilangan dan kemudian memanggil fungsi yang sesuai untuk menghitung nilai FPB atau KPK. Hasil perhitungan akan ditampilkan ke pengguna.
•	Jika pengguna memilih pilihan 3, program akan menampilkan pesan terima kasih dan keluar dari perulangan while.
•	Jika pengguna memilih pilihan selain 1, 2, atau 3, program akan menampilkan pesan bahwa pilihan tidak valid dan meminta pengguna memilih lagi.

