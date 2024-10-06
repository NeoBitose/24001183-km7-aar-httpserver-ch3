
# Binar Car Rental + API for CRUD using Express.js

Aplikasi rental mobil ini dirancang untuk memudahkan proses pengelolaan armada mobil rental dengan menerapkan RESTful API sebagai antarmuka komunikasi antara server dan client. Dalam aplikasi ini, seluruh data mobil disimpan dalam format JSON, mencakup informasi penting seperti nama mobil, merek, harga sewa, ketersediaan, dan fitur-fitur lainnya. Penggunaan Express.js sebagai framework backend memungkinkan pengembang untuk membuat API yang efisien dan terstruktur, memfasilitasi operasi CRUD (Create, Read, Update, Delete) pada daftar mobil secara dinamis.

Dengan RESTful API, pengguna aplikasi dapat menambah mobil baru ke dalam daftar, melihat informasi lengkap mengenai mobil yang tersedia, memperbarui detail mobil jika ada perubahan, serta menghapus data mobil yang tidak lagi tersedia di armada. Arsitektur API yang digunakan memastikan bahwa aplikasi dapat diakses dan diintegrasikan dengan mudah oleh berbagai platform, menjadikannya fleksibel untuk digunakan baik oleh admin maupun pelanggan. Selain itu, penggunaan JavaScript di server-side dengan Node.js dan Express.js memberikan performa yang cepat dan responsif, menjaga pengalaman pengguna tetap optimal dalam mengelola data rental mobil.

## Daftar Isi

- [Tentang Proyek](#tentang-proyek)
- [Fitur](#fitur)
- [Instalasi](#instalasi)

## Tentang Proyek

1. Membuat project menggunakan NodeJS
2. Membuat server menggunakan HTML statis
3. Membuat server menggunakan JSON statis
4. Membuat RESTful API yang dapat digunakan untuk melakukan manajemen data mobil
   - Manajemen data mobil harus dapat dilakukan melalui REST API (Menggunakan Postman)
   - Manajemen data mobil meliputi aksi-aksi berikut : Endpoint tambah data mobil, Endpoint memodifikasi data mobil yang sudah ada, Endpoint Menghapus data mobil yang sudah ada, Endpoint Melihat daftar mobil yang tersedia (cukup dengan endpoint nya saja)
   - Dapat membuat sebuah HTTP Server dengan menggunakan HTTP Server dan Express.js.
     - HTTP Server harus bisa menyajikan data response dalam bentuk JSON
     - Untuk data response bisa menggunakan data arraynya saja. Referensi data ada pada link berikut.
     - Ketika ada request / maka server akan merespon dengan { message: “Ping successfully” }.
     - Ketika ada request list cars maka server akan merespon dengan array list mobil.
     - Ketika ada request detail cars maka server akan merespon dengan single data dari array mobil..
     - Ketika ada request create cars maka server akan merespon dengan array yang sudah terisi dengan data mobil yang baru.
     - Ketika ada request update cars maka server akan merespon dengan data yang sudah diupdate dari
array data mobil.
     - Ketika ada request delete cars maka server akan merespon dengan data yang sudah dihapus dari
array data mobil.
   - Dapat membuat sebuah HTTP Server sesuai dengan kaidah RESTful API.
     - Dapat membuat endpoint dengan HTTP Method yang sesuai.
     - Dapat membuat nama endpoint sesuai dengan kaidah RESTful.
     - Setiap request yang dijalankan harus menggunakan Postman.
     - Setiap request yang dijalankan tanpa adanya error.


## Fitur

**RESTful API untuk manajemen data mobil tanpa database** :
  - GET / akan membuka root endpoint dengan response
{message: “ping successfully”}
  - GET /cars akan membuka list cars
  - GET /cars/:id akan membuka satu data cars.
  - POST /cars akan mengembalikan response data cars yang sudah terbuat.
  - PUT /cars/:id akan mengembalikan response data cars yang sudah terupdate.
  - DELETE /cars/:id akan mengembalikan response data cars yang sudah terhapus.

## Instalasi

Ikuti langkah-langkah berikut untuk menginstal dan menjalankan aplikasi ini di komputer Anda:

1. **Download aplikasi Binar Rental Car**:
   - Clone repositori ini atau unduh file zip dari [https://github.com/NeoBitose/24001183-km7-aar-httpserver-ch3-.git](#).
   ```bash
   git clone https://github.com/NeoBitose/24001183-km7-aar-httpserver-ch3-.git
   ```

2. **Atur Konfigurasi Server pada folder server, pilih index.js**:
   - default server nanti nya akan berjalan di localhost port 3000.

3. **Jalankan perintah "npm install" pada terminal folder instalasi**:
   - buka terminal dan pastikan terinstall node js, kemudian jalankan perintah diatas.

4. **Jalankan perintah "npm run dev" atau "npm run start" pada terminal folder instalasi**:
   - setelah langkah sebelumnya dilakukan maka jalankan perintah diatas.

5. **Buka postman anda, dan explore fitur yang tersedia dalam aplikasi**:
   - Jelajahi berbagai fitur crud untuk file json dalam folder data.

