PEMBUATAN KABEL STRAIGHT DAN CROSS BESERTA PING JUGA KONFIGURASI DEVICE

A. Pembuatan Kabel Straight dan Cross

  a. Alat dan Bahan

     1. Kabel UTP

![WhatsApp Image 2024-03-14 at 09 05 40](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/6f597000-5a75-4618-94fa-193b883e1933)

    
     2. Tang Crimping

  ![WhatsApp Image 2024-03-14 at 09 05 40 (1)](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/cc09a1d8-ecb9-44ad-92ba-7b5601b3bb1f)


     3. Konektor RJ45

   ![WhatsApp Image 2024-03-14 at 09 05 40 (2)](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/ecbc97ff-a0af-4b7a-a873-07f277dad719)
        

     4. Tester

  ![WhatsApp Image 2024-03-14 at 09 05 40 (3)](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/d186a168-cd4c-4471-9da4-eb0719070ff3)
        

  b. Langkah-langkah

     1. Yang pertama, ambil kabel UTP dan potong kurang lebih sepanjang 1 meter, sebanyak 2 kabel karna kita akan membuat 2 jenis yaitu Straight dan Cross
     
     2. Kuliti bagian kabel menggunakan Tang Crimping, usahakan untuk mengupas kurang lebih 3-5cm dari ujung kabel. Pastikan kabel bagian dalam yang bewarna tidak ada yang terputus

  ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/ee4ccfef-8085-448e-8c6b-4fb2ad92ce3b)


     3. Kabel Straight
     
        1.) Setelah kabel berhasil di Crimping kita bisa menyusun sesuai urutan warna kabel khusus untuk Straight seperti di bawah ini

  ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/689dccf7-cd4c-4a77-8760-aedfb8108343)


        2.) Jika warna kabel berhasil di urutkan. Cobalah untuk meluruskan kabel kabel tersebut sampai sejajar dan lurus.Pastikan ketika proses untuk meluruskan kabel sebaiknya jari kita menekan bagian ujung kabel yang telah di crimping agar tidak ada kabel yang tertarik, agar menghindari perbedaan panjang antara kabel

   ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/e6a62598-d97c-49e5-9a30-636a01ddfd66)


        3.) Lalu jika sudah lurus dan sejajar tinggal kita masukkan ke dalam RJ45 dan setelah di masukkan kita bisa menggunakan alat tang Crimping tadi masukkan kabel yang telah terpasang RJ45 nya ke dalam lubang 8P pada Tang Crimpingnya,tujuannya agar merapatkan dan menekan RJ45 yang berisi kabel tadi

  ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/721d59f9-12d2-4693-bf12-a23d68ad350a)


     4. Kabel Cross
     
        1.) Langkah-langkahnya membuat kabel cross sama persis seperti membuat kabel straight di atas, ikuti langkah 2 dan 3. Namun susunan warna kabelnya berbeda

  ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/34e33763-8b66-4805-a975-9c64bc0c6a5c)

  ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/5c2eb2b5-a692-489b-8e95-4e553494ed45)


     5. Pengetesan dengan Tester
     
        1.) Kita menggunakan kabel tester untuk menguji 2 kabel tadi, masukkan setiap ujung kabel ke dalam slot yang ada di kabel tester
        
        2.) Hidupkan alatnya, jika menguji kabel Straight perlu diperhatikan urutan nomor warna yang tampil di alat kabel tester nya apakah nomor nya sudah sesuai urutan seperti di bawah ini

   ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/0427c961-e058-4feb-985c-831b515ee768)


        3.) Sama halnya jika kita menguji kabel cross kita juga harus memastikan nomor yang tertampil pada alat apakah sudah sesuai dengan urutan di gambar atas tadi


B. Ping dan Konfigurasi Device

   Dalam melakukan percobaan ini karna kita menggunakan kabel LAN, wifi pada laptop kita harus di nonaktifkan terlebih dahulu

   1. Ping

      Dalam melakukan percobaan PING ini kita menggunakan kabel LAN yang terhubung dari laptop ke router melalui HUB. Command yang dilakukan pada WindowsPowershall atau command prompt adalah

    ping @ipAddress

      Lalu akan muncul seperti gamabar di bawah ini:

  ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/b3adf7bc-24d2-4465-b763-30de495e9cfe)

      Apabila saat pengecekan yang muncul adalah "unreachable" maka terdapat masalah pada Jaringan. Apabila yang muncul "Request time out" maka kemungkinan ada masalah di kabel LAN nya

  2. Konfigurasi Device

     Untuk melakukan konfigurasi kita lakukan dengan 2 Laptop yang saling terhubung oleh kabel LAN. Lalu pada ke 2 Laptop kita buka bagian WindowsPoershell atau Command prompt dan cek ip masing masing

     ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/579b06e2-a683-4603-9bce-c6b6a1dff7b0)

     Jika sudah mendapat Ip masing masing kita bisa mencoba untuk masuk ke user dari laptop lain dengan command ssh usr@IpAdd usr diisi dengan username device lain dan IpAdd diisi dengan ip address dari device yg ingin kita konfigurasi

     ![Screenshot 2024-01-29 144817](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/a4af4161-b367-41d1-8591-247bbb76c86c)

     Jika ingin keluar, tinggal brerikan commmand exit
      
