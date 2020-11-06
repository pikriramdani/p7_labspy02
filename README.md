# p7_labspy02
repository ini di buat untuk memenuhi tugas pada pertemuan 7 bahasa pemrograman (modul praktikum 2)<br><br>
Nama : PIKRI RAMDANI<br>
NIM  : 312010162<br>
Kelas: TI.20 A.1<br><br>
<hr>


### Menentukan Bilangan Terbesar dari 3 nilai yang diinputkan

<br>
Pada Pertemuan ke-7 ini saya mendapat tugas dari Dosen Bahasa Pemrograman Teknik Informatika - Universitas Pelitas Bangsa yaitu Bapak. Agung Nugroho,S.Kom.,M.Kom. untuk membuat Aplikasi yang menentukan Bilangan terbesar dari tiga nilai client/user inputkan menggunakan Bahasa Pemrograman Python.<br><br>


Pada repository ini saya akan menjelaskan alur dalam *Flowchart* yang telah saya buat. File *Flowchart* bisa dilihat pada Link berikut ini : [Flowchart P7 Menentukan Bilangan Terbesar Dari 3 Nilai Yang diinputkan](flowchart-p7-pikri-ramdani-312010162.pdf)
<br><br>
Berikut source code yang saya tulis untuk menjadikan aplikasi tersebut. 

``` python
print("Masukan Angka ke-1 : ")
angka1=int(input())
print("Masukan Angka ke-2 : ")
angka2=int(input())
print("Masukan Angka ke-3 : ")
angka3=int(input())

print("\n")

if (angka1 > angka2) and (angka1 > angka3) :
    print(f"Bilangan Pertama Lebih Besar Dari Bilangan Kedua dan Ketiga ")

elif (angka2 > angka1) and (angka2 > angka3) :
    print(f"Bilangan Kedua Lebih Besar Dari Bilangan Pertama dan Ketiga ")

elif (angka3 > angka1) and (angka3 > angka2) :
    print("Bilangan ketiga Lebih Besar dari Bilangan Pertama dan Kedua ")

else:
    print(f"Semua Bilangan Sama Besar")
```
 
  
