# Docker  

Contoh kasus :  
Komputer B ingin melanjutkan project komputer A, 
Tapi terjadi Issue  

<img src="do1.jpg" width="200" height="100">  

"This app doesn’t work on my machine"  
Issue tersebut muncul karena banyak faktor  

</br>

Untuk hal itu maka kita memerlukan **Docker**  
Docker adalah software yang menjalankan suatu aplikasi menggunakan container  

<img src="do2.jpg" width="200" height="100">  

Docker men-sharing kernel dari host OS, serta meng-container-kan suatu aplikasi agar dapat dijalankan dimana saja dan kapan saja.  

Aplikasi yg berjalan di dalam container docker tidak terpengaruh oleh faktor luar karena terisolasi.   

<img src="do3.jpg" width="200" height="100">  

Docker berfungsi sebagai penyedia layanan virtual bagi aplikasi yg diinstall pada sebuah host.   
Docker akan menyediakan hal-hal yang diperlukan untuk aplikasi mulai dari akses file, koneksi internet, hingga port agar aplikasi dapat berjalan dengan mulus  

</br>

**Container vs Virtual Machine**

<img src="do4.jpg" width="200" height="100">  

VM memakan banyak resource dan waktu utk booting karena melakukan virtualisasi pada host hardware-nya.   
Sedangkan container kebalikannya dari vm, container melakukan virtualisasi pada host OS-nya.  

</br>

### Docker Fundamental

<img src="do5.jpg" width="200" height="100">  

* Docker File : Blueprint untuk membuat image  
* Image : Template untuk menjalankan container  
* Container : Perwujudan dari image  
* Docker Registry : Tempat untuk upload/download image  

</br>

### Perintah Dasar di Docker  
**Docker Pull**  
Download image dari docker hub

<img src="do6.jpg" width="200" height="100">  

</br>

**Docker Run**  
Menjalankan container

<img src="do7.jpg" width="200" height="100">  

<img src="do8.jpg" width="200" height="100">  

</br>

**Docker PS**  
Melihat container yang berjalan

<img src="do9.jpg" width="200" height="100">  

</br>

**Docker File**  
Merupakan sebuah blueprint untuk  membuat image, kamu juga bisa membuat custom image menggunakan docker file.  

<img src="do10.jpg" width="200" height="100">  

Caranya :  
* Buat file Dockerfile di dalam project yang kamu buat  
* Tulis beberapa perintah ke dalam dockerfile  
* Jalankan docker file menggunakan perintah 

<img src="do11.jpg" width="200" height="100">