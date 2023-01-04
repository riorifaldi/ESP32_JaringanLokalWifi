# ESP32_Wifi

Wireless Fidelity atau yang lebih awam kita sebut wifi adalah suatu teknologi yang menggunakan gelombang radio dalam rentang 2,4GHz sampai dengan 5GHz untuk menghubungkan perangkat seperti PC/laptop, smartphone, dan perangkat microcontroller seperti ESP32 dan ESP8266 ke jaringan lokal wireless untuk bisa mengakses internet. Untuk dapat melakukan akses internet tersebut,maka perangkat elektronik diatas perlu berada dalam satu titik akses atau hotspot jaringan nirkabel sehingga terhubung dengan wifi. Pada umumnya jaringan wifi dapat menjangkau hingga 20 meter didalam ruangan dan lebih dari 20 meter untuk di luar ruangan. Pada awal kemunculannya, wifi hanya digunakan sebagai perangkat nirkabel pada jaringan LAN (Local Area Network) akan tetapi karena pesatnya teknologi di zaman sekarang wifi menjadi kebutuhan sehari-hari untuk akses jaringan internet dan IoT.

**ALAT DAN BAHAN**
1) ESP32
2) Breadboard
3) Kabel jumper
4) Sensor DHT 11, RFID
5) LED (5) dan Push Button (3)
6) Servo
7) Resistor 330,1K, 10K Ohm (@ 3)

**HASIL PERCOBAAN** 

**A. ESP32 WiFi Modes dan WiFi Scan**

![hasil A_1](https://user-images.githubusercontent.com/118170084/209354866-0a3395a1-7a4e-4e47-8ea3-77757b7bd388.png)

Pada percobaan yang pertama mencoba untuk memeriksa apakah jaringan WiFi berada dalam jangkauan ESP32 kita. Untuk mengetahui jumlah jaringan yang ditemukan dengan fungsi `WiFi.scanNetworks()`


**B. Menghubungkan ESP32 Dengan Jaringan WiFi**

![hasil B_1](https://user-images.githubusercontent.com/118170084/209354913-8ea4848f-6ec6-4ba2-8656-a9d3f27706ea.png)

Pada percobaan ini, untuk menghubungkan ESP32 ke jaringan WiFi harus mengetahui SSID dan password-nya terlebih dahulu. Selanjutnya jaringan tersebut harus berada dalam jangkauan WiFi ESP32. Untuk menyambungkan ESP32 ke jaringan WiFi dengan fungsi `initWiFi()`


**C. Menghubungkan Kembali (Re-connect) ESP32 Dengan Jaringan WiFi**

![hasil C_1](https://user-images.githubusercontent.com/118170084/209355944-7872771d-05e4-4619-a6c9-cc606d33b6cb.png)

Pada percobaan ini mencoba untuk menghubungkan kembali (reconnect) WiFi setelah koneksi terputus dengan menggunakan fungsi `WiFi.reconnect()`


**D. Mengganti Hostname ESP32**

![hasil D_1](https://user-images.githubusercontent.com/118170084/209355981-cb045bac-eb0c-432b-9d12-23e15c5513b6.jpg)

**E. Mengirim Data Sensor ke Database**

![Output Send Sensor Data to Database](https://user-images.githubusercontent.com/118170084/209356666-4f67f38b-f860-4f61-825d-d62ad22c299b.jpg)
