# 🚀 ESP32 IoT Dashboard (AP + STA)

Sistem IoT berbasis **ESP32** untuk monitoring jarak menggunakan sensor **HC-SR04** dengan tampilan **web dashboard realtime**.

Menggunakan mode **Dual WiFi (AP + STA)** sehingga perangkat tetap bisa diakses meskipun WiFi utama tidak tersedia.

---

## ✨ Fitur

* 📡 Mode **AP + STA (Dual Mode)**
* 📏 Monitoring jarak realtime (cm)
* 📊 Grafik jarak realtime
* 🌐 Web dashboard (HP & PC)
* 🔄 Auto fallback koneksi

---

## 🌐 Mode Koneksi

* **STA (Station)**
  Terhubung ke WiFi rumah

* **AP (Access Point)**
  ESP32 membuat hotspot: **ESP32-Backup**

📌 Akses:

* STA → IP dari router
* AP → `192.168.4.1`

---

## 🧰 Komponen

* ESP32
* HC-SR04 Ultrasonic Sensor
* Breadboard
* Kabel jumper

---

## 📸 Preview

<div align="center">

<table>
<tr>
<th>AP Mode</th>
<th>STA Mode</th>
</tr>

<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/b199e974-2846-42eb-a276-96ff3322f5e4" width="250"><br>
<sub>Menggunakan koneksi AP</sub>
</td>

<td align="center">
<img src="https://github.com/user-attachments/assets/2db69c0f-8c28-45e6-9985-7c6468f9b2a8" width="250"><br>
<sub>Menggunakan koneksi STA</sub>
</td>
</tr>

<tr>
<td align="center">
<img src="https://github.com/user-attachments/assets/032b5beb-4f2d-4150-965a-34ae51700ec7" width="250"><br>
<sub>Hasil koneksi AP</sub>
</td>

<td align="center">
<img src="https://github.com/user-attachments/assets/c87ca217-c565-4d86-a0ab-d79446535517" width="250"><br>
<sub>Hasil koneksi STA</sub>
</td>
</tr>

</table>

</div>

---

## ⚡ Keunggulan

* Fleksibel (bisa online & offline)
* Tidak tergantung satu jaringan
* Monitoring realtime via web

---

## 👨‍💻 Author

**Hema**
