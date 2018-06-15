
# Weather Teller

> a program to tell the weather. the name says it all.

## A Little Bit about APIs
API atau _Application Programming Interface_ bisa dikatakan sebagai sebuah "cara" untuk suatu software untuk berinteraksi dengan berbagai macam hal lainnya. API juga bisa dikatakan sebagai suatu jembatan yang menghubungkan atau memungkinkan komunikasi antara dua pihak dengan suatu format yang terstandarisasi. Contohnya kita ingin untuk menggunakan _TwitterAPI_ untuk mengambil _tweets_ yang berada di Twitter untuk kita gunakan pada program kita. Yang TwitterAPI lakukan adalah ia akan menyediakan tweets tersebut, tetapi dalam bentuk yang berbeda dari yang biasa kita lihat di web. TwitterAPI akan memberikan informasi tersebut dalam bentuk tertentu (misal, JSON). Demikian jika kita melihat dari sisi seorang programmer. Dari sisi user, biasanya penggunaan API sudah dalam bentuk GUI (_Graphical User Interface_) yang sudah enak dilihat mata, misal aplikasi weather forecast yang biasa berada di _smartphone_ kita.

## OpenWeatherMap API
OpenWeatherMap API adalah sebuah API yang disediakan oleh openweathermap.org yang mengizinkan para developer untuk mengambil data cuaca yang disediakan. Data yang dapat diambil berupa:
 - Kondisi cuaca saat ini
 - Prediksi cuaca
 - Peta cuaca
 - UV Index
 - ... dan seterusnya.
 
## Package Structure
Package yang akan dibuat akan terbagi menjadi dua, yaitu package yang berguna untuk memunculkan tampilan ke user (a.k.a. user interface) dan package yang berguna untuk mengambil dan memproses data hingga bisa ditampilkan kepada user.

Berikut secara visual kira-kira strukturnya:
```
└───src
    └───main
        └───java
            ├───display
            └───weatherapi
```

## Checklist 
 - [ ] Membuat kelas untuk memanfaatkan OpenWeatherMap API agar dapat mengambil data
 - [ ] Menentukan informasi-informasi yang perlu ditampilkan kepada user
 - [ ] Membuat kelas untuk memproses data yang telah diambil menggunakan OpenWeatherMap API (sesuai dengan poin 2)
 - [ ] Menentukan/Mendesain struktur user interface
 - [ ] Membuat kelas-kelas untuk user interface
 - [ ] Menghubungkan data dengan user interface yang telah dibuat
 
 
