# Pertemuan 05 Perulangan Python
Nama: Rahma Aliya
NIM: 2225250103
Kelas: 3F
## Tujuan
Menggunakan for dan while untuk menyelesaikan masalah iteratif.
## Cara Menjalankan
Program dijalankan menggunakan Python melalui terminal VS Code.

Untuk menjalankan Kuis 2, gunakan perintah:

python kuis/kuis2_deret_aritmetika.py
## Algoritma Kuis 2
1. Memasukkan nilai suku pertama (a).
2. Memasukkan nilai beda (d).
3. Memasukkan banyak suku (n).
4. Memeriksa apakah nilai n merupakan bilangan bulat positif.
5. Jika n kurang dari atau sama dengan 0, pengguna diminta memasukkan kembali nilai n.
6. Menggunakan perulangan for untuk menghitung setiap suku deret aritmetika.
7. Menjumlahkan seluruh suku yang telah dihitung.
8. Menampilkan setiap suku dan jumlah seluruh deret.
## Hasil Pengujian
### Pengujian 1

Input:
a = 2
d = 3
n = 5

Output:
Suku ke-1: 2.00
Suku ke-2: 5.00
Suku ke-3: 8.00
Suku ke-4: 11.00
Suku ke-5: 14.00
Jumlah = 40.00

Status: Berhasil

### Pengujian 2

Input:
a = 10
d = -2
n = 4

Output:
Suku ke-1: 10.00
Suku ke-2: 8.00
Suku ke-3: 6.00
Suku ke-4: 4.00
Jumlah = 28.00

Status: Berhasil

### Pengujian 3

Input:
a = 1.5
d = 0.5
n = 3

Output:
Suku ke-1: 1.50
Suku ke-2: 2.00
Suku ke-3: 2.50
Jumlah = 6.00

Status: Berhasil

## Refleksi
Kesalahan yang ditemukan adalah ketika nilai n dimasukkan kurang dari atau sama dengan 0. Untuk mengatasinya, digunakan perulangan while sehingga program meminta pengguna memasukkan kembali nilai n sampai mendapatkan bilangan bulat positif.