# praktikum-9

Exception Handing

```
- Exception Adalah suatu kesalahan atau error yang terjadi saat proses eksekusi perogram yang sedang berjalan;
- Kesalahan ini Biasanya disebabkan Karena Salah satu Programnya ada Masalah atau tidak terdetek.
```

Assertion

```
- Assertion(Pernyataan) merupakan kewajaran suatu proram yang kamu bisa aktif atau nonaktif ketika kamu selesai menjalankan sebuah program
```

Assert Expression (Arguments)

```
- Jika pernyataan gagal, Python menggunakan ArgumentExpression ArgumentExpression sebagai argumen argumen untuk AssertionError AssertionError. Pengecualian AssertionError Pengecualian AssertionError dapat ditangkap dan ditangani ditangani seperti pengecualian lainnya menggunakan try- kecuali pernyataan, tetapi jika dibiarkan, mereka akan menghentikan program dan menghasilkan backtrace.
```

Contoh kode di bawah menghasilkan hasil sebagai berikut:
![image](https://user-images.githubusercontent.com/115526901/208331534-14a5e0df-0cdb-4647-b130-4dd8144ab509.png)

Menangani Pengecualian

```
Jika Anda memiliki beberapa kode mencurigakan yang mungkin mengeluarkan pengecualian, Anda dapat mempertahankan program Anda letakkan kode yang mencurigakan di *try: blok. Setelah coba: blok, sertakan pernyataan sertakan *except: statemen, diikuti oleh blok kode yang menangani masalah seanggun mungkin.
```

Contoh kode di bawah menghasilkan hasil sebagai berikut:
![image](https://user-images.githubusercontent.com/115526901/208331796-a5f7fef4-38da-41af-95c2-3459f14094fd.png)

![image](https://user-images.githubusercontent.com/115526901/208331947-920d6430-6946-4ce6-8499-5be6023fdeb2.png)

Fasal Kecuali tanpa pengecualian

```
- Anda juga dapat menggunakan pernyataan exception tanpa exception yang didefinisikan sebagai berikut:
try: You do your operations here; ...................... except: If there is any exception, then execute this block. ...................... else: If there is no exception then execute this block.

Pernyataan coba-kecuali jenis ini menangkap semua pengecualian pengecualian yang terjadi. Menggunakan percobaan seperti try-expect pernyataan tidak dianggap sebagai praktik pemrograman yang baik, karena mereka menangkap semuanya pengecualian tetapi tidak membuat programmer mengidentifikasi kemungkinan penyebab masalah terjadi.
```

Klausa kecuali dengan berbagai pengecualian

```
- Anda juga dapat menggunakan pernyataan exception yang sama untuk menangani beberapa exception sebagai berikut:
try: You do your operations here; ...................... except(Exception1[, Exception2[,...ExceptionN]]]): If there is any exception from the given exception list, then execute this block. ...................... else: If there is no exception then execute this block.
```

klausa coba-akhirnya

contoh:
- Jika Anda memiliki izin untuk membuat file dalam mode tulis yang dapat ditulis, maka ini akan menghasilkan hasil berikut:
![image](https://user-images.githubusercontent.com/115526901/208332770-ba3dbd0a-04bd-4bfb-96b1-163543956e25.png)

- Contoh yang sama dapat ditulis lebih bersih sebagai berikut:
![image](https://user-images.githubusercontent.com/115526901/208332873-2f31f99a-ab06-4b7d-8e27-a28c7f3d4957.png)

Ketika exception dilempar ke dalam blok try, eksekusi segera dilanjutkan ke akhir memblok. Setelah semua pernyataan di blok akhirnya dieksekusi, pengecualian dimunculkan lagi dan ditangani dalam pernyataan kecuali jika ada di lapisan berikutnya yang lebih tinggi dari percobaan-kecuali penyataan.

Argumen Pengecualian

- berikut adalah contoh untuk satu pengecualian:
![image](https://user-images.githubusercontent.com/115526901/208333186-fff332f9-7a41-430d-9811-b791c2f25e60.png)


Melempar Pengecualian 

- Pengecualian dapat berupa string, kelas, atau objek. Sebagian besar pengecualian adalah pengecualian dari inti Python menimbulkan adalah kelas, dengan argumen=argumen yang merupakan turunan dari kelas. Mendefinisikan pengecualian barucukup mudah dan dapat dilakukan sebagai berikut:
![image](https://user-images.githubusercontent.com/115526901/208333332-4218b25f-7dfb-48a6-97aa-dde8b81dcd2e.png)


Pengecualian yang ditetapkan pengguna

- Python juga memungkinkan Anda membuat pengecualian sendiri dengan menurunkan kelas-kelas dari yang standar pengecualian bawaan;
- Berikut adalah contoh-contoh yang terkait dengan RuntimeError. Di sini, kelas dibuat yang merupakan subkelas dari subkelas RuntimeError. Ini berguna saat Anda perlumenampilkan tampilan informasi yang lebih spesifik saat e pengecualian tertangkap;
- Di blok coba, pengecualian yang ditentukan pengguna dimunculkan dan ditangkap di blok kecuali. Itu variabel e digunakan untuk membuat instance dari kelas Networkerror.

![image](https://user-images.githubusercontent.com/115526901/208333914-7a84ad24-f176-4aa8-865b-218676312e97.png)










