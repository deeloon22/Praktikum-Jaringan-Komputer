# Praktikum-Jaringan-Komputer
## 🧩 Cisco Networking Academy Lab 10.4.4  
## 🖧 Packet Tracer - Configure VLANs, Trunking, and Inter-VLAN Routing (Physical Mode)
### Link Video Youtube https://youtu.be/khDp5U2y_jw

### Deskripsi Singkat  
Proyek ini merupakan hasil praktikum Jaringan Komputer yang berfokus pada pembuatan dan konfigurasi VLAN, trunking, serta inter-VLAN routing menggunakan Cisco Packet Tracer (Physical Mode).Tujuannya adalah untuk memahami bagaimana pembagian jaringan menggunakan VLAN dapat meningkatkan keamanan, efisiensi, dan pengelolaan jaringan, serta bagaimana router dapat digunakan untuk menghubungkan antar VLAN.


### Tujuan Pembelajaran
1. Membangun topologi jaringan dengan dua switch, satu router, dan empat PC.
2. Mengonfigurasi VLAN dan port access pada masing-masing switch.
3. Mengaktifkan trunking (802.1Q) antar switch dan antara switch–router.
4. Menerapkan inter-VLAN routing (Router-on-a-Stick) agar host dari VLAN berbeda bisa saling berkomunikasi.
5. Melakukan pengujian konektivitas antar perangkat untuk memastikan jaringan berfungsi dengan benar.

### Topologi Jaringan 
<p align="center">
<img width="663" height="297" alt="image" src="https://github.com/user-attachments/assets/2ef2142b-0dba-4bd0-a03f-93dbd79d2fe8" />
</p>

#### Analisis dan Pembahasan
1. VLAN berfungsi membagi jaringan besar menjadi beberapa domain broadcast kecil agar lebih aman dan efisien.
2. Trunking (802.1Q) memungkinkan beberapa VLAN berjalan di satu kabel antar perangkat.
3. Router-on-a-Stick memungkinkan router menangani lalu lintas antar VLAN menggunakan sub-interface.

#### Manfaat utama VLAN dan trunking:
1. Keamanan meningkat karena memisahkan jaringan antar departemen.
2. Manajemen lebih mudah dan fleksibel.
3. Kinerja jaringan meningkat dengan domain broadcast yang lebih kecil.
