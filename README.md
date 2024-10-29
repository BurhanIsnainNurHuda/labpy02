# Laporan Praktikum 2

    Nama: Burhan Isnain Nur Huda
    NIM: 312410266
    Kelas: TI.24.A.2
    Mata Kuliah: Bahasa Pemograman 

# Kasus 1: Program Pemesanan Tiket Bioskop

Algoritma:

    1.Mulai
    2.Inisialisasi harga tiket reguler = 50000 dan VIP = 100000
    3.Input tipe tiket dari user
    4.Input status member dari user
    5.Jika tipe tiket = reguler, set harga = 50000
    6.Jika tipe tiket = VIP, set harga = 100000
    7.Jika status member = ya, hitung diskon 20%
    8.Tampilkan total harga
    9.Selesai
    
Flowchart:

![IMG_20241028_210413](https://github.com/user-attachments/assets/b9fa3e93-b1bb-4f9d-9186-a3cdab7e1538)

Program Python:   

![IMG_20241028_184813](https://github.com/user-attachments/assets/9bec1072-82a3-4011-b637-688448b246f4)


Hasil Eksekusi Program:

    1. Input Valid - Tiket Reguler dengan Member
![IMG_20241028_191602](https://github.com/user-attachments/assets/d162e7fa-bd5e-48f9-9a2c-5199811cf9a2)

Penjelasan:

    •Input: tipe tiket = reguler, status = ya
    •Harga awal: Rp50,000
    •Diskon 20%: Rp10,000
    •Total bayar: Rp40,000
•

    2. Input Valid - Tiket VIP tanpa Member
![IMG_20241028_192725](https://github.com/user-attachments/assets/879d1a93-b6f5-4129-b3fc-b80d4e1332cd)

Penjelasan:

    •Input: tipe tiket = vip, status = tidak
    •Harga awal: Rp100,000
    •Tidak ada diskon
    •Total bayar: Rp100,000
•

    3.Input Valid - Tiket VIP dengan Member
![IMG_20241028_193015](https://github.com/user-attachments/assets/b0dbc81c-402f-4508-9ced-5c3e7a02837a)

Penjelasan:

    •Input: tipe tiket = vip, status = ya
    •Harga awal: Rp100,000
    •Diskon 20%: Rp20,000
    •Total bayar: Rp80,000
•    
    
    4.Input Valid - Tiket Reguler tanpa Member
![IMG_20241028_193412](https://github.com/user-attachments/assets/ea652cd0-ed86-475a-988e-8e52663474d9)

Penjelasan:

    •Input: tipe tiket = reguler, status = tidak
    •Harga awal: Rp50,000
    •Tidak ada diskon
    •Total bayar: Rp50,000
•

    5.Input Tidak Valid - Tipe Tiket Salah
![IMG_20241028_193808](https://github.com/user-attachments/assets/033e8af0-cf7f-4ef4-a68b-fd8e67ec06f2)

Penjelasan:

    •Input tipe tiket tidak sesuai pilihan
    •Program menampilkan pesan error
    •Program berhenti
•

    6. Input Tidak Valid - Status Member Salah
![IMG_20241028_194039](https://github.com/user-attachments/assets/58a034c6-6b3c-40b6-9b50-b2036fc03850)

Penjelasan:

    •Input status member tidak sesuai
    •Program menganggap sebagai non-member
    •Harga normal tanpa diskon

 •  
  
     Tabel Ringkasan Input-Output:
![IMG_20241028_194348](https://github.com/user-attachments/assets/4db494b3-271f-4553-ad93-f1d8c16a75d2)


# Kasus 2: Program Kalkulator Sederhana

Algoritma:

    1. Start
    2. Input Angka Pertama
       •Tampilkan pesan: "Masukkan angka pertama:"
       •Simpan input sebagai `angka1`
    3. Input Angka Kedua
       •Tampilkan pesan: "Masukkan angka kedua:"
       •Simpan input pengguna sebagai `angka2`
    4. Input Operator
       •Tampilkan pesan: "Masukkan operator (+, -, *, /):"
       •Simpan input sebagai `operator`
    5. Proses Operasi
       •Jika `operator` adalah `+`:
         •Hitung `hasil = angka1 + angka2`
       •Jika `operator` adalah `-`:
         •Hitung `hasil = angka1 - angka2`
       •Jika `operator` adalah `*`:
         •Hitung `hasil = angka1 * angka2`
       •Jika operator adalah /:
         •Jika `angka2` tidak sama dengan 0:
           •Hitung `hasil = angka1 / angka2`
       •Jika `angka2` sama dengan 0:
         •Tampilkan pesan error: "Error: Pembagian dengan nol tidak diperbolehkan."
       •Jika `operator` tidak valid (bukan salah satu dari +, -, *, /):
         •Tampilkan pesan error: "Error: Operator tidak valid."
    6. Output Hasil
        •Jika operasi berhasil (tanpa error), tampilkan hasil: "Hasil: {hasil}"
    7. End
    
Penjelasan Algoritma:

    Langkah 1-4: Program mulai dengan meminta input dari pengguna untuk dua angka dan satu operator.
    Langkah 5: Melakukan operasi aritmatika berdasarkan operator yang dipilih. Program menggunakan struktur kontrol `if`, `elif`, dan `else` untuk menentukan operasi yang harus dilakukan.
    Langkah 6: Jika operasi berhasil, hasilnya ditampilkan. Jika ada kesalahan (seperti pembagian dengan nol atau operator tidak valid), program akan menampilkan pesan kesalahan yang sesuai.
    Langkah 7: Program selesai setelah menampilkan hasil atau pesan kesalahan.

Program Python:

![IMG_20241029_221708](https://github.com/user-attachments/assets/682656f3-3d21-43ef-8169-12afcb23cde2)


Hasil Eksekusi Program:   

    Contoh 1 Penjumlahan:   
    
![IMG_20241029_222159](https://github.com/user-attachments/assets/014d4327-cbc0-4966-9797-fc174369234f)

Penjelasan:

Input:

    Angka pertama yang dimasukkan adalah 10.
    Angka kedua yang dimasukkan adalah 5.
    Operator yang dipilih adalah + (penjumlahan).
    
Output:

    Hasil dari operasi 10 + 5 adalah 15.0. Program menampilkan hasil ini kepada pengguna.

. 

    Contoh 2 Pengurangan:

![IMG_20241029_222606](https://github.com/user-attachments/assets/f6b8d915-ae2c-40e8-9732-5db7602bc618)

Penjelasan:

Input:

    Angka pertama yang dimasukkan adalah 10.
    Angka kedua yang dimasukkan adalah 5.
    Operator yang dipilih adalah - (pengurangan).
    
Output:

    Hasil dari operasi 10 - 5 adalah 5.0. Program menampilkan hasil ini kepada pengguna.

•    

    Contoh 3 Perkalian:

![IMG_20241029_222938](https://github.com/user-attachments/assets/d29d0cfc-5434-4f7f-9d8a-73cfb6dfc50a)
    
Penjelasan:

Penjelasan:

Input:

    Angka pertama yang dimasukkan adalah 10.
    Angka kedua yang dimasukkan adalah 5.
    Operator yang dipilih adalah * (perkalian).

Output:

    Hasil dari operasi 10 * 5 adalah 50.0. Program menampilkan hasil ini kepada pengguna.
