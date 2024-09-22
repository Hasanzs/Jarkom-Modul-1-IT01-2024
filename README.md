# Jarkom-Modul-1-IT01-2024


## ***KELOMPOK IT 01***
| Nama      | NRP         |
  |-----------|-------------|
  | Aras Rizky Ananta| 5027221053   |
  | Hasan | 5027231073  |  
  


#  Write Up Praktikum Jarkom modul 1 (IT01)




## Advance Sanity Check

### Langkah - langkah :
1. Masukkan ip di soal ke terminal
2. Setelah itu di paket 85 kita bisa lihat ada username: janeD03
3. Setelah itu di paket 85 kita bisa lihat ada namafile: Clue3.txt
4. Lalu dibawahnya ada pesan rahasia cGVud29yZA==
5. Dari kode yang diperoleh, kita Decode dan hasilnya: "penword".
6. Maka flag didapatkan

   
![advanced sanity](https://github.com/user-attachments/assets/e8611e92-7406-448a-b708-93d2df11d5bb)


![decode advance sanity](https://github.com/user-attachments/assets/54ca6d6e-1d67-44a4-8df0-032144a3a262)



<hr>

## FTP Login

### Langkah - langkah :
1. Masukkan ip di soal ke terminal
2. Lalu filter ke FTP
3. Lalu follow stream ke yang mengarah "login/semacamnya"
4. Di salah satu stream kita dapat {username: sn34ky} {password: sup3rsn1ff3r}
5. Maka flag didapatkan


![ss 1](https://github.com/user-attachments/assets/847b50e7-98e0-4790-974a-c2d27677fb76)


![ss2](https://github.com/user-attachments/assets/fa45d715-b5bc-4a60-b96c-a0b6c9daa729)


<hr>

## 22 Nightmare
### Langkah - langkah :
1. Masukkan ip di soal ke terminal
2. Lalu di beberapa streamnya saya menemukan Sh1k4.jpg (ternyata filenya)
3. Lalu saya juga menemukan Noko.py
4. Setelah itu saya Export object kedua itu tadi
5. keyword di Sh1k4.jpg berisikan kata "NUN"
6. lalu kita decode kode biner yang ada input Noko.py
7. Yang didapatkan ialah "Hallo iam Torako Koshi"
8. Maka flag didapatkan
   
![22 nightmare](https://github.com/user-attachments/assets/05fe8b8a-8394-4c61-b8ed-719e85955d00)

<hr>

## Rizzset
### Langkah - langkah :
1. Masukkan ip di soal ke terminal
2. Lalu di beberapa streamnya saya menemukan info domain "www.its.ac.id"
3. Dan ip dari domain tersebut ialah "103.94.189.5"
4. Disini kita diharuskan menggunakan tools "Jarm"
5. Setelah instalasi kita masukkan ip nya di jarm
6. Lalu hasil fingerprint jarmnya didapatkan
7. Maka flag didapatkan

   
![rizzset](https://github.com/user-attachments/assets/bb7fb349-54d8-49dd-a4e6-3182345ecadd)


<hr>


### Pegawai negeri
### Langkah - langkah :
1. Pada bagian FTP-DATA,di line 47 ada sebagian data csv file disana ketemu orang yang password nNnM%coQuF
2. Di file csv 362 ketemu pekerjaannya Cici Mustofa
3. Scroll bagian akhir dari file csv atau bagian akhir upload
![pn](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20010030.png)
![pn1](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20010059.png)
![pn2](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20010118.png)


<hr>


### EZ
1.DI TCP stream 0,ketemu jawaban dan detail yang dimasukkan
2.Di line pertama dari TCP stream 0,ketemu port dari IP 172.24141.242 yang menerima
![E](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20010214.png)
![E1](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20010303.png)


<hr>


### Illegal Breakthrough
### Langkah - langkah :
1.Setiap file di praktikum PCAP ini biasa dimulai dengan serangan oleh Attack jadi korban adalah IP destination dari line pertama
2.Lihat port destination di bagian korban 
3.Di protocol http ketemu ulangan cara masuk dengan akun dan password dan berbeda semua itu diupload ke /ww1.php
4.Jika dilihat dibawah ada tool bernama "Fuzz Faster U Fool v2.1.0-dev" atau official ffufv2.1.0-dev
![IB](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20010754.png)
![IB1](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20012202.png)
![IB2](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20012623.png)


<hr>


### Corporate Breach
### Langkah - langkah :
1.Diline empat sebelum http 404 ada pengiriman data dengan nama hacker
2.Diline 2384 jika dilihat diline 2388 tidak ada "Line-based text data: text/html (21 lines)" beda daari status 200 yang lain
![CB](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20012732.png)
![CB1](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20214954.png)


<hr>


### Suprise
### Langkah - langkah :
1.Diawalan protocol FTP disebutkan versi dideskripsi
2 & 3 Download file dan Eksekusi file
![S](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20012935.png)
![S1](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20013007.png}
![S2](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20013405.png)


<hr>


### Packets Barrage
### Langkah - langkah :
1.Setiap file PCAP biasanya dimulai saat serangan dimulai jadi bagian IP origin diline pertama
2.Shift-msClick http status 404 dan 302
3.Dibawah GET /download.php follow tcp stream atau hhtp ketemu file dan isinya
![pb](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20013457.png)
![pb1](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20013543.png)


<hr>


### Stegography
### Langkah - langkah :
1.Download atau Export data file
2.Cari cara translasi gambar
3.Jika ditranlasi dan dan dibalik ketemu kata "pahlawan keamanan siber"
![Sss](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20013633.png)
![Sss1](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20013831.png)
![Sss2](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20013842.png)
![Sss3](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20013855.png)


<hr>


### Simba
### Langkah - langkah :
1.Saya ketemu dari pertama kali ketemunya file sukses didownload itu dilihat tcp stream dapat terlihat itu sukses karena lewat dari domain mmeyers
2.Saya beruntung
![ssSss](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-19%20140842.png)
![ssSss](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-20%20212030.png)


##### Revisi


### Gajah Terbang(Server Recon)
### Langkah - langkah :
1.Karena protocolnya PostGreSQL
2.Setelah PostgreSQL ketemu port beberapa TCP saya coba semuanya karena tidak ada IP alamat
3.Disalah satu isi dari TCP stream ketemu versi
4.DiTCP stream 9 ketemu akun dan password admin dari rolenya
5.Password di Has translate
![gt](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-20%20190204.png)
![gt1](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-20%20190244.png)
![gt2](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-20%20190656.png)

### Gajah Terbang(Attacker Recon)
### Langkah - langkah :
1.Dilihat dari banned user_id ke 3 yang dimiliki oleh kuntoaji
2.Has translate
3.Di SELECT FROM banned_user: ada id 3 tgl
4.Dilihat dari transaction yang x 3 y z k dia membeli product dengan id 1 dan 4
![gta](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-20%20204958.png)
![gt1](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-20%20190244.png)
![gta2](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-20%20200506.png)

### Malicious Code
### Langkah - langkah :
1.Shift-msClick semua direktori yang dimasukkan
2.Jika dilihat dari berulang kali /index.php artinya orang nya bruteforce ke dir tersebut
3.Manual hitung 
4.Tebak
![mc](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-20%20214018.png)
![mc2](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-20%20191935.png)
![mc3](https://github.com/Hasanzs/Jarkom-Modul-1-IT01-2024/blob/main/Screenshot%202024-09-20%20193049.png)

###
