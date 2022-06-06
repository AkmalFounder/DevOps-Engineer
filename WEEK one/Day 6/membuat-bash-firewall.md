# Langkah 1

1. Pastikan sudah instal firewallnya dengan cara (sudo apt install ufw -y)

![logo](6.png)

2. Lalu buatlah file yang ber extension .sh

![logo](7.png)

3. masukan script di file tersebut dengan cara (sudo nano [namafiletsb])

![logo](8.png)

masukan teks ini

#!/bin/bash

sudo ufw allow 22;sudo ufw allow 80;sudo ufw allow 443



4. lalu kalian check apaka file tersebut sudah bisa di excute? jika belum lakukan perintah

(chmod u+x [namafilenya])



![logo](9.png)

5. jika sudah akan berwarna hijau seperti gambar di bawah

![logo](9.png)

6. untuk menjalankan file tersebut ketik (./namafile)

![logo](10.png)

7. kemudian ketik sudo ufw enable

![logo](11.png)

7. Maka berhasil di jalankan

![logo](12.png)
