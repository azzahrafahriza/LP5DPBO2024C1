# LP5DPBO2024C1

## Janji
Saya Azzahra Fahriza Fitriani dengan NIM 2102296 mengerjakan Latihan Praktikum 5 dalam mata kuliah DPBO untuk keberkahan-Nya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Desain 
terdapat dua kelas utama pada program ini

### Class Mahasiswa 
Kelas ini merepresentasikan entitas mahasiswa dalam sistem. Setiap objek Mahasiswa memiliki atribut seperti NIM, nama, jenis kelamin, dan asal kota. Kelas ini juga menyediakan metode setter dan getter untuk mengakses dan mengubah nilai atribut.

### Class Menu 
Kelas ini adalah kelas utama yang mengatur tampilan utama aplikasi dan berinteraksi dengan pengguna. Kelas ini memiliki fungsi main sebagai entry point aplikasi. Kelas ini juga bertanggung jawab untuk membuat antarmuka pengguna menggunakan Java Swing, termasuk tombol, tabel, dan field input. Selain itu, kelas ini mengatur aliran data antara GUI dan kelas lainnya. Berikut beberapa fungsi yang ada dalam kelas ini 
- insertData(): merupakan fungsi yang bertugas menambahkan data mahasiswa ke dalam tabel.
- updateData(): adalah metode yang mengubah data yang telah ada dalam tabel.
- deleteData(): berperan dalam menghapus satu baris data dari tabel.
- clearForm(): bertugas untuk mengosongkan isian pada formulir tabel kembali menjadi kosong.

## Alur
1. Inisialisasi GUI -> Program membangun antarmuka pengguna menggunakan Java Swing. Ini mencakup elemen-elemen seperti tabel, tombol, dan field input.
2. Populasi Data Awal -> Sebuah metode populateList() dipanggil untuk mengisi list mahasiswa dengan data awal. Data mahasiswa diinisialisasi dengan nilai-nilai tertentu.
3. Pengaturan Tabel -> Metode setTable() digunakan untuk mengatur model tabel dengan data dari list mahasiswa. Ini dilakukan untuk menampilkan data mahasiswa di dalam tabel.
4. Interaksi Pengguna -> Terdapat interaksi antara pengguna dan aplikasi, yaitu:
  - Pengguna dapat menambahkan data mahasiswa baru atau memperbarui data mahasiswa yang sudah ada melalui tombol "Add/Update".
  - Pengguna juga dapat menghapus data mahasiswa yang dipilih melalui tombol "Delete".
  - Saat pengguna mengklik baris tabel, data mahasiswa dari baris tersebut akan ditampilkan di field input untuk diedit atau dihapus.
  - Tombol "Cancel" digunakan untuk menghapus isian di field input.
5. Manajemen Data -> Aplikasi melakukan manajemen data mahasiswa dengan melakukan hal-hal berikut:
  - Menambahkan data mahasiswa baru ke dalam list.
  - Memperbarui data mahasiswa yang sudah ada di list.
  - Menghapus data mahasiswa dari list.
6. Konfirmasi Penghapusan -> Sebelum menghapus data mahasiswa, aplikasi akan menampilkan dialog konfirmasi untuk memastikan bahwa pengguna benar-benar ingin menghapus data tersebut.
