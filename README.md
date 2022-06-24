<h1>Index Pembangunan Kesehatan Masyarakat</h1>

<h2>1.	Background</h2>

Kekerasan Dalam Rumah Tangga (KDRT) merupakan salah satu masalah yang bersifal global yang berdampak luas terhadap kesehatan. Kekerasan tersebut bukan hanya yang         berbentuk fisik, tetapi juga kekerasan psikis, sosial ekonomi dan seksual yang sering kali luput dari perhatian. Pemerintah dalam hal ini berupaya untuk  mengendalikan Kekerasan Dalam Rumah Tangga dalam rangka meningkatkan kualitas kesehatan masyarakat.
IPKM adalah kumpulan indikator kesehatan yang dapat digunakan untuk menggambarkan masalah kesehatan. Banyaknya jenis indikator ini menyebabkan Pemerintah kesulitan dalam menentukan indikator mana yang menjadi sasaran prioritas pembanguan kesehatan masyarakat. Sehingga dalam hal ini, kami ingin membantu Pemerintah untuk menganalisis korelasi diantara indikator-indikator yang ada dalam IPKM. Indikator mana yang merupakan penentu dari suatu program yang akan dijalankan Pemerintah. 
Masalah tidak selesai hanya sampai dengan penentuan indikator dalam IPKM, masalah lain muncul ketika suatu program telah ditentukan dan dijalankan maka dibutuhkan suatu alat untuk memonitor perkembangan dari program tersebut. Pastinya, perubahan akan selalu terjadi. Begitu juga dengan nilai dari indeks-indeks pada IPKM. Oleh karena itu, analyst perlu melakukan pengecekan terhadap efektivitas dari korelasi yang telah ditentukan sejaln dengan penambahan data baru. 

<h2>2.	Objectives</h2>

Upaya kesehatan adalah setiap kegiatan dan/atau rangkaian kegiatan yang dilakukan secara terpadu, dan berkelanjutan untuk memelihara dan meningkatkan derajat kesehatan masyarakat berupa pencegahan penyakit, peningkatan kesehatan, pengobatan penyakit, dan pemulihan kesehatan oleh pemerintah dan membantu menteri kesehatan melakukan rangkaian kegiatan dalam upaya peningkatan kesehatan masyarakat.
IPKM sebagai salah satu alat monitor keberhasilan pembangunan kesehatan masyarakat melalui penentuan peringkat provinsi dan kabupaten/kota.  Indikator-indikator terpilih dalam IPKM lebih menunjukkan dampak dari pembangunan kesehatan tahun sebelumnya dan menjadi acuan perencanaan program pembangunan kesehatan untuk tahun berikutnya. 

<h3>i)	Problem Statement dan personas</h3>

Diharpakan dengan meningkatnya kesehatan dalam masyarakat, tindakan kekerasan dalam rumah tangga menjadi menurun. Oleh karena itu inisiatif yang kami usulkan adalah:
A.	Menganalisa dan mengevaluasi masing-masing indikator 
B.	Mencari korelasi antara indikator yang ada
C.	Membuktikan dan meilhat korelasi antara indikator kesehatan dan indikator kekerasan dalam rumah tangga
D.	Menentukan indikator mana yang menjadi sasaran prioritas dari indikator kesehatn 
E.	Melakukan evaluasi berkelanjutan, secara khusus dari indikator-indikator terpilih dan secara umum dari semua indikator
Inisiatif akan dibuat dalam product yang berbentuk dashboard dengan data yang didapatkan dari open data Jawa Barat dan website KPAI. Produk ini didesain untuk Pemerintah dan Kementrian Kesehatan Provinsi Jawa Barat, dan juga analyst sebagai PIC yang melakukan pengolahan dari data.

<h3>ii)	MVP features</h3>

Membuat dasbor berdasarkan Data Jawa Barat, menghubungkan data antara satu indikator dengan indikator lainnya untuk korelasi dan kesimpulan antara indikator- indikator yang ada. Dasbor akan memiliki fitur sebagai berikut:

a. _HomePage_ – Berisi informasi penjelasan singkat mengenai subject yang dianalisa dan tata cara dari penggunaan dasbor

b. _Overall matrix performance Health index_ (untuk menjawab problem statement poin A,B, dan C), dilengkapi dengan heat map kota-kota di Jawa Barat, menghubungkan data antar indikator, dengan 4 indikator yang mungkin menjadi penyebab utama, yakni:

  i.	Bayi Gizi Buruk
  
  ii.	Balita Gizi Buruk
  
  iii.	Persentase Penduduk yang memiliki keluhan kesehatan
  
  iv.	Penyakit Infeksi Menular Seksual

c.	_Overall matrix on family abuse_ (untuk menjawab problem statement poin A,B, dan C), dilengkapi dengan heat map kota-kota di Jawa Barat dan pengelompokkan berdasarkan umur dan pendidikan. Menghubungkan data antar indikator, dengan 2 indikator yang berkorelasi:

i.	Jumlah kepala keluarga berdasarkan golongan umur

ii.	Jumlah ibu hamil

d.	_Call an action matrix_ (untuk menjawab problem statement poin D&E), untuk beberapa daerah dengan indeks kesehatan rendah dan kekerasan keluarga tinggi, berikut dengan perlindungan anak nasional sesuai data untuk mengetahui daerah mana yang menjadi fokus dan tindakan apa yang diperlukan pada daerah tertentu berdasarkan 3 data tersebut.

<h2>3.	Overview dan Process:</h2>

<h3>a.	Proses</h3>
<p align="center">
  <img src="https://github.com/Marwin88/Project-Lab-BI-1-Pacmann/blob/main/data/picture/Picture1.png" width="350" title="hover text">
</p>

i.	Pengambilan data

Hal pertama yang dilakukan adalah mendapatkan data untuk berbagai masalah yang akan kita analisa. Berikut adalah list data yang mayoritas datanya berasal dari open data Jawa Barat kecuali data pengaduan anak KPAI yang didapat dari site KPAI dan bersifat nasional data. Data akan dikelompokkan kedalam dua grup:
1.	Data Index Kesehatan dan Korelasinya:

a.	Indeks kesehatan berdasarkan kabupaten kota

b.	Jumlah kasus penyakit infeksi menular seksual

c.	Jumlah balita bergizi kurang

d.	Jumlah bayi bergizi buruk

e.	Persentase penduduk yang memiliki keluhan hidup

2.	Data kekerasan anak:

a.	Data pengaduan anak KPAI Nasional

b.	Jumlah korban kekerasan dalam rumah tangga

c.	Jumlah ibu hamil berdasarkan kabupaten kota

d.	Jumlah kepala keluarga berdasarkan golongan umur

e.	Jumlah korban kekerasan berdasarkan kelompok usia

f.	Jumlah korban kekerasan berdasarkan tingkat pendidikan


ii.	Data Cleaning dan Data Merging

Setelah data terkumpul, dalam pengerjaan ini kita bagi kedalam 2 proses yaitu cleaning data pengaduan anak KPAI, lalu data cleaning dan join dengan korban kekerasan. Di proses kedua adalah data merging untuk index kesehatan.

1.	Data Cleaning – Data Kekerasan Anak

Disini dibutuhkan data wrangling dan cleaning karena data KPAI memiliki berbagai macam header yang berbeda dengan data lainnya yang berasal dari Open Data Jawa Barat. Berikut adalah gambaran diagram alur pengerjaan nya dan beberapa point penting di step ini. 

<p align="center">
  <img src="https://github.com/Marwin88/Project-Lab-BI-1-Pacmann/blob/main/data/picture/Picture2.png" width="350" title="hover text">
</p>

a.	Melt data agar mudah dianalisis

<p align="center">
  <img src="https://github.com/Marwin88/Project-Lab-BI-1-Pacmann/blob/main/data/picture/Picture3.png" width="350" title="hover text">
</p>

b.	Karena data kekerasan anak bersifat data nasional, perlu dilakukan interpolasi untuk mencari data jawa barat dengan asumsi total penduduk jawa barat / total penduduk indonesia

<p align="center">
  <img src="https://github.com/Marwin88/Project-Lab-BI-1-Pacmann/blob/main/data/picture/Picture4.png" width="350" title="hover text">
</p>

c.	Data ibu hamil yang sudah clean kita cari besaran persentase nya per kota dan per tahun

<p align="center">
  <img src="https://github.com/Marwin88/Project-Lab-BI-1-Pacmann/blob/main/data/picture/Picture5.png" width="350" title="hover text">
</p>

d.	Merge data dan dapatkan data kekerasan anak per kota kabupaten dan per tahun

<p align="center">
  <img src="https://github.com/Marwin88/Project-Lab-BI-1-Pacmann/blob/main/data/picture/Picture6.png" width="350" title="hover text">
</p>

2.	Data Join – Data Kekerasan Anak dan data Kekerasan dalam Rumah Tangga
Dalam proses ini kita akan mencoba memapping kan data kekerasan anak dan juga kekerasan dalam rumah tangga, dan mendapat data granularity level kota kabupaten dan per tahun. Berikut ini adalah gambaran diagram alur pengerjaan nya dan beberapa point penting di step ini.

 

a.	Mengasumsikan data di kekerasan dalam rumah tangga yang ada dari 2018 dan 2021, diubah menjadi 2018 dan 2020
 
b.	Merge data dan dapatkan data kekerasan anak dan mapping nya dengan data kekerasan dalam rumah tangga
 

3.	Data cleaning untuk index kesehatan
Untuk data index kesehatan, karena data nya berasal dari source data yang sama maka lebih mudah dalam penggabungan datanya. Secara general hanya akan banyak memakai syntax merge dan drop and rename column. Berikut diagram alur pengerjaan nya.
 
iii.	Data Visualization
Dengan data yang sudah clean dengan proses sebelumnya, maka akan lebih mudah untuk menganalisa dan mendapatkan insight saat data kita masukkan ke dalam tableau. Pada dasarnya di proses ini berikut adalah diagram alurnya.
 

b.	User Flow
Setelah dashboard jadi dan terpublish secara publik, berikut adalah userflow yang kita harapkan nantinya akan dijalankan oleh user. Dengan userflow ini akan menjawab beberapa pertanyaan yang sudah ter state di sub bab sebelumnya.
 

1.	Call an action
Adalah dashboard pertama setelah homepage yang akan dijumpai oleh user, dari sini user akan langsung melihat analytics result dari area mana saja yang menjadi perhatian khusus dari sisi index kesehatan dan kekerasan rumah tangga. Hal ini akan menyelesaikan masalah di point D dan E di sub bab sebelumnya.
D. Menentukan indikator mana yang menjadi sasaran prioritas dari indikator kesehatan
E. Melakukan evaluasi berkelanjutan, secara khusus dari indikator-indikator terpilih dan secara umum dari semua indikator
2.	Overall matrix performance Health index dan Overall matrix on family abuse
Di dashboard ini akan membreakdown data per area dan per tahun yang dikehendaki, jadi akan terlihat korelasi antara index kesehatan dan parameter lainnya (seperti gizi buruk, tingkat ims dll), ini akan menyelesaikan masalah di point A B dan C.
A. Menganalisa dan mengevaluasi masing-masing indikator
B. Mencari korelasi antara indikator yang ada
C. Membuktikan dan meilhat korelasi antara indikator kesehatan dan indikator kekerasan dalam rumah tangga


