# Electric Remote-Controlled Boat System
![electrical](/images/electrical.jpg)
## Deskripsi
Sistem ini adalah perancangan kapal yang dikendalikan menggunakan remote control dengan sumber tenaga listrik. Sistem ini memanfaatkan beberapa komponen utama untuk mengontrol pergerakan kapal dan memastikan kelancaran operasinya.

---

## Diagram Sistem
Sistem terdiri dari **9 komponen utama** yang saling terhubung untuk menjalankan fungsi penggerak dan kontrol kapal secara optimal.

---

## Komponen Utama

### 1. Battery
- Sumber daya listrik utama untuk seluruh sistem.  
- Memberikan daya ke **Boost/Buck Converter** untuk menyesuaikan kebutuhan tegangan komponen lainnya.

### 2. Boost/Buck Converter
- Mengatur tegangan dari baterai agar stabil dan sesuai dengan kebutuhan masing-masing komponen, seperti ESC dan Receiver.

### 3. ESC (Electronic Speed Controller)
- Mengontrol kecepatan dan arah motor BLDC berdasarkan sinyal dari Receiver.  
- Berfungsi sebagai penghubung antara motor BLDC dan sistem kontrol.

### 4. BLDC Motor
- Mengubah energi listrik menjadi energi mekanik untuk menggerakkan **Propeller**.

### 5. Propeller
- Menghasilkan gaya dorong untuk menggerakkan kapal maju atau mundur di air.  
- Diputar oleh **BLDC Motor**.

### 6. Receiver
- Menerima sinyal kontrol dari **Remote/Transmitter** dan meneruskannya ke **ESC** dan **Servo**.  
- Menjadi penghubung antara pengguna dan komponen kapal.

### 7. Remote/Transmitter
- Perangkat pengendali jarak jauh yang mengirimkan perintah ke **Receiver** untuk mengatur kecepatan dan arah kapal.

### 8. Servo
- Mengontrol posisi **Rudder** berdasarkan sinyal dari **Receiver**.  
- Memungkinkan kapal untuk berbelok ke kiri atau kanan.

### 9. Rudder
- Berfungsi sebagai kemudi untuk mengatur arah kapal.  
- Posisi **Rudder** dikontrol oleh **Servo**.

---

## Alur Kerja Sistem

### 1. Penyediaan Daya
- **Battery** menyediakan daya ke seluruh sistem.
- Tegangan distabilkan oleh **Boost/Buck Converter** untuk digunakan oleh komponen seperti **ESC** dan **Receiver**.

### 2. Pengendalian Jarak Jauh
- Pengguna menggunakan **Remote/Transmitter** untuk mengirimkan sinyal kontrol ke **Receiver**.

### 3. Distribusi Sinyal
- **Receiver** mendistribusikan sinyal ke:  
  - **ESC**, untuk mengatur kecepatan dan arah putaran **BLDC Motor**.  
  - **Servo**, untuk mengontrol posisi **Rudder**.

### 4. Pergerakan Kapal
- **ESC** mengatur putaran **BLDC Motor**, yang memutar **Propeller** untuk menggerakkan kapal.
- **Servo** mengatur orientasi **Rudder**, menentukan arah kapal.

### 5. Navigasi Kapal
- Kapal bergerak sesuai kombinasi kontrol pada **Propeller** dan **Rudder**, berdasarkan perintah dari **Remote/Transmitter**.

---

## Daftar Pustaka
Raharja, L. P. S., Darmawan, A., Kristio, P., & Nugroho, P. (2023). Rancang Bangun Prototipe Kapal Elektrik Dengan Sistem Kendali Jarak Jauh. *Jurnal Teknologi Terpadu, 11*(1), 1-xx. ISSN: 2338-6649.




# Remote-Controlled Fuel Engine Boat System
![fuel engine](/images/fuel.jpg)
## Deskripsi
Sistem ini adalah perancangan dan implementasi dari kapal berbahan bakar mesin yang dikendalikan secara jarak jauh menggunakan remote control. Kapal ini dilengkapi dengan berbagai komponen elektronik dan mekanik yang bekerja secara bersama-sama untuk memastikan kontrol yang baik.

---

## Diagram Sistem
Sistem ini terdiri dari **11 komponen utama**, yang masing-masing memiliki fungsi spesifik dalam mendukung operasi kapal.

---

## Komponen Utama

1. **Battery**
   - Menyediakan daya listrik untuk semua komponen elektronik, seperti receiver, servo, motor, dan lainnya.
   - Tegangan dari baterai dikendalikan agar sesuai kebutuhan dengan bantuan Boost/Buck Converter.

2. **Boost/Buck Converter**
   - Mengatur tegangan dari baterai agar stabil sesuai dengan kebutuhan masing-masing komponen elektronik, seperti Receiver dan Motor.

3. **Remote/Transmitter**
   - Mengirimkan sinyal kontrol dari pengguna ke kapal.
   - Sinyal ini mencakup perintah untuk mengatur gas mesin (**Linear Actuator**) dan arah kapal (**Servo**).

4. **Receiver**
   - Menerima sinyal dari **Remote/Transmitter**.
   - Mendistribusikan perintah ke:
     - **Servo**, untuk mengontrol **Rudder** (kemudi kapal).
     - **Linear Actuator**, untuk mengontrol gas pada mesin.

5. **Gas Tank**
   - Menyimpan bahan bakar yang disuplai ke **Fuel Engine**.
   - Memastikan mesin dapat bekerja terus-menerus selama bahan bakar tersedia.

6. **Propeller**
   - Mengubah tenaga mekanis dari **Fuel Engine** menjadi gaya dorong untuk menggerakkan kapal di atas air.

7. **Rudder**
   - Berfungsi sebagai kemudi untuk mengarahkan kapal.
   - Orientasi **Rudder** dikontrol oleh **Servo**, memungkinkan kapal berbelok ke kiri atau kanan.

8. **Servo**
   - Mengontrol posisi **Rudder**, yang menentukan arah kapal sesuai perintah dari remote control.

9.  **Linear Actuator**
    - Mengontrol gas pada kapal.
   

10. **Water Pump**
    - Berfungsi untuk memompa air, yang biasanya digunakan untuk sistem pendinginan mesin atau aplikasi lainnya.
    - Digunakan bersama **Motor**, yang menggerakkan pompa untuk menjaga aliran air yang stabil.

---

## Alur Kerja Sistem

1. **Battery** menyediakan daya ke seluruh sistem. Tegangan dari baterai distabilkan dengan **Boost/Buck Converter** sebelum dialirkan ke komponen lainnya.

2. Pengguna menggunakan **Remote/Transmitter** untuk mengirimkan sinyal kontrol ke **Receiver**.

3. **Receiver** menerima sinyal kontrol dari remote dan meneruskannya ke:
   - **Servo**, untuk mengontrol arah kapal melalui **Rudder**.
   - **Linear Actuator**, untuk mengatur gas pada supaya bisa berjalan.

4. **Propeller** menghasilkan gaya dorong yang memungkinkan kapal bergerak di atas air.

5. Arah kapal dikendalikan oleh **Rudder**, yang posisinya diatur oleh **Servo**, sesuai perintah dari remote.

6. Maju kapal diatur melalui **Linear Actuator**, yang mengontrol gas pada kapal.

7. **Water Pump**, digerakkan oleh **Motor**, memompa air yang dapat digunakan untuk sistem pendinginan mesin atau aplikasi lainnya.

---

## Daftar Pustaka

- Adwinda, E. G. (2024). RC Boat Fuel Engine. Tidak diterbitkan.

---

