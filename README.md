# Praktikum 9 
## Exception and Handling
#### Contoh Assert Statement
- Ketika kode di atas dijalankan, menghasilkan hasil sebagai berikut:
![gambar](gambar/9.1.png)
- Jika pernyataan gagal, Python menggunakan ArgumentExpression ArgumentExpression sebagai argumen argumen untuk AssertionError AssertionError. Pengecualian AssertionError Pengecualian AssertionError dapat ditangkap dan ditangani ditangani seperti pengecualian lainnya menggunakan try- kecuali pernyataan, tetapi jika dibiarkan, mereka akan menghentikan program dan menghasilkan backtrace.
#### ContohHandling an Exception
- Contoh-contoh ini membuka file, menulis konten file, dan keluar dengan aman karena ada tidak masalah
- Ketika kode di atas dijalankan, menghasilkan hasil sebagai berikut:
![gambar](gambar/9.2.png)
- Contoh ini mencoba membuka file yang Anda tidak memiliki izin menulis, sehingga membuat file pengecualian
- Ketika kode di atas dijalankan, menghasilkan hasil sebagai berikut:
![gambar](gambar/9.3.png)
#### Contoh The try-finally Clause
- Ketika exception dilempar ke dalam blok try, eksekusi segera dilanjutkan ke akhir memblok. Setelah semua pernyataan di blok akhirnya dieksekusi, pengecualian dimunculkan lagi dan ditangani dalam pernyataan kecuali jika ada di lapisan berikutnya yang lebih tinggi dari percobaan-kecuali penyataan.
- Ketika kode di atas dijalankan, menghasilkan hasil sebagai berikut:
- Jika Anda tidak memiliki izin untuk membuka file dalam mode tulis yang dapat ditulis, maka ini akan menghasilkan hasil berikut:
![gambar](gambar/9.4.1.png)
- Contoh yang sama dapat ditulis lebih bersih sebagai berikut:
![gambar](gambar/9.5.png)
#### Contoh Argument of an Exception
- Berikut adalah contoh untuk satu pengecualian
- Ketika kode di atas dijalankan, menghasilkan hasil sebagai berikut:
![gambar](gambar/9.6.png)
#### Contoh Raising an Exception
