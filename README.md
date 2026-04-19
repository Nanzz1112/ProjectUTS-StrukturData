# ProjecUTS-StrukturData

Pada project UTS mata kuliah Struktur Data yang diempu oleh I Made Gede Sri Artha, S.T.


- Dhananjaya 2501010023 - Nanzz1112

- I Gede Raditya Ananda Putra 2501010024 - heyitsraditya

- Dewa Gede Ardhi Giridhana 2501010019 - Giridhanaaa

kami memilih studi kasus nyata berupa antrian coffee shop, dan kami menggunakan konsep  ***Queue*** dalam merancang dan mengimplementasikan sebuah sistem se
derhana

# Antrian Coffee Shop

# Rumusan Masalah dan Solusi

## Rumusan Masalah
1. Bagaimana queue dapat digunakan untuk mengelola antrian pelanggan?
2. Bagaimana implementasi Queue menggunakan Array dalam sistem antrian?
3. Bagaimana sistem antrian tersebut dapat meningkatkan efisiensi pelayanan di coffee shop?

## Solusi
1. Dalam operasional coffee shop, pengelolaan antrian pelanggan merupakan aspek penting untuk menjaga keteraturan dan keadilan dalam pelayanan. Tanpa sistem yang jelas, antrian dapat menjadi tidak terorganisir dan berpotensi menimbulkan ketidakpuasan pelanggan. Oleh karena itu, diperlukan suatu metode yang mampu mengatur urutan pelayanan secara sistematis. Konsep Queue dalam struktur data menawarkan solusi yang tepat karena menerapkan prinsip First In First Out (FIFO), sehingga pelanggan yang datang lebih awal akan dilayani terlebih dahulu.

#### Queue dengan prinsip FIFO (First In First Out):
- Pelanggan yang datang lebih dulu → dilayani lebih dulu
- Pelanggan baru → masuk ke belakang antrian

#### Contoh alur:
- Andi datang → masuk antrian
- Budi datang → di belakang Andi
- Citra datang → di belakang Budi
- Barista melayani → Andi keluar dari antrian

Ini juga memastikan agar antrian adil dan teratur sehingga tidak ada yang menyela antrian.


2. Dalam mengimplementasikan konsep Queue ke dalam sistem nyata, diperlukan struktur data yang mampu menyimpan dan mengelola data antrian secara efisien. Salah satu struktur data yang dapat digunakan adalah Array. Array memungkinkan penyimpanan data secara berurutan sesuai dengan urutan kedatangan pelanggan. Dengan memanfaatkan indeks pada Array, proses penambahan (enqueue) dan penghapusan (dequeue) data dapat dilakukan secara terstruktur dan mudah dipahami.

#### Contoh Queue dengan Array:
- front → posisi pelanggan pertama
- rear → posisi pelanggan terakhir
```
Array: [Andi, Budi, Citra, (kosong), (kosong)]
         ↑            ↑
       front        rear
```


3. Penerapan konsep Queue dalam sistem antrian tidak hanya bersifat teoritis, tetapi juga memiliki dampak nyata dalam meningkatkan kualitas pelayanan di coffee shop. Sistem yang dirancang diharapkan mampu mengatasi berbagai permasalahan seperti ketidakteraturan antrian, lamanya waktu tunggu, serta kurangnya transparansi dalam pelayanan. Dengan adanya sistem antrian yang terstruktur, proses pelayanan dapat berjalan lebih efisien, adil, dan mudah dipantau, sehingga memberikan pengalaman yang lebih baik bagi pelanggan.

#### Sistem ini membantu coffee shop dalam:
Menghindari kekacauan antrian

- Tidak ada rebutan
- Memberikan pelanggan urutan jelas
- Meningkatkan efisiensi pelayanan
  
Monitoring antrian

- Bisa tahu jumlah pelanggan yang menunggu
- Bisa estimasi waktu tunggu

#### Contoh:
- Nomor antrian otomatis
- Layar display nomor pelanggan berikutnya
- Integrasi dengan aplikasi kasir

# Landasan Teori
Struktur data merupakan cara untuk menyimpan, mengorganisasikan, dan mengelola data agar dapat digunakan secara efisien dalam suatu program. Pemilihan struktur data yang tepat sangat berpengaruh terhadap performa program, baik dari segi kecepatan maupun penggunaan memori. Struktur data menjadi dasar dalam pengembangan perangkat lunak karena membantu dalam mempermudah proses pengolahan data serta implementasi algoritma secara optimal.

Salah satu jenis struktur data linear yang sering digunakan adalah stack dan queue. Stack adalah struktur data yang bekerja dengan prinsip Last In First Out (LIFO), yaitu data yang terakhir masuk akan menjadi data pertama yang keluar. Sedangkan queue merupakan struktur data yang menggunakan prinsip First In First Out (FIFO), di mana data yang pertama masuk akan menjadi yang pertama keluar. Kedua struktur data ini banyak digunakan dalam berbagai aplikasi nyata seperti sistem antrian, manajemen memori, serta pengolahan data .

Konsep FIFO dan LIFO menjadi dasar utama dalam pengoperasian queue dan stack. FIFO menggambarkan sistem antrian seperti pada pelayanan pelanggan, di mana yang datang lebih dulu akan dilayani terlebih dahulu. Sebaliknya, LIFO menggambarkan sistem tumpukan seperti tumpukan benda, di mana elemen terakhir yang ditambahkan akan diambil terlebih dahulu. Perbedaan konsep ini menentukan bagaimana data diakses dan diproses dalam suatu sistem.

Dalam implementasinya, stack dan queue dapat dibangun menggunakan beberapa struktur dasar seperti array dan linked list. Array menyimpan data secara berurutan dalam memori dengan ukuran tetap, sehingga akses data menjadi cepat. Sementara itu, linked list menggunakan node yang saling terhubung, sehingga lebih fleksibel dalam hal penambahan dan penghapusan data. Pemilihan antara array dan linked list biasanya disesuaikan dengan kebutuhan sistem, seperti efisiensi memori dan kompleksitas operasi.


