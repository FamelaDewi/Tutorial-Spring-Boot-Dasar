# Tutorial-Spring-Boot-Dasar

## Agenda

* Pengenalan Spring
* Inversion Of Control
* Application Context
* Depedency Injection
* Bean
* Life Cycle
* Event Listener
* Dan lain-lain

## Apa itu Spring ?

Spring merupakan framework Java yang mempermudah para programmer dalam membuat sebuah aplikasi Java dengan menerapkan salah satunya adalah design-patern : dependency-injection. Beberapa Fitur yang disediakan Spring Framework adalah sebagai berikut.

* Depedency Injection
* Aspect Oriented Programming
* Spring MVC dan Restful Web Service
* Support koneksi database, dsb.

### Pengenalan Spring Framework
* Spring Framework adalah framework paling populer di Java
* Saking Populernya,Spring Framework sampai mengalahkan popularitas Java Enterprise sendiri
* Spring Framework Semakin Populer karena sangat ringan dan mudah digunakan dibandingkan Java Enterprise
* [https://spring.io/]

### Pengenalan Spring Boot
Spring Boot merupakan framework untuk mempermudah pembuatan aplikasi Spring Framework
Dahulu untuk menggunakan Spring Framework, untuk pemula tidaklah mudah, karena terlalu banyak yang harus dilakukan sebelum bisa membuat aplikasi
Spring Boot menjadikan kompleksitas tersebut ditangani secara otomatis oleh Spring Boot, sehingga kita bisa membuat aplikasi * Spring Framework secara cepat tanpa harus melakukan pengaturan apapun
Spring Boot sekarang sudah menjadi salah satu framework wajib ketika kita ingin membuat aplikasi Spring Framework

### Kenapa Menggunakan Spring?
* Tidak bisa dipungkiri, saat ini Spring adalah satu-satunya framework paling populer di Java
* Belum ada yang bisa menandingi popularitasnya di Java
* Saking populernya, bahkan banyak perusahaan pindah ke JVM karena ingin menggunakan Spring-nya, bukan Java
* Dengan banyaknya bahasa yang bisa berjalan di atas JVM, seperti Kotlin, Groovy dan Scala, maka secara programmer punya banyak pilihan bahasa pemrograman ketika menggunakan Spring Spring juga sudah banyak sekali diadopsi di banyak perusahaan, baik itu skala besar atau kecil

## Inversion Of Control
Inversion of Control jika diterjemahkan secara literer berarti “pembalikan kendali”. Maksudnya, secara istilah,  adalah membalik (atau memindahkan) kendali (atau tanggung jawab) pengelolaan object yang semula dilakukan oleh program dipindahkan ke Framework atau Container.

### Keuntungan IOC
Berikut adalah keuntungan yang akan didapatkan oleh developer ketika menggunakan teknologi IOC.
* Decoupling antar proses eksekusi task dan cara implementasinya.
* Modularity antar komponen semakin bagus
* Dapat memilih dan merubah implementasi suatu proses dengan mudah
* Memudahkan proses testing pada program
* Tidak perlu membuat code yang mengatur cara instantiasi, mengelola object dalam memory, dan membersihkannya setelah tidak digunakan.
 

