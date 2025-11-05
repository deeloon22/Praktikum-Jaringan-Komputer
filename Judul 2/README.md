# Praktikum-Jaringan-Komputer
## 🧩 Cisco Networking Academy Lab 10.4.4  
## Build a Switch and Router Network  

### Deskripsi Singkat  
Lab ini merupakan bagian dari praktikum Jaringan Komputer dengan fokus pada **pembangunan jaringan menggunakan router dan switch**.  
Tujuan utamanya adalah mempraktikkan konfigurasi perangkat Cisco, penerapan **IPv4 dan IPv6**, serta **verifikasi konektivitas antar host** di jaringan yang dibangun.


### Tujuan Pembelajaran
1. Membangun topologi jaringan sesuai diagram yang diberikan.  
2. Mengonfigurasi **Router (R1)** dan **Switch (S1)** menggunakan perintah dasar Cisco IOS.  
3. Mengimplementasikan **IP Addressing** (IPv4 & IPv6).  
4. Mengaktifkan komunikasi antar subnet melalui **default gateway**.  
5. Melakukan **verifikasi konektivitas jaringan** menggunakan perintah `ping` dan `show`.  
6. Menampilkan informasi perangkat melalui berbagai perintah diagnostik.

### Topologi Jaringan Build a Switch and Router Network
<p align="center">
<img width="622" height="182" alt="image" src="https://github.com/user-attachments/assets/186776af-eb2a-457a-a8bb-13285cc9b101" />
</p>

### Konsep Utama
#### 🔹 Konfigurasi Router (R1)
- Menetapkan hostname, password, dan banner MOTD.  
- Menonaktifkan DNS lookup untuk menghindari kesalahan input.  
- Mengonfigurasi IPv4 & IPv6 pada interface `GigabitEthernet0/0/0` dan `GigabitEthernet0/0/1`.  

#### 🔹 Konfigurasi Switch (S1)
- Menetapkan hostname dan interface VLAN 1.  
- Mengatur IP Address serta default gateway.  
- Memastikan semua interface aktif (status up/up).  

#### 🔹 Konfigurasi PC
- Menetapkan alamat IP, subnet mask, dan default gateway.  
- Melakukan pengujian konektivitas antar PC menggunakan perintah `ping`.

### Verifikasi Koneksi
#### Ping antar PC
<p align="center">
<img width="427" height="191" alt="image" src="https://github.com/user-attachments/assets/14e017df-0920-43c6-9e00-c8b53c6ad481" />
</p>

