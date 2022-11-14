# Sequelize  

<img src="se1.jpeg" width="200" height="100">  

>templeate express di awal  

<img src="se2.jpeg" width="200" height="100"> 

>di app js

<img src="se3.jpeg" width="200" height="100">  

>memberitahu bahwa server uda jalan

<img src="se4.jpeg" width="200" height="100">  

> di dalam index kumpulan dr router  
rooter diambil dr express.router  
Maka slash router akan berubah ke

<img src="se5.jpeg" width="200" height="100">  

<img src="se6.jpeg" width="200" height="100">  

>di dalam user.router.js

<img src="se7.jpeg" width="200" height="100">  

> di dalam controller blmada  
itu semua merupakan started template  

</br>

<img src="se8.jpeg" width="200" height="100">  

>tempat sequelize  
dr sequelize menuju database

<img src="se9.jpeg" width="200" height="100">  

> dr orm perintah lbh singkat  
dengan adanya orm lbh mudah  

<img src="se10.jpeg" width="200" height="100">  

> perubahan penggunaan sequalize yg lbh mudah  

</br>

<img src="se11.jpeg" width="200" height="100"> 

> untuk mengsi data dan mencari data 

untuk menggunakan sequalize ada 2 cara :  
* with migration  
* without migration  

Without migration : tinggal ikuti dr step 1

<img src="se12.jpeg" width="200" height="100"> 

>buat dr sini  

Dari getting started  

Migration adalah : History perubahan pada table, jd setiap ada perubahan pada table masuk ke migration  

Contoh perintah ddl masuk ke migration :  
Migration akan menyimpan history perubahan pada table

<img src="se13.jpeg" width="200" height="100">  

>migration : penympan perubah
seeders : butuh data awal, data demo  

sequalize akan menggunakaan pilih default pada dialect masing-masing  
Kalau butuh setting no port mysql bisa tambah port  
Kalau database gk ada bisa menggunakan db: create

<img src="se14.jpeg" width="200" height="100">   

perintah2 sequelize

<img src="se15.jpeg" width="200" height="100">  

>karna database belajar_sequalize blm ada maka menggunakan db:create  

</br>  

Membuat model menggunakan modele:generete

<img src="se16.jpeg" width="200" height="100">  

> migration melakukan perintah membuat table, ada id, name , pass, dsb

<img src="se17.jpeg" width="200" height="100">  

>ada up dan down, up buat table, down hapus table

<img src="se18.jpeg" width="200" height="100">  

> buat ngejalani

<img src="se19.jpeg" width="200" height="100">  

> sehingga muncu database nya

<img src="se20.jpeg" width="200" height="100">  

> deskripsi user

<img src="se21.jpeg" width="200" height="100">  

> sesuai dgn migrasinya  
kalau gk jdi bisa di undo yang dimana dia akan menjalankan down  

<img src="se22.jpeg" width="200" height="100">  

<img src="se23.jpeg" width="200" height="100">  

> sehingga user hilang

<img src="se24.jpeg" width="200" height="100">  

> migration menjalakan sesuai urutan  
kalau memakai undo maka akan mengundo yg paling awal  
kalau undo-all : maka semua akan di down

<img src="se25.jpeg" width="200" height="100">  

> undo ke migration tertentu  

Membuat table :

<img src="se26.jpeg" width="200" height="100">    

setelah itu db: migrate

<img src="se27.jpeg" width="200" height="100">  

> maka colom username jdi ada

<img src="se28.jpeg" width="200" height="100">  

> membuat kolom di tempat yg diinginkan, menggunakan after  

migrtaion : bisa merubah struktur table

<img src="se29.jpeg" width="200" height="100">   

Membuat data awal/data demo

<img src="se30.jpeg" width="200" height="100">  

di file seeders bisa membuat data wal

<img src="se31.jpeg" width="200" height="100">  

<img src="se32.jpeg" width="200" height="100">  

> cth membuat data menggunakan seeder, yg akan masuk ke data base

<img src="se33.jpeg" width="200" height="100">  

> untuk menjalankan 

<img src="se34.jpeg" width="200" height="100">  

> maka akan ada datanya  

Untuk memasukkan querry  

<img src="se35.jpeg" width="200" height="100">  

<img src="se36.jpeg" width="200" height="100"> 

> maka berhasil mendapatkan data

<img src="se37.jpeg" width="200" height="100">  

> memanggil user dr id  

</br>

Model Blog

<img src="se38.jpeg" width="200" height="100">  

<img src="se39.jpeg" width="200" height="100">  

> model blognya

<img src="se40.jpeg" width="200" height="100">  

>sehingga ada table blog  

Isi data blog

<img src="se41.jpeg" width="200" height="100">  

<img src="se42.jpeg" width="200" height="100">  

> di dalam blog

<img src="se43.jpeg" width="200" height="100">  

> kemudian diisi

<img src="se44.jpeg" width="200" height="100">  

> data blognya