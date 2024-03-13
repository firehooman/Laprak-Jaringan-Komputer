1. Komunikasi Data

   Pada bagian ini kita akan mencoba menjalankan paket data melalui Wireshark dengan Capturing From Wi-Fi. Bagian ini saya memerlukan waktu 10 menit untuk mendapatkan paket data yang sedang berjalan. 

   ![Screenshot (480)](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/74b167d8-04b9-4226-bd3a-d76c0e3db8ae)

2. Throughput

   Berikut adalah data yang didapatkan dari paket data yang berjalan pada jarigan Wi-Fi, seperti gambar di bawah ini :

   ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/43deb138-4ffd-43cb-a142-091818544929)

   
4. Packet Loss

   Dengan melakukan filtering data seperti gambar di bawah, didapatlah beberapa data paket yang tidak terkirim, dengan total jumlah 21 atau 0.0% dari total paket yang berlangsung. Berikut adalah data packet loss     yang terjadi :

   ![Screenshot (482)](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/3b12a759-af9f-47ea-aafc-0c70bcc17524)
   ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/f56c9bd0-ab1a-412c-8bb5-75e33e6e2150)


   
6. Delay

   Convert semua packet tersebut menjadi format CSV dan lakukan analisis data melalui excel. Karna yang diperlukan hanya informasi waktu, maka hilangkan kolum informasi lain pada file csv yang sudah di export

   ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/0079ed63-b070-4b89-b0aa-c9ae3a81f276)

   Analisis yang didapatkan:

   ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/92d29ffb-284c-4bf6-aa45-c7b9de9974d4)

   Time 1 = Waktu awal
   Time 2 = Waktu awal yang diulai setelah 0
   Delay = Time 2 – Time 1
   
   Jadi didapatkan nilai dari data delay dan rata – rata delay sebagai berikut :

   ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/5030efa8-2a91-41f6-923d-de49a7a68ca4)

   
8. Jitter

   Berikut adalah data yang didapatkan dari nilai delay sehingga mendapatkan Jitter
   
   ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/48d5fda8-5d1c-459c-82ce-17f99a8bebf0)

   Analisis yang didapatkan adalah :
   Delay 1 = Nilai Delay – Nilai Delay Setelahnya 
   Delay 2 = Semua Nilai Delay, Kecuali Delay Pertama
   Jitter = Delay – Delay 1

   Jadi, Didapatkan hasil dari nilai jitter dan rata – rata jitter juga didapatkan sebagai berikut:

   ![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/29450481-4aab-4428-847a-a2235e6e0ca2)

