# Panduan Menggunakan Git

Panduan ini menjelaskan langkah-langkah dasar untuk menggunakan Git, mulai dari instalasi, inisialisasi repositori, hingga melakukan commit dan push ke repository remote seperti GitHub.

## Prasyarat

- Pastikan Git sudah terinstal di komputer. Anda bisa memeriksa dengan menjalankan perintah:

![alt text](Images/Check_GIT.png)

## Konfigurasi Git

- Setelah Git terinstal, lakukan konfigurasi awal untuk menetapkan nama pengguna dan email yang akan tercatat di setiap commit:
 
  ```bash
  git config --global user.name "Nama Anda"
  git config --global user.email "email@contoh.com"


## Inisialisasi Repositori Git

1. Buat direktori baru untuk proyek Anda, atau buka direktori proyek yang sudah ada:

  ```bash
    mkdir dibimbing-belajar-github
    cd dibimbing-belajar-github

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

9. Setelah masing-masing branch melakukan proses ya dan sudah di git commit, lakukan proses merge disetiap branch ke branch utama (main) :

![alt text](Images/gambar_7.png)

 - Pada saat proses merge, terjadi conflict pada feature/project_akhir saat di merge lalu untuk mengatasi conflict ya perlu menambahkan git add dan git commit karena ada beberapa data yang belum di simpan ke git local

 ![alt text](Images/gambar_9.1.png)

10. Adapun gambaran dalam bentuk graph atau struktur git local dan melihat semua riwayat commit :

- Diagram git local melalui terminal
![alt text](Images/gambar_10.png) 

- Diagram git local melalui Gitlens 
![alt text](Images/gambar_10.1.png)

- Riwayat semua commit 
![alt text](Images/gambar_11.png)

11. setelah melakukan merge, selanjutnya membuat repository di cloud atau di github :

![alt text](Images/gambar_12.png)

12. Lakukan git remote untuk terkoneksikan dengan local ke cloud (github) dan push untuk mengirim ke github :

![alt text](Images/gambar_13.png)

 13. Tampilan file sudah masuk ke repository github :



 14. Setelah dimasukan ke repository github lalu ada perubahan pada README.md dan penambahan gambar :

 ![alt text](Images/gambar_7.png)

15. 

