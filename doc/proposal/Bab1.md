**BAB I**

**PENDAHULUAN**

1.
  1. 1 **Latar Belakang Masalah**

PT Sinar Anugerah merupakan salah satu dari sekian perusahaan yang menjalankan bisnis pengelolaan barang. Perusahaan yang berdiri sejak tahun 2004 ini sudah melakukan  sistem pendataan dengan menggunakan sistem aplikasi. Misalnya semua pendataan  barang masuk dan keluar serta _return_ barang.Akan tetapi sistem aplikasi yang telah dibuat pada proyek 1 sebelumnya masih terdapat kekurangan yaitu belum adanya rekapitulasi hasil pendapatan tiap per bulan dan per tahun.

Pada pembuatan aplikasi pada proyek 1 sebelumnya,belum terdapat proses untuk mengelola rekapitulasi hasil pendapatan berdasarkan waktu yang ditentukan. Sehingga rekapitulasi tersebut dilakukan dengan cara manual yaitu masih menggunakan _blueprint_ dan tidak secara komputerisasi sehingga data-data tersebut terkadang kurang relevan dan sering hilang atau rusak. Selain itu dalam aplikasi ini juga belum memiliki fitur _chart_ yang berfungsi untuk memudahkan pegawai PT. Sinar Anugerah membandingkan jumlah pendapatan dari hasil penjualan untuk tiap bulan dan tiap tahunnya.

Maka dari itu dengan adanya kekurangan-kekurangan tersebut, dibutuhkan suatu pengembangan aplikasi yang bertujuan untuk membantu dan mempermudah pegawai PT. Sinar Anugerah dalam merekapitulasi dan menganalisis hasil pendapatan.Dalam hal ini, kami berusaha mengembangkan sebuah aplikasi dimana aplikasi ini akan dikembangkan dengan menggunakan web service kemudian untuk bahasa pemrograman menggunakan PHP dan untuk integrasi datanya akan dibangun sebuah wadah penyimpanan berupa database dengan menggunakan Mysql. Adapun proyek ini kami beri judul &quot;Pengembangan Aplikasi Pengelolaan dan Transaksi Barang PT. Sinar Anugerah Berbasis Framework CI Sub Modul Penjualan&quot;.



1.
  1. 2 **Identifikasi Masalah**

Identifikasi masalah yang didapat dalam perancangan sistem informasi ini sebagai berikut :

1. a)Dibutuhkan pengelolaan rekapitulasi hasil pendapatan agar lebih mudah dalam menghitung keuntungan dan kerugian yang diterima.
2. b)Dibutuhkan fitur chart yang berfungsi untuk memudahkan pegawai dalam membandingkan besar pendapatan setiap tahun dan setiap bulan.
3. c)Terdapat kelemahan dalam segi keamanan sehingga memungkinkan terjadinya peretasan konten dan data pada aplikasi pengelolaan dan transaksi barang PT.Sinar Anugerah

1.
  1. 3 **Tujuan**

Berdasarkan latar belakang dan identifikasi masalah diatas, maka tujuan yang ingin dicapai adalah :

1. a)Menambah fitur pada aplikasi yang digunakan untuk mengelola rekapitulasi hasil pendapatan.
2. b)Menambah fitur _chart_ pada aplikasi yang digunakan untuk mempermudah pegawai dalam membandingkan besar pendapatan setiap tahun dan setiap bulan.
3. c)Meningkatkan keamanan aplikasi untuk menghindari atau meminimalisir terjadinya peretasan konten dan data.

1.
  1. 4 **Ruang Lingkup**

Agar pokok permasalahan pembuatan sistem informasi pengelolaan  ini terarah maka pembatasan masalah adalah sebagai berikut :

1. a)Pengembangan aplikasi ini menggunakan PHP sebagai bahasa pemprogamannya disertai dengan OAuth2 sebagai penunjangnya dan Mysql Sebagai DBMS, serta windows sebagai sistem operasinya.
2. b)Aplikasi hanya dikelola oleh seorang administrator, pegawai sales, dan pegawai gudang dari pihak pengelola yang mempunyai hak akses penuh dalam pengelolaan data, sedangkan konsumen  atau para pengunjung tidak disediakan layanan dalam aplikasi ini. Untuk aktivitas pada pihak supplier maupun konsumen tidak dikaitkan pada aplikasi ini dikarenakan data dan aktivitas yang diambil pada supplier dan konsumen hanya berubah data nya saja kemudian dijadikan sumber acuan pada sistem.

1. c)Pada return barang ke supplier, proses pergantian barang rusak dari supplier ke PT. Sinar Anugerah tidak di proses secara mendetail.

1.
  1. 5 **Sistematika Penulisan**

Laporan proyek I yang berjudul &quot;Pengembangan aplikasi Pengelolaan dan Transaksi Barang PT Sinar Anugerah  Berbasis Framework CI Sub Modul Penjualan&quot; ini terdiri dari  5 bab yaitu :

Bab I Pendahuluan berisikan tentang PT Sinar Anugerah dan segala proses pendataan  yang sedang berjalan dimana pendataan barang-barang yang dilakukan masih dikelola tanpa sistem komputerisasi .

Bab II Landasan Teori berisikan tentang teori dan referensi yang berkaitan dengan  pengelolaan barang. Selain itu, BAB II ini berisikan tentang teori-teori seperti bahasa pemrograman PHP, MySQL, Database, _Context Diagram_, Data Flow Diagram, HTML, _Macromedia Dreamweaver 8_, _Website_, dan _Software_ yang akan menunjang dalam perancangan dan pembuatan aplikasi sistem informasi _opensource_ pengelolaan barang berbasis web ini.

Bab III Analisis dan Perancangan berisikan tentang analisis sistem yang sedang berjalan saat ini menggunakan flow map, metode alirnya menggunakan _Unfied Modeling Language_ (UML) yang terdiri dari _Use Case_, _Class Diagram, Sequence Diagram, Communication Diagram, Activity Diagram, Statechart, Deployment Diagram, Component Diagram, dan Object Diagram_. Perancangan sistem yang akan dibangun mengacu pada sistem yang saat ini sedang berjalan, sehingga sesuai dengan karakteristik sistem manual yang sudah ada dan tentunya tidak mengubah fungsi-fungsi sistem yang sudah berjalan di suatu perusahaan.

Bab IV Pada bab ini berisi implementasi sistem yang menjelaskan tentang implementasi hasil dari analisis dan perancangan sistem ke dalam bentuk Bahasa pemograman, serta kebutuhan dalam mengembangkan sistem. Selain itu, akan membahas tentang pengujian aplikasi yang dibuat.

Bab V berisikan kesimpulan tercapai atau tidaknya tujuan dibuat Pengembangan Aplikasi Pengelolaan dan Transaksi Barang PT Sinar Anugerah  berbasis Framework CI Sub Modul Penjualan ini serta saran untuk membangun website ini menjadi lebih baik.

1.
  1. 6 **Jadwal Kegiatan Pengerjaan Proyek**

| Kegiatan | Oktober | November | Desember | Januari | Februari |
| --- | --- | --- | --- | --- | --- |
| | Minggu | Minggu | Minggu | Minggu | Minggu |
| | 1  2  3  4 | 1  2  3  4 | 1  2  3  4 | 1  2  3  4 | 1  2  3  4 |
| Pengajuan dan Review Proposal | o x x o | o o o o | o o o o | o o o o | o o o o |
| Proses Bimbingan | o o x x | x x x x | x x x x | x o o o | o o o o |
| Pengumpulan draft laporan | o o o o | o o o o | o o o o | x x o o | o o o o |
| Sidang Proyek I | o o o o | o o o o | o o o o | o x x x | o o o o |
| Pengumpulan distribusi CD dan Jurnal Proyek I | o o o o | o o o o | o o o o | o o o x | x o o o |


Table 1.1 Jadwal Kegiatan