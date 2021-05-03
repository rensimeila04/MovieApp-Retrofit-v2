# MovieApp
  <p align="center">
  <a <code><img width="40%" src="https://github.com/rensimeila04/MovieApp-Retrofit-v2/blob/master/screenshot.png"></code>
  </a>
  <a <code><img width="23%" src="https://github.com/rensimeila04/MovieApp-Retrofit-v2/blob/master/Screenrecording_20210430_135144.gif"></code>
  </a>
  </P>
  
  # WHAT'S THERE?
  ## ✅ REST API
  > API adalah singkatan dari Application Programming Interface yaitu sebuah software
yang memungkinkan para developer untuk mengintegrasikan dan mengizinkan dua aplikasi yang
berbeda secara bersamaan untuk saling terhubung satu sama lain.
Tujuan penggunaan dari API adalah untuk saling berbagi data antar aplikasi yang berbeda
tersebut, dan juga untuk mempercepat proses pengembangan aplikasi dengan cara menyediakan
sebuah function yang terpisah sehingga para developer tidak perlu lagi membuat fitur yang
serupa.<br><br>
> REST API merupakan salah satu dari desain arsitektur yang terdapat di dalam API itu
sendiri. Dan cara kerja dari RESTful API yaitu REST client akan Melakukan akses pada
data/resource pada REST server dimana masing-masing resource. Atau data/resource tersebut
akan dibedakan oleh sebuah global ID atau URIs (Universal Resource Identifiers).
Jadi, Nantinya data yang diberikan oleh REST server itu bisa berupa format text, JSON atau
XML. Dan saat ini format yang paling populer dan paling banyak digunakan adalah format
JSON.<br><br>
Adapun metode HTTP yang secara umum dipakai dalam REST api adalah:<br><br>
• GET, berfungsi untuk membaca data/resource dari REST server<br>
• POST, berfungsi untuk membuat sebuah data/resource baru di REST server<br>
• PUT, berfungsi untuk memperbaharui data/resource di REST server<br>
• DELETE, berfungsi untuk menghapus data/resource dari REST serve<br>
• OPTIONS, berfungsi untuk mendapatkan operasi yang disupport pada resource dari
REST server.<br>
  ## ✅ Retrofit
  > Retrofit adalah sebuah library android yang membantu pengembang untuk melakukan
request ke sebuah endpoint REST API. Library ini dikembangkan oleh Square Inc
(https://github.com/square) sebuah perusahaan yang berbasis di Amerika Serikat. Library ini
menyederhanakan kode program yang digunakan untuk mengakses REST API. Tidak hanya untuk
mengakses REST API dengan proses sederhana (GET, POST, PUT, DELETE) retrofit juga
mendukung berbagai macam format authentikasi via http, menambahkan header pada request,
menambahkan parameter serta mengirim data berupa image ke server.<br>

> Terdapat 3 komponen utama dalam Retrofit, yaitu :<br>
> - [x] Database<br>
> Database merupakan class object (singleton) yang di gunakan untuk mendaftarkan class Data Access Object dan berfungsi sebagai titik akses utama ke remote database (REST API).<br>
> - [x] Model<br>
> Model merupakan class yang di gunakan untuk menyimpan suatu nilai atau data. Retrofit membutuhkan class model untuk menyimpan data respon yang di dapat dari REST API.<br>
> - [x] Data Access Object<br>
> Data Access Object (DAO) merupakan antaramuka (interface) yang di gunakan retrofit untuk akses data dari class client ke remote database (REST API) serta memuat metode yang di gunakan untuk mengakses resourcenya.<br><br>
  > More <br>
  > [>> Vogella ](https://www.vogella.com/tutorials/Retrofit/article.html)<br>
  > [>> Codepath ](https://github.com/codepath/android_guides/wiki/Consuming-APIs-with-Retrofit)<br>
  > [>> Meetme ](http://engineering.meetme.com/2014/03/best-practices-for-consuming-apis-on-android/)<br>
  > [>> Jack Wharthon ](https://speakerdeck.com/jakewharton/simple-http-with-retrofit-2-droidcon-nyc-2015)<br>
  > [Retrofit](https://square.github.io/retrofit/)
  
