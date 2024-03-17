# tugas-modul-switching
# Network Address Translation (NAT)

Konfigurasi NAT di Cisco Packet Tracer
![hasil](https://github.com/habibh028/tugas-modul-switching/assets/126387192/27a70538-5509-4ff5-b1fc-5ae618a3bd1d)

-----------------------------------------

langkah langkah nya :
1. buat dan siapkan: 4 pc, switch, 2 router, dan server, lalu hubungkan.

   ![1](https://github.com/habibh028/tugas-modul-switching/assets/126387192/c7c9998c-07c4-4488-a8cc-f794832cfc08)

2. pada PC konfigurasikan IP DHCP nya

    ![pc](https://github.com/habibh028/tugas-modul-switching/assets/126387192/a8084855-187f-4edf-a360-785c742814de)


3. Konfigurasi Switch

    <img src="https://github.com/habibh028/tugas-modul-switching/assets/126387192/67ad3e82-d4ee-4ba6-9fe9-100485e77612" width="70%" height="70%">

4. konfigurasi pada router 1

   <img src="https://github.com/habibh028/tugas-modul-switching/assets/126387192/9a648573-ff3f-4caa-b471-cb052f27970d" width="70%" height="70%"> 

   <img src="https://github.com/habibh028/tugas-modul-switching/assets/126387192/e3c238f0-f7d9-439c-99af-118ec781a5d7" width="70%" height="70%"> 
   
   <img src="(https://github.com/habibh028/tugas-modul-switching/assets/126387192/18cbc3d0-3247-460e-836a-1ebee28ea242" width="70%" height="70%">  

5. konfigurasi pada router 2

   <img src="https://github.com/habibh028/tugas-modul-switching/assets/126387192/0840f725-6da8-4433-bbe1-b306014cdfe6" width="70%" height="70%"> 
 
6. Memberi IP pada Server

   <img src="https://github.com/habibh028/tugas-modul-switching/assets/126387192/cda7039b-7cc8-45a4-8bbe-cdec69b07cf0" width="70%" height="70%"> 

7. Uji coba ping pada pc apakah sudah berhasil

   <img src="https://github.com/habibh028/tugas-modul-switching/assets/126387192/e083d4c1-fbe5-4c29-8064-94d0431d58a9" width="70%" height="70%"> 

-----------------------------------------

Mencoba `show ip dhcp pool`, `show ip nat statistics`, dan `show ip nat translation`

![percobaan](https://github.com/habibh028/tugas-modul-switching/assets/126387192/5b40b0d6-c920-4398-bc41-f7a68d5465ca)


`show ip dhcp pool`, `show ip nat statistics`, dan `show ip nat translation` adalah perintah yang digunakan pada router untuk menampilkan informasi terkait konfigurasi DHCP (Dynamic Host Configuration Protocol), statistik NAT (Network Address Translation), dan terjemahan NAT yang sedang berlangsung. 

- `show ip dhcp pool`: Perintah ini digunakan untuk menampilkan informasi terkait konfigurasi pool DHCP yang telah dibuat pada router.
- `show ip nat statistics`: Perintah ini digunakan untuk menampilkan statistik terkait proses NAT yang berjalan pada router, seperti jumlah alamat IP yang telah diterjemahkan.
- `show ip nat translation`: Perintah ini digunakan untuk menampilkan daftar terjemahan alamat IP yang sedang berlangsung pada router.

Dengan menggunakan perintah-perintah ini, Anda dapat memantau dan menganalisis konfigurasi serta aktivitas DHCP dan NAT pada router.


