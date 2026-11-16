# myportfolio_mobile

### Tugas 7

1. Widget Tree adalah suatu deskripsi struktur hierarki objek-objek dalam flutter bersifat immutable. Dalam widget Tree terdapat induk yang berperan sebagai container dan child yang dirender suatu induk.

2. Sejauh ini, dalam proyek ini terdapat widget MyApp, MyHomePage, InfoCard & ItemCard. MyApp berperan sebagai widget root yang menjadi induk tertinggi yang merender MyHomePage. Dalam MyHomePage terdapat children nya yaitu InfoCard yang merender kartu informasi seperti nama dan NPM, lalu terakhir terdapat ItemCard yang merender berbagai button seperti Tambah Proyek, Lihat Proyek, Logout, dll.

3. MaterialApp merupakan widget yang mengkonfigurasi semua setting utama dari aplikasi flutter seperti tema warna, arah teks, rute, dll.

4. Widget dapat dibagi menjadi Stateful & Stateless Widget. Secara umum wdiget bersifat immutable sehingga tidak dapat diubah kecuali melakukan build yang baru. Bedanya Stateless Widget dengan Stateful Widget adalah Stateful Widget memiliki objek state yang dapat diubah di luar build sehingga sebaiknya dipakai ketika memerlukan suatu tampilan dinamis yang dapat berubah saat kode sudah running

5. BuildContext merupakan elemen sendiri widget tersebut yang di-pass ke build() method dari widget yang memiliki pointer terhadap induknya sehingga jika dalam metode build() tersebut memerlukan informasi dari widget induknya maka tinggal menggunakan variabel BuildContext yang di pass dalam build() nya.

6. Hot reload merupakan suatu cara untuk memperbarui aplikasi flutter kita dengan meng-scan jika ada pergantian kode, mengcompile ulang file-file yang terdeteksi perubahan, mengirim file baru tersebut ke VM Flutter yang running yang lalu merge dengan kode yang sudah ada. Pada hot reload state object tidak diubah sehingga perubahan2 yang kita buat pada stateful widget ketika running akan tetap tersimpan. Hot restart sedangkan merupakan cara memperbarui aplikasi dimana seluruh Element tree digantikan, setiap objek state dihancurkan, lalu ngebuild seluruh kode dari awal .

Penggunaan AI:
Deepseek digunakan dalam pengerjaan tugas untuk lebih memahami kode.

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
