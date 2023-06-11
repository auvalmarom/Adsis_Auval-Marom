## Soal 1
  Buat direktori dengan nama UAP-Adsis, isi dengan file txt dengan format penamaan catatannya-<nama kamu>.txt, kemudian isi file txt tersebut dengan nama dan NIM kamu. Kemudian atur permission view-only pada file tersebut untuk user biasa. Tunjukkan bukti berupa screenshot yang menunjukkan bahwa file tersebut berhasil diatur permissionnya menjadi view-only untuk user biasa.
  ### Jawaban
  1. Membuat direktori baru dengan nama *UAP-Adsis*
        ![1.1](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal1/1.1.jpg)
  2. Pergi ke direktori *UAP-Adsis* kemudian membuat file txt dengan nama *catatannya-auval.txt*
        ![1.2](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal1/1.2.jpg)
  3. Dengan menggunakan perintah 'nano' mengedit isi dari file txt *catatannya-auval.txt* dengan Nama dan NIM
        ![1.3](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal1/1.3.jpg)
  4. Mengubah permission file menjadi read only
        ![1.4](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal1/1.4.jpg)
## Soal 2
  Lakukan konfigurasi alamat IP address sementara pada sistem dan default gateway. (petunjuk 192.168.56.x | x adalah nomor absen)
  ### Jawaban
  1. Mengkonfigurasi alamat ip dan default gateway
        ![2.0](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal2/2.0.jpg)
## Soal 3
  Lakukan Instalasi Webmin lalu buatlah user bernama nama anda, lalu buat group  Adsis_(kelas masing-masing) dan masukkan nama anda di group
  ### Jawaban
  1. Melakukan instalasi Webmin
      ![3.1](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal3/3.1.jpg)
  2. Masuk menggunakan akun user
      ![3.2](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal3/3.2.jpg)
  3. Pilih menu Users and Group kemudian pilih create user
      ![3.3](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal3/3.3.jpg)
  4. Mengisikan username user baru dengan nama saya *auvalmarom*
      ![3.4](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal3/3.4.jpg)
  5. Membuat group baru dengan nama *Adsis_E* dan menambahkan user *auvalmarom* ke dalam group
      ![3.5](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal3/3.5.jpg)
  6. User *auvalmarom* sudah masuk dalam group *Adsis_E*
      ![3.6](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal3/3.6.jpg)
## Soal 4
  Lakukan ping ke alamat ip anda dan coba lakukan reject dan drop di webmin, lalu analisis apa yang terjadi?
  ### Jawaban
  1. Melakukan ping 192.168.56.10 berhasil dengan 0% packet loss
      ![4.0](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal4/4.0.jpg)
  2. Membuat rule ipv4 baru yang akan mengatur reject pada type icmp
      ![4.1](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal4/4.1.jpg)
  3. Melakukan ping 192.268.56.10 ping mengalami packet loss karena icmp telah di reject
      ![4.2](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal4/4.2.jpg)
## Soal 5
  Buatlah perintah otomatis yang berfungsi untuk ping *www.filkom.ub.ac.id*
  ### Jawaban
  1. Menjalankan perintah sudo crontab -e dan menuliskan perintah seperti yang terlihat, perintah tersebut akan melakukan ping ke *filkom.ub.ac.id* pada pukul 16.42 tanggal 11 Juli
      ![5.1](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal5/5.1.jpg)
  2. Dapat terlihat ping ke *filkom.ub.ac.id* telah berjalan secara otomatis pada waktu yang sudah ditentukan
      ![5.2](https://github.com/auvalmarom/Adsis_Auval-Marom/blob/main/Screenshots/Soal5/5.2.jpg)
  
