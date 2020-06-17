---
layout: post
category: tutorial
tagline: By Mimin
tags:
  - program
  - polinomial
  - pascal
  - jdoodle
published: true
---
{% include JB/setup %}

Sebelumnya mimin ucapkan terima kasih telah berkenan menggunakan program sederhana yang bernama **POLINOMIAL F(x)**.  

<br/>
<a href="jdoodle.com/a/28tA" class="btn btn-danger">Coba Program<span class="glyphicon glyphicon-eye-open" style="margin-left: 5px;"></span></a>
<br/>  

Kita perlu mengetahui petunjuk penggunaan program tersebut agar output yang dihasilkan sesuai yang kita harapkan. Selain itu, perlu diketahui bersama, program ini masih sederhana bahkan belum dilengkapi dengan validasi inputan. Mengingat tujuan awal program ini sebatas memenuhi tugas mata kuliah mimin.. ^^

## Aturan Masukkan Rumus F(x)
Kunci dari aturan masukkan rumus F(x) adalah berpedoman pada bentuk polinomial (suku banyak). Selengkapnya sebagai berikut.
### Operasi Perpangkatan
**Sintak** : x^a (dibaca x pangkat a, dengan a adalah suatu **bilangan asli** dan x adalah suatu variabel yg dapat diganti dengan suatu **bilangan bulat**)  
**Contoh** : x^1, x^12, 2^4, -5^6
### Operasi Perkalian
**Sintak** : x\*x (dibaca x kali x, dengan x adalah suatu variabel yg dapat diganti dengan suatu **bilangan bulat** atau dapat diganti dengan **suatu operasi perpangkatan**)  
Perkalian dapat dilakukan beberapa kali sekaligus seperti contoh berikut.  
**Contoh** :  
+ x\*2
+ 3 \* -2\*x
+ 3 * x^4 * -2^1 * 0 (opsional : gunakan spasi untuk mempermudah penulisan)    

### Operasi Penjumlahan dan Pengurangan
**Sintak Penjumlahan** : x\+x (dibaca x tambah x, dengan x adalah suatu variabel yg dapat diganti dengan suatu **bilangan bulat** atau dapat diganti dengan **suatu operasi perpangkatan** dan **suatu operasi perkalian**)  
Contoh :    
* x + x^2\*3
* 2 + 2\*x\*3 + x^3    

Untuk operasi pengurangan dilakukan dengan menggunakan sintak penjumlahan, contohnya :   
* x+ -2
* 2\*x^2 + -2\*x + -2 + -1\*x    

Jika ingin menuliskan -x maka tuliskan -1\*x.

### Beberapa Contoh Masukkan F(x)
- 2\*x^2 + x + 1
- x^3 + \-1\*x^2 + x + -1
- x^4 \* x^2 + -3\*x\*x^2
- Selebihnya, sesuaikan selera anda dengan mengikuti aturan di atas.


## Aturan Masukkan Interval (x)
**Sintak** : a~b (artinya semua nilai x antara a dan b, dengan a, b bilangan bulat dan b > a)  
**Contoh** :  
- 1~4 (artinya x = {1,2,3,4})
- \-3 ~ 2 (artinya x = {-3, -2, -1, 0, 1, 2})
- \-2020~ -1000   

## CATATAN
- Gunakan spasi untuk mempermudah penulisan, karena hal tersebut tidak berpengaruh.
- Jangkauan nilai f(x) adalah \-2147483648 .. 2147483647
- Program ini masih jauh dari kata sempurna, oleh karena itu, apabila menemukan bug dapat segera memberitahukan kepada mimin. Terima kasih ^^

