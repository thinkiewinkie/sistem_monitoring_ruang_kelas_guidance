## Aktivasi Ruangan

Aktivasi ruangan pada sistem bertujuan agar **perangkat monitoring fisik** dapat memberikan informasi akses secara langsung ke sistem serta memberikan akses terhadap kontrol aliran listrik pada ruangan. Dokumen ini menjelaskan prosedur aktivasi ruang kelas pada sistem yang memerlukan hak akses pengguna sebagai **Super Admin** atau **Admin**. Pastikan Anda memiliki hak akses yang sesuai sebelum melanjutkan.

### Langkah-Langkah

- **Akses Menu Ruangan:**

  1. Masuk ke dalam sistem dengan akun Super Admin atau Admin Anda.
  2. Navigasikan ke menu **Ruangan** pada antarmuka pengguna.

- **Pilih Ruangan:**

  1. Pada daftar ruangan yang ditampilkan, cari baris yang sesuai dengan ruangan yang ingin Anda aktifkan perangkat monitoringnya.
  2. Klik tombol opsi atau ikon titik tiga **( ⋮ )** yang terletak pada baris ruangan tersebut.
  3. Setelah popup opsi muncul, tekan pada **Rincian**, dan Anda akan diarahkan pada halaman rincian ruangan yang telah dipilih.

  <img src="https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/activation_1.png" alt="room_activation_step_1" loading="lazy" width="360px" />

- **Aktivasi ruangan:**

  Setelah masuk kedalam rincian ruangan, anda akan dihadapkan dengan antarmuka yang menampilkan informasi ruangan meliputi nama ruangan, fungsi utama, status, dan perangkat rfid serta informasi tambahan seperti lokasi ruangan. **Perhatikan pada gambar dibawah yang ditandai dengan kotak biru bagian Status dan Perangkat RFID**, ini adalah informasi penting yang menjadi parameter apakah ruangan telah diaktivasi atau belum. Jika pada rincian tertulis dengan status **TIDAK DIKETAHUI** dan juga perangkat RFID **BELUM DIAKTIVASI**, maka Anda dapat memulai aktivasi perangkat dengan menekan tombol **AKTIVASI**.

  <img src="https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/activation_2.png" alt="room_activation_step_2" loading="lazy" width="360px" />

  Setelah anda menekan tombol **AKTIVASI**, tunggu hingga sistem selesai melakukan aktivasi ruangan dan terjadi perubahan pada status dan perangkat RFID ruangan. Secara default, status ruangan akan berubah menjadi **TERSEDIA** dan perangkat RFID menjadi **SUDAH DIAKTIVASI**.

  Pada halaman rincian ruangan yang sudah diaktivasi, akan menampilkan informasi RFID dan juga kontrol jalur listrik dalam ruangan.

  <img src="https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/activation_4.png" alt="room_activation_step_4" loading="lazy" width="360px" />

  Apabila perangkat gagal dihubungi oleh sistem pada langkah sebelumnya, langkah selanjutnya adalah melakukan aktivasi perangkat secara fisik. Prosedur aktivasi fisik ini akan dijelaskan dalam **Aktivasi perangkat fisik** dalam dokumen ini.

### Permasalahan Umum Setelah Proses Aktivasi Ruangan

Setelah melakukan proses aktivasi, terkadang Anda akan menemui beberapa permasalahan dimana sistem gagal menghubungi perangkat yang berakibat pada keterbatasan dalam akses kontrol listrik dan informasi perangkat monitoring fisik seperti yang tampak pada gambar berikut:

<img src="https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/activation_3.png"
alt="room_activation_step_3" loading="lazy" width="360px" />

Permasalahan ini dapat disebabkan oleh beberapa faktor, antara lain:

#### Kesalahan Jaringan Pada Komputer

Kesalahan jaringan dapat menyebabkan kegagalan sistem dalam menghubungi perangkat. Untuk mengatasi ini, silahkan gunakan jaringan internet atau WiFi yang stabil untuk komputer anda.

#### Perangkat Montoring Fisik Gagal Terhubung Dengan WiFi

Kesalahan berikutnya adalah dimana perangkat monitoring fisik gagal untuk terhubung dengan jaringan WiFi dan menyebabkan perangkat berada dalam status **CONFIG MODE** atau mode konfigurasi. Beberapa faktor yang menyebabkan perangkat gagal terhubung dengan jaringan WiFi yaitu:

1. Kesalahan dalam memasukkan SSID dan kata sandi WiFi pada saat melakukan konfigurasi perangkat. SSID dan kata sandi yang dimasukkan harus menyesuaikan penulisannya dengan SSID dan kata sandi pemancar WiFi (Router), baik dengan huruf kapital atau huruf kecilnya. Kesalahan dalam memasukan data ini berakibat pada perangkat monitoring fisik gagal terhubung ke jaringan WiFi, sehingga tidak dapat mengirimkan data ke sistem dan membuat perangkat berada dalam **CONFIG MODE**. Untuk mengatasi permasalahan ini, cukup lakukan konfigurasi ulang perangkat dengan mengisikan SSID dan kata sandi WiFi yang benar.

2. Kesalahan dalam memasukkan nama ruangan pada saat melakukan konfigurasi. Hal ini berdampak pada pengiriman data ke sistem dan alamat ruangan yang salah. Untuk mengatasi permasalahan ini, cukup lakukan kondigurasi ulang perangkat monitoring fisik dan dengan menyesuaikan nama ruangan tujuan.

3. Perangkat monitoring fisik gagal terhubung ke jaringan WiFi. Beberapa faktor yang menyebabkan perangkat gagal terhubung ke jaringan wifi antara lain:

   - Versi WiFi yang tidak didukung sehingga perangkat monitoring fisik gagal untuk terhubung dengan jaringan. Perlu diperhatikan bahwa perangkat monitoring fisik hanya dapat terhubung dengan jaringan WiFi dengan frekuesn 2.4Ghz. Untuk mengatasi permasalahan ini, cukup dengan menggunakan frekuensi WiFi yang kompatibel dengan perangkat.

   - Jarak pemancar WiFi (Router) yang tidak terjangkau oleh perangkat. Setiap router WiFi memiliki kemampuan jarak pemancar yang beragam, sehingga untuk mengatasi permasalahan ini perlu mempertimbangkan jarak WiFi yang mampu dipancarkan oleh router.

4. Kerusakan pada komponen perangkat monitoring fisik. Perangkat monitoring fisik dapat mengalami kerusakan, sehingga pastikan untuk melakukan pengecekan berkala pada perangkat monitoring fisik.
