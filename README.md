# PEMROGRAMAN WEB 1
Nama : Rizki Khomsatun Barokah

Kelas : TI-1A

NPM : 230102022    

## HTML
HTML adalah sebuah bahasa pemrograman standar yang sering digunakan untuk membuat halaman website yang dapat diakses dengan menggunakan internet. HTML sebuah singkatan dari Hyper Text Makrup Language yang menjelaskan tentang struktur halaman web. Dalam elemen HTML kita tau bagian-bagian seperti heading (judul), paragraf (p), dan masih banyak elemen-elemen yang ada dalam HTML
1. <!DOCTYPE html> menjelaskan bahsa dokumen ini merupakan dokumen HTML5
2. akar halaman dari html yaitu dengan menggunakan elemen <html>
3. informasi meta tentang halaman HTML dengan menggunakan elemen <head>
4. untuk menentukan judul halaman dapat menggunakan element <title>
5. wadah dokumen atau sebagai tempat untuk semua elemen-elemen dapat di masukkan kedalam <body>
6. elemen yang mendefinisikan sebuah judul yaitu dengan h1 selain menggunakan h2 dapat menggunakan <h2> <h3> <h4> <h5> <h6>
7. elemen yang berfungsi untuk mendefinisikan sebuah paragraf maka dapat menggunakan <p>
![alt text](https://github.com/RizkiKhomsatunBarokah/PWEB1/blob/main/SS%20image/Screenshot%20(431).png?raw=true)
8. kita dapat menambahkan sebuah link ke dalam bagian html dengan menggunakan tag <a>.
9. kita dapat menambahkan gambar secara online maupun offline dengan menggunakan sebuah tag HTML <img> dengan tag <src> sebagai sumber file serta <alt> untuk menuliskan teks alternatif serta di ikuti dengan width dan height.
10. Dalam HTML kita dapat memberikan jeda baris dengan menggunakan sebuah tag yang ada, yaitu dengan menggunakan tag <br>.
11. Kita dapat memodifikasi semua tampilan web HTML dengan menggunakan sebuah tag <style></style> dengan menggunakan tag ini kita dapat mengubah seperti background warna, warna font, ukuran teks, jenis font yang ingin kita gunakan. 
- untuk mengubah background warna kita menggunakan tag <background-color>
- untuk mengubah warna teks kita menggunakan tag <color>
- untuk mengubah ukuran font,kita menggunakan tag <font-size>
- untuk mengubah jenis font, kita menggunakan tag <font-family>
- untuk meratakan tulisan kita, dapat menggunakan tag <text-align>
![alt text](https://github.com/RizkiKhomsatunBarokah/PWEB1/blob/main/SS%20image/Screenshot%20(432).png?raw=true)
12. Di dalam suatu HTML kita juga bisa mengatur teks yang akan ditampilkan sesuai dengan yang kita inginkan. 
- untuk teks yang kita tebalkan, dapat menggunakan tag <b></b>
- untuk menandai bahwa itu penting,kita bisa menggunakan tag <strong>
- untuk membuat style teks yang miring,kita bisa menggunakan tag <i>
13. dalam HTML kita juga bekerja sama dengan CSS untuk dapat mempermudah dalam pembuatan web. CSS dapat ditambahkan kedalam HTML dengan menggunakan 3 cara, yaitu dengan:
- style atribut di dalam elemen HTML (inline)
- <style></style> di dalam <head> termasuk ke dalam (internal)
- dengan menggunakan <link> untuk menautkan file CSS eksternal (eksternal).
![alt text](https://github.com/RizkiKhomsatunBarokah/PWEB1/blob/main/SS%20image/Screenshot%20(433).png?raw=true)
14. Dalam HTML kta juga bisa membuat sebuah tabel dengan perintah tag <table> dengan <tr> sebagai baris dan <td> sebagai data tabel serta tag <th> sebagai header dari tabel tersebut. kita juga bisa membuat border tabel dengan menggunakan tag <border> serta menyatukan beberapa baris atau kolom dengan menggunakan tag colspan atau rowspan
15. kita dapat membuat list dengan menggunakan tag HTML. tag list dalam sebuah HTML di bagi menjadi 2, yaitu list ordered dan list unordered. 
- list unordered yaitu list yang tidak berurutan, dapat menggunakan tag <li>
- List ordered, yaitu List yang berututan, untuk menuliskan sesuatu dengan ordered makan bisa menggunakan tag <ol> di ikuti dengan <li> 
![alt text](https://github.com/RizkiKhomsatunBarokah/PWEB1/blob/main/SS%20image/Screenshot%20(434).png?raw=true)
16. atribut Class juga digunakan dalam bahasa pemrograman HTML untuk menunjuk ke nama dalam style sheet. 
- atribut id dapat menentukan id unik untuk elemen HTML yang berfungsi untuk menunjuk ke gaya tertentu dalam sebuah style sheet. 
17. sebuah tag yang berisi pernyataan skrip atau menunjuk ke file skrip eksternal. 


## CSS
CSS adalah sebuah singkatan dari Cascading Style Sheets yang mempunyai arti sebuah bahasa pemrograman yang digunakan untuk menentukan bagaimana dokumen dan website disajikan kepada pengguna. CSS menjelaskan bagaimana elemen HTML harus ditampilkan. 
1. selector CSS. digunakan untuk menemukan elemen HTML. dibagi menjadi beberapa bagian,yaitu:
- Selector sederhana digunakan berdasarkan nama, id, Kelas
- penyeleksi Kombinator berdasarkan hubungan tertentu diantara elemen
- selector kelas semu berdasarkan pada keadaan-keadaan tertentu 
- selector elemen semu memilih dan memberikan gaya pada elemen
- selector atribut berdasarkan atribut atau nilai-nilai atribut.
![alt text](https://github.com/RizkiKhomsatunBarokah/PWEB1/blob/main/SS%20image/Screenshot%20(435).png?raw=true)
2. Sama dengan HTML, CSS juga bisa mengubah warna font maupun warna background. 
3. border style pada CSS juga menentukan jenis batas yang akan ditampilkan 
- dotted menampilkan batas titik-titik.
- dashed menampilkan batas putus-putus.
- solid menampilkan batas yang solid.
- double manmpilkan batas yang ganda.
- hidden perbatasan tersembunyi.
- none tidak menampilkan apapun.
dan masih banyak lagi jenis-jenis border dalam CSS.
![alt text](https://github.com/RizkiKhomsatunBarokah/PWEB1/blob/main/SS%20image/Screenshot%20(437).png?raw=true)
4. Margin pada CSS berfungsi untuk menciptakan ruang disekitar elemen, di luar batas yang ditentukan. elemen dalam margin memiliki nilai :
- auto (browser akan menghitung margin secara otomatis).
- lenght (margin ditentukan dalam px, pt, cm).
- % (menentukan margin dalam % lebar elemen).
- inherit (menentukan sebuah margin haris diwarisi dari elemen induk).
5. height dan width juga digunakan dalam CSS untuk mengatur tinggi serta lebar suatu elemen. 
6. box kotak dalam CSS digunakan ketika berbicara tentang suatu desain dan tata letak. 
- content adalah isi kotak, tempat sebuah teks dan gambar muncul.
- padding berfungsi untuk menghapus area disekitar konten.
- border adalah perbatasan yang mengelilingi padding serta konten.
- margin berfungsi untuk membersihkan area diluar perbatasan. 
7. Dalam CSS juga terdapat element untuk merubah atau menentukan warna teks serta background teks.
8. Dalam sebuah CSS kita dapat dengan mudah menambahkan sebuah icon ke dalam web sesuai yang kita inginkan. kita bisa menambahkan sebuah ikon dengan mudah ke dalam pemrograman dengan perpustakaan ikon seperti font awesome. 
9. style tautan yang ada dalam CSS bergantung pada statusnya. beberapa macamnya yaitu :
- a:link (untuk sebuah tautan normal yang belum dikunjungi).
- a:visited (untuk tautan yang telah dikunjungi pengguna).
- a:hover (untuk tautan saat pengguna mengarahkan mouse ke atasnya).
- a:active (untuk sebuah tautan saat diklik).
10. penggunaan List dalam bahasa CSS masih menggunakan ul ataupun ol tetapi ada yang membedakanya yaitu dengan menggunakan list-style-type.
11. properti indeks-Z berfungsi menentukan urutan tumpukan suatu elemen agar tidak terjadi tumpang tindih dengan elemen yang lainnya. 
12. sebuah CSS memiliki properti untuk menentukan atau memotong sebuah konten ataupun mengatasinya dengan menambahkan scrollbar,yaitu dengan menggunakan overflow. beberapa macam overflow yang ada, yaitu :
- visible (merupakan sebuah bawaan yang dimana overflow tidak terpotong tetapi konten yang kita maksudkan ditampilkan diluar kotak).
- hidden (overflow terpotong dan konten yang berada di luar kotak tidak akan ditampilkan).
- scroll (overflow yang terpotong akan ditambahkan scrollbar untuk melihat konten lainnya).
- auto (mirip dengan scroll tetapi di dalam auto ini menambahkan sebuah scrollbar jika benar-benar dibutuhkan).
![alt text](https://github.com/RizkiKhomsatunBarokah/PWEB1/blob/main/SS%20image/Screenshot%20(438).png?raw=true)
13. kombinator dalam CSS berfungsi untuk menjelaskan hubungan antara penyeleksi. ada 4 jenis kombinator, yaitu:
- descendent selector (space).
- child selector (>).
- adjacent sibling selector (+).
- general sibling selector (~).
14. CSS attribute selector digunakan untuk memilih elemen dengan atribut tertentu.
15. automatich Numbering with counters dalam CSS berfungsi pada nilai variabel. nilai variabel dapat ditambah dengan menggunakan aturan Css itu sendiri. 
- counter-riset (berfungsi untuk membuat ataupun mengatur ulang counter).
- counter-increment (berfungsi untuk menambahkan penghitung).
- content (berfungsi untuk menyisipkan konten yang dihasilkan).
- counter() atau counters() berfungsi untuk menambahkan nilai penghitung ke dalam suatu elemen.

## JAVASCRIPT
Javascript adalah sebuah bahasa pemrograman yang digunakan developer untuk membuat halaman web yang interaktif.
1. Javascript Values. di dalam Javascript sintaks dapat mendefinisikan 2 jenis nilai, yaitu:
- fixed Values.
- variabel values.
2. Javascript variabel. dapat di deklarasikan dengan 4 macam, yaitu :
- Automatically
- Using var.
- using let.
- Using Const. 
3. Javascript Arithmetic. beberapa tanda dalam aritmatika:
- penjumalahn (+).
- pengurangan (-).
- perkalian (*).
- pembagian (/).
- modulus (%).
- kenaikan (++).
- mengurangi angka (--).
- eksponensial (**) menaikan operan pertama ke pangkat operan kedua. 
![alt text](https://github.com/RizkiKhomsatunBarokah/PWEB1/blob/main/SS%20image/Screenshot%20(439).png?raw=true)
4. Javascript Assigment. 
![alt text](https://github.com/RizkiKhomsatunBarokah/PWEB1/blob/main/SS%20image/Screenshot%20(430).png?raw=true)
5. Javascript Data Type. Javascript memiliki beberapa data type, yaitu:
- string
- number. 
- bigint.
- boolean.
- undefined. 
- null. 
- symbol.
- object.
dan object data type:
- an object 
- an array.
- a date. 
6. Javascript Function sintaks. function dalam Javascriptdidefinisikan dengan:
function name (parameter1, parameter2). 
pemanggilan function dilakukan ketika ada sesuatu yang memanggilnya. 
- Saat suatu peristiwa terjadi
- ketika dipanggil dari kode Javascript
- secara otomatis. 
![alt text](https://github.com/RizkiKhomsatunBarokah/PWEB1/blob/main/SS%20image/Screenshot%20(440).png?raw=true)
7. String dalam Javascript. string berguna untuk menyimpan teks dan ditulis menggunakan tanda kutip. string yang dibuat dengan tanda kutip tunggal atau ganda memiliki fungsi yang sama, tidak ada sebuah perbedaan antara keduanya. 
![alt text](https://github.com/RizkiKhomsatunBarokah/PWEB1/blob/main/SS%20image/Screenshot%20(441).png?raw=true)
8. array dalam Javascript berfungsi untuk menampung banyak nilai dalam sebuah nama yang sama atau dalam satu nama array. 
9. Math dalam Javascript tidak memiliki konstruktor dan bersifat statis. semua metode dan properti dapat digunakan tanpa membuat objek math telebih dahulu. 
10. Loop dalam Javascriptatau disebut dengan perulangan berfungsi untuk menjalankan kode yang berulang kali,setiap kali dengan nilai berbeda. 
![alt text](https://github.com/RizkiKhomsatunBarokah/PWEB1/blob/main/SS%20image/Screenshot%20(442).png?raw=true)
