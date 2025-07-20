### Sistem Peringatan Banjir

Alat ini bekerja dengan memanfaatkan sensor water level dan sensor ultrasonik untuk mendeteksi ketinggian air. Data dari senso, kemudian dikirimkan secara nirkabel ke ESP32 menggunakan modul NRF24L01. ESP32, yang terhubung ke internet via WiFi, menerima data tersebut dan mengirimkan notifikasi ke pengguna melalui Telegram jika ketinggian air melebihi batas tertentu. 
