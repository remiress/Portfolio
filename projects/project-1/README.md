### Sistem Monitoring Suhu dan Kelembaban

Alat ini bekerja dengan menggunakan sensor DHT11 untuk mendeteksi suhu di lingkungan sekitarnya. Data suhu yang diperoleh oleh sensor DHT11 dikirimkan ke ESP32 untuk diproses. Apabila suhu yang terdeteksi melebihi batas yang telah ditentukan, kipas akan secara otomatis diaktifkan untuk mendinginkan ruangan. Sistem ini menggunakan protokol MQTT untuk menghubungkan perangkat dengan lokal host, memungkinkan pengguna untuk memantau dan menampilkan data suhu secara real-time. 
