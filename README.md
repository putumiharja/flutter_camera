# Praktikum 1 Flutter Camera

Berikut hasil dari Latihan Flutter Camera

## 1. Take A Picture : 

![image alt](https://github.com/putumiharja/flutter_camera/blob/a8b5efc1b5427708adc270cc0c52c2c6766a044e/1.%20Proses%20pengambilan%20gambar.png)

## 2. Display The Picture :

![image alt](https://github.com/putumiharja/flutter_camera/blob/a8b5efc1b5427708adc270cc0c52c2c6766a044e/2.%20Hasil%20pengambilan%20gambar.png)


## Maksud void async pada praktikum 1

void → Menunjukkan bahwa fungsi main() tidak mengembalikan nilai apa pun.
async → Menandakan bahwa fungsi ini bersifat asinkron,sehingga dapat menggunakan await di dalamnya.

Mengapa async dibutuhkan?

Fungsi availableCameras() adalah operasi asinkron yang membutuhkan waktu untuk mendapatkan daftar kamera yang tersedia.
Dengan menggunakan await, kita memastikan bahwa daftar kamera diperoleh sebelum TakePictureScreen dipanggil.
