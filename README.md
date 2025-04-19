# 1. Penjelasan Proyek Camera and Filter Application

## Penjelasan
Proyek ini bertujuan untuk menggunakan kamera dengan efek filter.

## Dependencies Yang Dipakai:
- camera: ^0.10.5+9
- image: ^4.1.7
- path_provider: ^2.1.5

## Komponen Utama:
1. **Camera Screen** = Menyediakan tampilan utama untuk menangkap gambar secara real-time menggunakan camera package.
2. **Image Filters** = Menerapkan berbagai filter pada gambar yang telah diambil.
3. **Real Time Preview Filter** = memungkinkan pengguna melihat efek filter secara langsung sebelum mengambil gambar.

## Dokumentasi

<img src="assets/images/dokumentasi-camera.gif" alt="Camera" width="300px">

# 2. Gabungkan hasil praktikum 1 dengan hasil praktikum 2 sehingga setelah melakukan pengambilan foto, dapat dibuat filter carouselnya!

# 3. Jelaskan maksud void async pada praktikum 1?
## Maksud void async pada praktikum 1 adalah untuk digunakan agar kita bisa menangani operasi kamera secara asinkron tanpa mengganggu alur program utama.

# 4. Jelaskan fungsi dari anotasi @immutable dan @override ?

#### @immutable
@immutable adalah anotasi yang menandakan bahwa sebuah class tidak dapat diubah (immutable) setelah dibuat. contohnya  imutable yaitu untuk widget, Ini bantuin performance dan bikin pengelolahan mudah diprediksi.

#### @override
@override menandakan bahwa method tersebut menimpa (override) method dari class parent/superclass.
