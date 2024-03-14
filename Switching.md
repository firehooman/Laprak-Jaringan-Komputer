SWITCHING

![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/0f611407-4559-4be4-a686-85f87bc2410f)

Show ip vlan pada Switch Perintah ini tidak secara eksplisit ada dalam perangkat Cisco IOS; yang lebih umum adalah show vlan atau show vlan brief untuk switch yang menggunakan Cisco IOS. Perintah ini menampilkan informasi tentang VLAN yang dikonfigurasi pada switch, termasuk ID VLAN, nama VLAN, dan port apa saja yang termasuk dalam VLAN tertentu

![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/ececb644-ce26-4518-a213-a7afbbca9b96)

Perintah show running-config menampilkan konfigurasi aktif (yang sedang berjalan) pada switch. Ini mencakup semua pengaturan dan konfigurasi yang telah diterapkan, termasuk konfigurasi VLAN, pengaturan port, konfigurasi trunk, dan lain-lain. Pada ROUTER_1: Perintah yang sama pada router akan menampilkan konfigurasi aktif dari router tersebut, termasuk antarmuka jaringan, rute statis atau dinamis, pengaturan protokol routing, konfigurasi NAT, DHCP, ACLs

![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/c21b9dd3-a3a4-48f9-b457-96779d5dac33)

Menampilkan detail tentang pool DHCP yang telah dikonfigurasi, termasuk range alamat IP yang tersedia untuk disewakan, mask subnet, default gateway, DNS server, lease time, dan lainnya. Ini membantu dalam memahami dan memverifikasi konfigurasi DHCP di jaringan.

![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/b9173eac-3269-4ac6-93ec-d063c34c7d2b)

Termasuk jumlah translasi aktif, jumlah hitungan untuk translasi NAT, dan sumber daya yang 
digunakan. Ini penting untuk memahami seberapa efektif NAT bekerja dan mendiagnosis masalah 
koneksi.

![image](https://github.com/firehooman/Laprak-Jaringan-Komputer/assets/126407683/32023fbb-ec2a-4ecc-84c1-bea66fcbac3f)

Membutuhkan router atau switch layer 3 untuk melakukan routing antar VLAN (InterVLAN routing). Paket dari sumber akan dikirim ke gateway (router atau switch L3), yang kemudian akan meneruskannya ke VLAN tujuan. Konfigurasi NAT: Jika tujuannya berada di luar jaringan lokal (misalnya, Internet), router akan melakukan NAT pada paket tersebut, mengganti alamat IP sumber internal dengan alamat IP publik router sebelum mengirimkannya ke jaringan eksternal. Untuk setiap skenario, perangkat di jaringan harus dikonfigurasi dengan benar, termasuk VLAN, routing, dan NAT, agar komunikasi data berjalan sesuai dengan harapan
