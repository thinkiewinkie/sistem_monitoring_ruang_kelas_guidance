### Konfigurasi Perangkat Fisik

Konfigurasi perangkat fisik adalah tahapan yang harus dilakukan untuk memaksimalkan fungsi sistem monitoring ruang kelas. Tujuan dari panduan ini adalah untuk memberikan informasi mengenai konfiruasi perangkat fisik seperti halnya mengakses pengaturan **ID Perangkat**, **SSID**, dan **Password**.

#### Ketentuan

Untuk mulai melakukan konfigurasi perangkat fisik, dibutuhkan beberapa perangkat tambahan seperti:

- Ponsel pintar
- Jaringan WiFi yang terhubung dengan internet.

Selain perangkat tambahan, terdapat beberapa ketentuan yang harus dipenuhi saat melakukan konfiguras, yaitu:

- Jaringan WiFi mendukung koneksi 2.4Hz
- Jaringan WiFi terproteksi dengan dengan tingkat keamanan 2 (WPA2)
- Rungan target sudah diaktivasi. (Silahkan lihat pada panduan aktivasi ruangan untuk mendaftarkan ID perangkat)

#### Langkah-langkah

- Antarmuka perangkat monitoring

  ![Antarmuka Perangkat](https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/device_interface.jpg)

  ![Adapter dan output listrik](https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/device_adapter.jpg)

  > Baca pada tabel keterangan dibawah untuk mengetahui komponen pada perangakat monitoring fisik.

  | Nomor | Komponen                                | Fungsi                                                                                          |
  | ----- | --------------------------------------- | ----------------------------------------------------------------------------------------------- |
  | 1     | LCD                                     | Menampilkan informasi ketersediaan ruangan, status akses ID Card, dan status aktivasi perangkat |
  | 2     | MCB                                     | Saklar listrik darurat                                                                          |
  | 3     | Posisi pembaca ID Card/Tag (RFID)       | Membaca ID Card/Tag pengguna                                                                    |
  | 4     | Stopkontak                              | Menyalurkan listrik untuk penggunaan dalam ruangan                                              |
  | 5     | AC Adapter/Adapter perangkat monitoring | Memberikan daya listrik ke komponen perangkat monitoring                                        |
  | 6     | Steker                                  | Memberikan daya untuk stopkontak                                                                |

- Menyalakan perangkat

  Untuk menyalakan perangkat, cukup dengan menghubungkan adapter perangkat dengan stopkontak yang dialiri listrik.

  > Komponen stopkontak dari perangkat monitoring tidak diperuntukkan sebagai sumber daya untuk perangkat fisik itu sendiri. Silahkan gunakan stopkontak yang sudah terinstalasi di ruangan dan juga memiliki arus listrik.

  Saat pertama kali dinyalakan, perangkat akan masuk kedalam mode konfigurasi, ditandai pada LCD yang bertuliskan **CONFIG MODE**.

  ![LCD perangkat dalam mode konfigurasi](https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/device_lcd_config.jpg)

- Menghubungkan ponsel ke perangkat fisik

  Dalam mode konfigurasi, perangkat akan memancarkan sinyal WiFi tersendiri dengan nama SSID `IoT_ITERA_AP`. Hubungkan ponsel dengan jaringan WiFi perangkat fisik yang meyala dengan menekan nama SSID perangkat.

  ![Access Point perangkat fisik](https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/device_ap.jpg)

- Login/Masuk ke perangkat monitoring

  Setelah ponsel terhubung dengan jaringan WiFi perangkat monitoring, akan muncul notifikasi yang meminta ponsel untuk melakukan login ke jaringan WiFi. Pada halaman login, pengguna akan diminta untuk memasukkan kredensial Username dan juga Password perangkat. Kredensial dapat dilihat pada sistem monitoring pada menu `Kredensial`. Silahkan masukkan kredensial kolom yang sesuai.

  > Demi keamanan, mohon kerjasama untuk tidak menyebarkan kredensial tersebut ke pihak manapun yang tidak memiliki kepentingan.

  ![Formulir login perangkat mointoring](https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/device_login_form.jpg)

  > Pada beberapa perangkat ponsel dan komputer, notifikasi permintaan login/masuk ke perangkat monitoring terkadang tidak muncul yang menyebabkan proses konfigurasi terhambat. Salah satu penyebab yang paling sering ditemui adalah akibat fitur kemanan ponsel yang memblokir notifikasi ini. Untuk mengatasinya, silahkan akses gateway perangkat monitoring melalui browser dengan memasukkan **`http://192.168.4.1`** pada kolom pencarian di browser.

- Konfigurasi ID Perangkat, SSID dan Password WiFi

  Konfigurasi perangkat, memerlukan aktivasi ruangan pada sistem monitoring ruang kelas sebelum nantinya perangkat dapat benar-benar memberikan informasi ruangan tujuan. Pastikan bahwa id perangkat telah terdaftar dan tercantum pada daftar perangkat monitoring di menu `Perangkat Monitoring`, id perangkat akan tertulis sebagai nama dari ruangan tujuan.

  ![ID perangkat teregistrasi](https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/device_monitoring.jpg)

  Setelah dipastikan ID Perangkat tercantum, anda dapat memasukkan ID perangkat, SSID dan Password wifi tujuan, dan menyimpan konfigurasi dengan menekan tombol submit.

  ![Konfigurasi perangkat monitoring](https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/device_config_form.jpg)

  Setelah konfigurasi disimpan, anda akan diarahkan pada halaman yang memberikan informasi bahwa proses konfigurasi berhasil yang memandakan bahwa proses konfigurasio telah selesai dilakukan.

  ![Konfigurasi disimpan](https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/device_config_done.jpg)

  Setelah proes konfigurasi selesai dan berhasil, perangkat monitoring akan secara otomatis memulai ulang. Pada LCD perangkat yang berhasil dikonfigurasi, lcd akan menampilkan informasi seperti nama ruangan dan juga status pemakaian saat ini.

  ![Konfigurasi disimpan](https://raw.githubusercontent.com/thinkiewinkie/sistem_monitoring_ruang_kelas_guidance/main/assets/images/device_lcd_active.jpg)

  > Jika proses konfigurasi gagal, LCD perangkat monitoring akan kembali masuk kedalam mode konfigurasi. Masalah ini umumnya disebabkan karena perangkat gagal terhubung dengan jaringan WiFi. Untuk mengatasi ini, pastikan bahwa jaringan WiFi sampai ke perangkat, atau lakukan konfigurasi ulang dengan memastikan SSID dan Password yang dimasukkan benar.
