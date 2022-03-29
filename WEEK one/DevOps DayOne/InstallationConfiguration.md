# Task 1 Day 1

# Step 1

## Download Ubuntu Server dan VMware terlebih dahulu

1. Link untuk mendownload https://ubuntu.com/download/server lalu klik "option 2 - Manual server installation"

![Img 1](assets/1.JPG)

2. Download VMware terlebih dahulu https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html seperti gambar dibawah ini

![Img 1](assets/22.JPG)
Kiri untuk Windows dan kanan untuk Linux

# Step 2

## Instalation and Configuration VMware

1. Setelah download aplikasi maka langsung di install lalu jalankan VMware klik "Create a New Virtual Machine" 

![Img 1](assets/2.JPG)

2. Kemudian pilih "Installer disc image (iso)" agar memasukkan file iso Ubuntu server lalu browse dan pilih file Ubuntu Server yang telah di download sebelumnya

![Img 1](assets/4.JPG)
![Img 1](assets/3.JPG)

3. Selanjutnya Input nama kita dan password nya.

![Img 1](assets/5.JPG)

4. Input size storage yang akan kita gunakan, disini saya memasukkan 15GB, kemudian klik next

![Img 1](assets/6.JPG)

5. Pilih "Customize Hardware" untuk mengkonfigurasi Virtual Machine Ubuntu Server

![Img 1](assets/7.JPG)

6. Kemudian masukkan 2GB untuk memory, Processor 2 Core, pada bagian Network Adapter pilih "NAT" lalu close

![Img 1](assets/8.JPG)

7. Kemudian Finish jika konfigurasi sudah selesai ditentukan

![Img 1](assets/7.JPG)

8. Kita jalankan server yang telah kita buat dengan menekan salah satu dari 2 tombol berikut

![Img 1](assets/23.JPG)

9. Pilih Bahasa Inggris lalu tekan tombol Space pada keyboard

![Img 1](assets/9.JPG)

10. Setelah itu Done


11. Selanjutnya konfigurasi jaringan menjadi Statis dengan klik bagian ens33 eth

![Img 1](assets/10.JPG)

12. Kemudian pilih "Edit IPv4"

![Img 1](assets/11.JPG)

13. Mmasukkan ip statis sesuai device kita dengan cara jika di windows maka ketik ipconfig di cmd

![Img 1](assets/12.JPG)

14. Apabila telah selesai selanjutnya pilih done

15. Kemudian pilih done di tampilan ini

![Img 1](assets/13.JPG)

16. Pilih Done lagi

![Img 1](assets/14.JPG)

17. Klik "Custom Storage Layout"

![Img 1](assets/16.JPG)

18. Pilih "Free Space -> Add GPT Partition" lalu masukan size maksimal dan selanjutnya Create

![Img 1](assets/17.JPG)

19. Jika sudah selesai pilih Done

20.  Disini kita masukkan nama dan password yang nantinya ingin digunakan untuk login di Ubuntu Server, jika udah selesai kemudian pilih done

![Img 1](assets/18.JPG)

21. Pilih "Install OpenSSH Server" lalu klik Done

![Img 1](assets/19.JPG)

22. Nah disini kita klik Done dan munggu hingga proses instalasi selesai

![Img 1](assets/19.JPG)

23.  Jika sudah selesai Tinggal kita Reboot

![Img 1](assets/20.JPG)

24. BRAVO.. !!! Instalasi Dan Konfigurasi di VMware sudah selesai

![Img 1](assets/21.JPG)



