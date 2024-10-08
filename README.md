# Assignment Guidance: GIT Repository

 ![alt text](Logo/Git-Vs-GitHub.png)

Disini saya menjelaskan langkah-langkah untuk menggunakan Git, mulai dari instalasi, inisialisasi repositori, hingga melakukan commit, push, pull dan clone ke repository remote seperti GitHub.

## Prasyarat

- Pastikan Git sudah terinstal di komputer. Anda bisa memeriksa dengan menjalankan perintah:

![alt text](Images/Check_GIT.png)

## Konfigurasi Git

- Setelah Git terinstal, lakukan konfigurasi awal untuk menetapkan nama pengguna dan email yang akan tercatat di setiap commit:
 
  ```bash
  git config --global user.name "Nama Anda"
  git config --global user.email "email@contoh.com"
  ```

## Tahapan-Tahapan menggunakan Git

1. Buat direktori baru untuk proyek Anda, atau buka direktori proyek yang sudah ada:

   ```bash
    mkdir dibimbing-belajar-github
    cd dibimbing-belajar-github
    ```

2. Inisialisasi repositori Git di direktori tersebut :

![alt text](Images/gambar_1.png)

3. Melakukan git add untuk memasukan file ke repository git local :

![alt text](Images/gambar_2.png)

4. Membuat beberapa branch untuk proses lebih lanjut, untuk penamaan branch ya sebagi berikut :

- feature/project_awal
- feature/project_tengah
- feature/project_akhir

![alt text](Images/gambar_3.png)

6.  Pindah ke branch feature/project_awal lalu lakukan proses sebegai berikut :

![alt text](Images/gambar_4.png)

7. Selanjutnya, Pindah ke branch feature/project_tengah lalu lakukan proses sebegai berikut :

![alt text](Images/gambar_5.png)

8. Selanjutnya, Pindah ke branch feature/project_akhir lalu lakukan proses sebegai berikut :

![alt text](Images/gambar_6.png)

9. Setelah itu balik lagi ke branch master lalu ubah namanya ke main :

![alt text](Images/gambar_7.png)

10. Lakukan merge pada setiap branch ke branch utama (main) :

![alt text](Images/gambar_8.png)

11. Adapun gambaran dalam bentuk graph atau struktur git local dan melihat semua riwayat commit :

- Diagram git local melalui terminal
![alt text](Images/gambar_9.png) 

- Diagram git local melalui Gitlens 
![alt text](Images/gambar_9.1.png)

12. setelah melakukan merge, selanjutnya membuat repository di cloud atau di github :

![alt text](Images/gambar_10.png)

13. Lakukan git remote untuk terkoneksikan dengan local ke cloud (github) dan push untuk mengirim ke github :

![alt text](Images/gambar_11.png)

 14. Tampilan file sudah masuk ke repository github :

![alt text](Images/gambar_12.png)

 15. Setelah dimasukan ke repository github lalu ada perubahan pada README.md dan penambahan gambar :

 ![alt text](Images/gambar_13.png)

16. Setelah melakukan perubahan, kemudian lakukan push lagi dengan branch yang berbeda untuk melakukan pull. disini saya menamakan feature/add_and_edit :

- setelah berhasil di push, selanjutnya klik url yang ada pada hasil output ya :
 ![alt text](Images/gambar_14.png)

 17. Setelah klik url ya akan diarahkan ke repository github yang akan melakukan pull :

- klik compore & pull request
 ![alt text](Images/gambar_15.png)

 18. Selanjutnya silakan check kembali perubahan yang dilakukan dan setelah bisa lanjut jika sudah pasti perubahannya :

- Menambahkan gambar
 ![alt text](Images/gambar_17.png)

- Edit README.md
 ![alt text](Images/gambar_18.png)

- Silakan klik create pull request (jika sudah yakin ingin dirubah)
 ![alt text](Images/gambar_16.png)

- Terakhir klik merge pull request dan klik confirm pull
 ![alt text](Images/gambar_19.png)

 19. Setelah berhasil di klik dan tidak terjadi conflict maka perubahan berhasil

 20. Selanjutnya, dari tim lain ingin mealakukan kolaborasi dengan menambahkan logo dan beberapa gambar tapi sebelumnya harus di clone untuk mengambil data dari github atau menyalinnya ke local mereka. maka, Jalankan perintah ini di terminal atau cmd :

   ```bash
    git clone https://github.com/Ajied21/dibimbing-belajar-github.git
   ```
 *untuk url bisa disesuaikan pada repository yang akan di clone

- Tampilan sebelum di clone
 ![alt text](Images/gambar_20.png)

- Setelah di clone
 ![alt text](Images/gambar_20.1.png)

- Check status pada git ya. apakah sama dengan sebelumnya dan ada beberapa update langsung dari github ya yang dilakukan oleh pemilik akun
 ![alt text](Images/gambar_20.2.png)

- Diagram dari Gitlens beserta update ya
 ![alt text](Images/gambar_20.3.png)

21. Setelah menambahkan logo dan bebrapa gambar. Lakukan git add, git commit dan git push ke repository github :

- Melakukan proses
 ![alt text](Images/gambar_21.png)

- Sebelum ditambahkan di github
 ![alt text](Images/gambar_22.png)

- Setelah ditambahkan di github
 ![alt text](Images/gambar_23.png)

22. Terakhir, lakukan git pull di local utama agar dapet update dari tim lain yang sudah di push ke github :

- Kondisi sebelum di pull  
 ![alt text](Images/gambar_24.png)

- Kondisi setelah di pull dan dapet update ya  
 ![alt text](Images/gambar_25.png)

 ## README.md ini mencakup langkah-langkah untuk menggunakan Git dari instalasi hingga manajemen branch, push, pull dan clone ke repository remote. Anda dapat menyesuaikannya lebih lanjut sesuai kebutuhan spesifik.
 
