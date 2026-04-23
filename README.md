# SISTEM-TAKE-OFF-LANDING
Sistem take off landing drone yang menggunakan 2 metode untuk identifikasi lokasi landing pad yaitu, Aruco dan CSI. Aruco di identifikasi melalui kamera dari drone memanfaatkan YOLO dan machine learning untuk mencari aruco marker dan juga menghitung jarak. Lalu, CSI yang memanfaatkan koneksi ESP-NOW untuk memetakan lokasi landing pad, dilihat dari pantulan gelombang pada landing pad. Digunakan Aruco, untuk memanfaatkan kamera dari drone, dan digunakan CSI karena sifatnya yang ringan dan realtime sehingga proses pemetaan tidak memberatkan daya terbang dari drone Tello. 
![Drone](Hardware.png)
![CSI](csi_image.png)
![CSI_ruangan](Visualisasi_csi_plotting_ruangan.png)
![CSI_tracking](Visualisasi_csi_long_log_terbang.png)
![Penempatan](PENEMPATAN_DRONE)

Kelemahan: drone bisa tiba tiba mati karena faktor lingkungan, seperti cahaya, jaringan, dll. CSI bisa tabrakan antar COM sehingga perlu build ulang kode.
