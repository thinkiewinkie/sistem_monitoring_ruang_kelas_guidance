### Registrasi Perangkat Monitoring

Registrasi perangkat monitoring bertujuan untuk mendaftarkan ID perangkat monitoring dengan cara melakukan aktivasi pada ruangan yang hendak diintegrasikan dengan perangkat monitoring. Dokumen ini menjelaskan prosedur registrasi perangkat monitoring pada sistem monitoring ruang kelas.

#### Ketentuan

Untuk dapat melakukan tindakan ini, diperlukan akun dengan tingkat pengguna berikut:

- **Super Admin**
- **Admin**

#### Langkah-langkah

- Akses Menu Ruangan

  1. Masuk ke dalam sistem dengan akun Super Admin atau Admin Anda.
  2. Navigasikan ke menu **Ruangan** pada antarmuka pengguna.

- Pilih Ruangan

  1. Pada daftar ruangan yang ditampilkan, cari baris yang sesuai dengan ruangan yang ingin Anda aktifkan perangkat monitoringnya.
  2. Klik tombol opsi atau ikon titik tiga **( ⋮ )** yang terletak pada baris ruangan tersebut.
  3. Setelah popup opsi muncul, tekan pada **Rincian**, dan Anda akan diarahkan pada halaman rincian ruangan yang telah dipilih.

     ![activation step 1](https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/activation_1.jpg)

- Aktivasi ruangan

  Setelah masuk kedalam rincian ruangan, anda akan dihadapkan dengan antarmuka yang menampilkan informasi ruangan meliputi nama ruangan, fungsi utama, status, dan perangkat rfid serta informasi tambahan seperti lokasi ruangan. **Perhatikan pada gambar dibawah yang ditandai dengan kotak biru bagian Status dan Perangkat RFID**, ini adalah informasi penting yang menjadi parameter apakah ruangan telah diaktivasi atau belum. Jika pada rincian tertulis dengan status **TIDAK DIKETAHUI** dan juga perangkat RFID **BELUM DIAKTIVASI**, maka Anda dapat memulai aktivasi ruangan dengan menekan tombol **AKTIVASI**. Tindakan ini juga **secara otomatis** akan **mendaftarkan ID perangkat monitoring** ke dalam sistem.

  ![activation step 2](https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/activation_2.jpg)

  Setelah anda menekan tombol **AKTIVASI**, tunggu hingga sistem selesai melakukan aktivasi ruangan dan terjadi perubahan pada status dan perangkat RFID ruangan. Secara default, status ruangan akan berubah menjadi **TERSEDIA** dan perangkat RFID menjadi **SUDAH DIAKTIVASI**, namun Anda akan menemui bahwa pada Informasi RFID menunjukkan bahwa sistem gagal terhubung dengan perangkat monitoring.

  ![activation step 4](https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/activation_3.jpg)

  Untuk mengatasi ini, diperlukan tindakan untuk mengkonfigurasi perangkat monitoring secara langsung. Untuk panduan konfigurasi perangkat dapat diakses pada `Panduan Konfigurasi Perangkat Monitoring` di `Daftar Panduan`.
