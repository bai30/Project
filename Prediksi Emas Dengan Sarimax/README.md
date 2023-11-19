#Prediksi Tren Emas dengan Sarimax

ini adalah project pertama saya dengan menggunakan ilmu Data Science. Dalam project kali ini saya memakai data harga emas selama 5 tahun di Yahoo Finance sehingga harga emas pada project ini berupa US Dolar.
![image](https://github.com/bai30/project/assets/149948184/7b7f08d1-0a41-4edc-88c3-9011ac5e5351)
dalam beberapa hari terakhir, tren harga emas cenderung turun. tujuan project ini adalah memprediksi tren harga emas 3 bulan kedepan.
pada dataset ini terdapat 1258 baris, saya membuat data menjadi weekly agar baris data tidak terlalu banyak dan tidak terlalu sedikit, baris pada data menjadi 261.
kolom yang saya pakai adalah kolom close, yaitu harga penutupan emas di tiap harinya. Dalam 261 data ini, saya menggunakan data training sebanyak 196 baris dan data test sebanyak 65.
algoritma yang saya pakai adalah sarimax dengan parameter sebagai berikut:
order = (2,1,2)
seasonal_orde r= (1,1,2,4)
![image](https://github.com/bai30/project/assets/149948184/8cbbc6a2-e131-4ab7-9930-74249b052b38)
