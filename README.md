# Job-2-Embedded
Jobsheet 2 embedded system  PROTOKOL KOMUNIKASI DAN SENSOR


Percobaan a.  ESP32 Capacitive Touch Sensor

Memiliki bentuk rangkaian sebagai berikut,

<img width="234" alt="Percobaan a" src="https://user-images.githubusercontent.com/121158751/208879373-58bbe23a-3675-4701-a52f-ca35cd3d230a.png">

Langkah Kerja :

A. ESP32 Capacitive Touch Sensor

1. Hubungkan kabel jumper Male-to-Female pada Pin D4 ESP32.

2. Buka Arduino IDE dan upload script program berikut ke ESP32.

3. Buka serial monitor untuk melihat raw data. Ubah tampilan serial monitor 
menjadi Serial Plotter pada menu Tools > Serial Plotter. 

4. Sentuh ujung kabel jumper dan amati yang terjadi, kemudian dokumentasikan 
hasilnya.

5. Buatlah rangkaian seperti di atas.

6. Buatlah program agar LED menyala ketika sensor disentuh, dan LED akan 
mati ketika sensor tidak disentuh.

7. Buatlah program agar ketika sensor disentuh, LED menyala Blink.

8. Buatlah program agar ketika LED menyala, maka pada Serial Monitor akan 
menampilkan angka yang akan bertambah setiap kali sensor disentuh.

9. Tambahkan 2 LED sehingga pada rangkaian terdapat 3 LED. Buatlah 
program agar ketika sensor disentuh, LED menyala menjadi running LED. 
Nyala running LED tersebut adalah bergerak dari kiri ke kanan, kemudian 
kanan ke kiri secara kontinyu

Hasil Percobaan :




https://user-images.githubusercontent.com/121158751/209138898-85547518-d286-499c-b541-742173831868.mp4




Berdasarkan hasl dari percobaan di atas, apabila sensor disentuh maka LED akan menyala blink dan mati apabila sensor tidak tersentuh

Percobaan b. Mengakses Sensor DHT 11 (Single Wire / BUS)

Langkah Kerja:

1. Buatlah rangkaian seperti pada Gambar di bawah ini.

<img width="257" alt="percobaan b" src="https://user-images.githubusercontent.com/121158751/208879478-abd0826e-1af3-47d3-bdab-9831c6194879.png">

2. Install library sensor DHT 11 melalui Sketch > Include Library > Manage 
Libraries. Ketikkan DHT pada kolom pencarian, pilih library yang akan 
diinstall seperti pada Gambar berikut ini. Kemudian install juga Adafruit 
Unified Sensor menggunakan cara yang sama.

3. Buatlah program seperti pada script di bawah ini untuk mengakses sensor 
DHT11. Kemudian upload program tersebut pada ESP32 dan 
dokumentasikan hasilnya. (sudah terlampir pada file)

4. Buatlah program agar ketika suhu rungan mencapai 30 derajat celcius, maka 
ESP32 akan menyalakan LED Merah dan buzzer secara beep (blink). Apabila 
suhu dibawah 30 derajat, ESP32 akan mematikan buzzer dan menyalakan 
LED berbentuk running LED seperti pada Percobaan A. Kemudian 
dokumentasikan hasilnya

Hasil Percobaan :



https://user-images.githubusercontent.com/121158751/208879543-be19bac2-c1a3-476e-8eb7-5019baef5d2e.mp4



Berdasarkan hasil percobaan di atas, percobaan ini menggunakan sensor suhu dan cara bekerjanya adalah ketika sensor suhu menangkap suhu
di atas 35 derajat celsius maka lampu led akan menyala berkedip.

Perobaan c.  Mengakses Sensor RFID (SPI Communication)

Memiliki bentuk rangkaian sebagai berikut,

<img width="395" alt="percobaan c" src="https://user-images.githubusercontent.com/121158751/208879598-304ccadb-5682-4ecd-a946-67244f2288dc.png">


Hasil Percobaan:


https://user-images.githubusercontent.com/121158751/208879635-2a115e1a-c3b1-4a97-8640-2042b1a9aa5b.mp4




Berdasarkan percobaan di atas, cara kerja dari percobaan ini adalah dengan menggunakan sensor dan kartu yang akan terdeteksi oleh sensor tersebut,
apabila sensor mendeteksi kartu maka pada serial monitor akan muncul pemberitahuan bahwa Akses diterima.
