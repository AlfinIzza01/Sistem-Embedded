# JOBSHEET 3 - TOPOLOGI JARINGAN LOKAL DAN WIFI
## Tujuan
1) Mahasiswa dapat memahami cara kerja protokol topologi jaringan lokal 
yang memanfaatkan Wi-Fi untuk berkomunikasi.
2) Mahasiswa dapat merancang topologi jaringan yang memanfaatkan Wi-Fi 
untuk penerapan Wireless Sensor Network (WSN) dan Internet of Things 
(IoT).
3) Mahasiswa dapat memilih dan menggunakan topologi jaringan yang tepat 
sesuai dengan kondisi lapangan untuk penerapan WSN dan IoT.


## Dasar Teori
<p align="justify">Wireless Fidelity atau yang lebih awam kita sebut wifi adalah suatu teknologi 
yang menggunakan gelombang radio dalam rentang 2,4GHz sampai dengan 5GHz 
untuk menghubungkan perangkat seperti PC/laptop, smartphone, dan perangkat 
microcontroller seperti ESP32 dan ESP8266 ke jaringan lokal wireless untuk bisa 
mengakses internet. Untuk dapat melakukan akses internet tersebut,maka 
perangkat elektronik diatas perlu berada dalam satu titik akses atau hotspot 
jaringan nirkabel sehingga terhubung dengan wifi. Pada umumnya jaringan wifi 
dapat menjangkau hingga 20 meter didalam ruangan dan lebih dari 20 meter untuk 
di luar ruangan. Pada awal kemunculannya, wifi hanya digunakan sebagai 
perangkat nirkabel pada jaringan LAN (Local Area Network) akan tetapi karena 
pesatnya teknologi di zaman sekarang wifi menjadi kebutuhan sehari-hari untuk 
akses jaringan internet dan IoT.
Berbagai data yang kita minta atau kirimkan melalui wifi didistribusikan 
melalui gelombang radio di udara. Supaya data tersebut bisa terbaca maka harus 
ada yang namanya wireless adaptor yang menghubungkan ke wifi. Gelombang 
radio yang berwujud sinyal ini lalu dikirim menuju router yang fungsinya untuk 
memecahkan kode. Setelah terbaca maka data dikirim ke jaringan internet yang 
memanfaatkan koneksi ethernet. Karena jaringan wifi ini bekerja dua arah maka 
tiap data yang diterima dalam waktu yang sama menjadi kode pada tiap paket data 
lalu dikirim kembali dalam bentuk sinyal radio yang diterima adaptor komputer 
nirkabel</p>


**Sub-job** pada jobsheet ini, antara lain:
1. ESP32 Wi-Fi Modes dan Wifi-Scan
2. Menghubungkan ESP32 dengan Jaringan Wi-Fi
3. Menghubungkan Kembali (Re-connect) ESP32 dengan Jaringan Wi-Fi
4. Mengganti Hostname ESP32
5. Mengirim Data Sensor ke Database

## Alat dan Bahan
**Alat dan bahan** yang digunakan dalam jobsheet ini, antara lain:
1) ESP32
2) Breadboard
3) Kabel jumper
4) Sensor DHT 11, RFID
5) LED (5) dan Push Button (3)
6) Servo
7) Resistor 330,1K, 10K Ohm (@ 3)

 
> *Buka folder untuk melihat laporan*
