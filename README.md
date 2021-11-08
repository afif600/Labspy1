# Labspy1

## Lab 2: Struktur Kondisi
### Latihan 1
### Program dan Output
### Program sederhana dengan input 2 buah bilangan serta menentukan bilangan terbesar dari kedua bilangan
<li> Program Menentukan Bilangan Terbesar Dari 2 Buah Bilangan </li>

```bash
print("Program Menentukan Bilangan Terbesar")
print("------------------------------------")

a = int(input("Masukan nilai a: "))
b = int(input("Masukan nilai b: "))

if a > b:
    maks = a
else:
    maks = b
print('Nilai Terbesar adalah %d' % maks)
```

![gambar 1](screenshot/lab2lat1_1.png

<li> Output </li>

![gambar 2](screenshot/lab2lat1_2.png

### Latihan 2
### Program dan Output
### Program mengurutkan data berdasarkan input jumlah data serta menentukan urutan dari data terkecil
<li> Program Mengurutkan Data Berdasarkan Input Jumlah Data Serta Menentukan Urutan Dari Data Terkecil </li>

```bash
print("Program mengurutkan data")
print("------------------------")
angka = []
def mengurut(angka):
   a = int(input("Bilangan ke-1:"))
   angka.append(a)
   b = int(input("Bilangan ke-2:"))
   angka.append(b)
   c = int(input("Bilangan ke-3:"))
   angka.append(c)
   tukar = True
   while tukar:
       tukar=False
       for n in range(len(angka)-1):
           if angka[n] > angka[n+1]:
               angka[n], angka[n+1] = angka[n+1], angka[n]
               tukar = True
   return angka
print("Urutan Bilangan:",mengurut(angka))
```

![gambar 3](screenshot/lab2lat2_1.png

<li> Output </li>

![gambar 4](screenshot/lab2lat2_2.png

## Lab 3: Perulangan
### Latihan 1
### Program dan Output
### Program Perulangan Bertingkat
<li> Program Perulangan Bertingkat </li>

```bash
#Program Perulangan
print("-------------------")

for i in range(0, 10):
    for j in range(10):
        print('%3d'%(i+j), end = ' ')
    print(' ')
```

![gambar 5](screenshot/lab3lat1_1.png

<li> Output </li>

![gambar 6](screenshot/lab3lat1_2.png

### Latihan 2
### Program dan Output
<li> Tampilkan n bilangan acak yang lebih kecil dari 0.5 </li>
<li> Nilai n di isi pada saat runtime </li>
<li> Anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya </li>
<li> Program Bilangan Acak Dari 0.5 </li>

```bash
from random import random
n = int(input("Masukan Nilai N: "))
for i in range(n):
    while 1:
        n = random()
        if n < 0.5:
            break
    print(n)
```

![gambar 7](screenshot/lab3lat2_1.png

<li> Output </li>

![gambar 8](screenshot/lab3lat2_2.png

### Sekian Terima Kasih