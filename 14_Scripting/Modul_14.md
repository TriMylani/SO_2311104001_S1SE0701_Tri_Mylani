# <h1 align="center">Laporan Praktikum Modul 14 <br> Scripting </h1>

<p align="center">Tri Mylani - 2311104001</p>

## Cara compile dan run Bash Script:

        chmod +x nama_file.sh
        ./nama_file.sh

### 1.  PERMULAAN
#### a. Buatlah file bernama greeting.sh sesuai dengan template code.

![alt text](image-6.png)
#### b. Buatlah script pada greeting.sh sehingga:

        i. Dapat menyapa user
        ii. Menampilkan tanggal hari ini
        iii. Menampilkan user yang sedang login saat ini
Contoh eksekusi:
$./greeting.sh

![alt text](image.png)
Hint: gunakan perintah date dan who!

![alt text](image-7.png)

#### 2.  PENGONDISIAN 
#### a. Buatlah file bernama greeting_1.sh sesuai dengan template code.

![alt text](image-8.png)
#### b. Buatlah script pada greeting_1.sh sehingga dapat menampilkan “selamat pagi” pada pagi hari (05:01-10:00), “selamat siang” pada siang hari (10:01-15:00), “selamat sore” pada sore hari (15:01-19:00) “selamat malam” pada malam hari (19:01-05:00).

![alt text](image-1.png)

Hint: gunakan date +%k 

![alt text](image-9.png)

#### 3.  PERULANGAN  
#### a. Buatlah file bernama countdown.sh sesuai dengan template code.

![alt text](image-10.png)
#### b. Buatlah script sehingga menghasilkan countdown dimulai dari angka 10 hingga angka 1 lalu diikuti tulisan “GO!”.

![alt text](image-2.png)
![alt text](image-11.png)

#### 4.  INPUT PENGGUNA   
#### a. Buatlah file bernama countdown_1.sh sesuai dengan template code. 

![alt text](image-12.png)
#### b. Buatlah script sehingga menghasilkan countdown berdasarkan masukan dari user. 

![alt text](image-3.png)
![alt text](image-13.png)

#### 5.  PARAMETER SCRIPT   
#### a. Buatlah file bernama countdown_2.sh sesuai dengan template code.

![alt text](image-14.png)
#### b. Buatlah script sehingga menghasilkan countdown berdasarkan parameter script. Pastikan kondisi-kondisi lain ditangani. 

![alt text](image-4.png)
Hint: gunakan variabel $# untuk mengetahui banyaknya argumen yang diberikan

![alt text](image-15.png)

#### 6.  PENGONDISIAN    
#### a. Buatlah file bernama list_direktori.sh. Jangan lupa untuk mengubah ijin script sehingga dapat dieksekusi.

![alt text](image-16.png)
#### b. Buatlah script sehingga menampilkan semua file pada direktori tersebut.
 
![alt text](image-5.png)

Hint: gunakan * pada bagian “for in”

![alt text](image-17.png)

        
## Referensi
1. Xinu Project. (2024). Embedded Xinu Documentation. Diakses dari: https://xinu.cs.purdue.edu
2. Oracle VM VirtualBox Documentation. Oracle Corporation. https://www.virtualbox.org
3. Sourcetrail Documentation. Coati Software. https://www.sourcetrail.com
