#Praktikum10

# Apa Itu Python String?

*  String adalah jenis yang paling populer di Python.
* Membuat string semudah memberi nilai pada sebuah variabel.
* Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.
* Python memperlakukan tanda kutip tunggal (' ') sama dengan tanda kutip ganda (" ").

# Latihan 1
' txt = 'Hello World' '
- Hitung jumlah karakternya
- Ambil karakter terakhir
- Ambil karakter index ke-2 sampai index ke-4 (llo)
- Hilangkan spasi pada text tersebut (HelloWorld)
- Ubah text menjadi huruf besar
- Ubah text menjadi huruf kecil
- Ganti karakter H dengan karakter J

# Source Code latihan 1
![img.1](gambar/latihan1%20code.png)

# Penjelasan Latihan 1
1. Untuk menghitung jumlah karakter, gunakan fungsi ' len() '.
2. Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku ' [ ] ' dan deklarasi nomor di dalam kurung siku dengan urutan Array dan menggunakan titik dua lalu masukan nomor Array selanjutnya.
3. gunakan index [-1], Untuk mengambil karakter terakhir. Sedangkan untuk mengambil karakter index ke-2 sampai ke-4, gunakan index [2:5].
4. gunakan method ' replace() ', untuk menghilangkan spasi pada string. Method replace() mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculan.
5. Di dalam method replace, kita dapat menggunakan 2 cara, yang pertama bisa menggunakan ' (txt.replace(" ", "")) ' dan kedua dengan cara ' (txt.replace(txt[5], "")) '.
6. Untuk mengganti karakter ' 'H' ' dengan karakter ' 'J' ', gunakan method ' replace() '.

# Output Latihan 1
![img.2](gambar/hsl%20latihan%201.png)

# Latihan 2
- Lengkapi kode berikut:
' umur = 24
 txt = 'Hello, nama saya john, dan umur saya adalah ... tahun'
 print(txt.format(umur)) '

# Source Code Latihan 2
![img.3](gambar/latihan%202%20code.png)

# Penjelasan Latihan 2
Untuk memasukkan variable ke dalam string, tambahkan kurung kurawal ' {} ' untuk menempatkan variable sebelumnya.

# OUtput Latihan 2
![img.4](gambar/hsl%20latihan%202.png)