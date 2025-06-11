# API-SEDERHANA
Ini adalah sebuah coding project API sederhana yang di bangun menggunakan PHP native, yang di gunakan untuk mengelola database pengguna, API ini sudah mendukung metode CRUD (Crate, Read, Update, Delete).
Project ini menggunakan software [Postman](https://www.postman.com) untuk menggunakan API nya dan menggunakan database dari Phpmyadmin. Metode yang tersedia yaitu `GET`, `POST`, `PUT`, `DELETE` dengan **endpoint** `/users`, Penggunaan metodenya sebagai beriku:

#Penggunaan Metode

1. Metode `GET`
   - Endpoint `/users`
   - Contoh URL nya `http://localhost/dbapi/index.php?path=users`
  ![Screenshot 2025-06-11 230554](https://github.com/user-attachments/assets/cc545d7b-7095-4ca2-abd9-ab3e2e8c2435)

2. Metode `POST`
   - Endpoint `/users`
   - Contoh URL nya `http://localhost/dbapi/index.php?path=users`
   - Pada bagian key tambah opsi yang ingin di `POST` atau bisa di coba seperti di gambar
![Screenshot 2025-06-11 230859](https://github.com/user-attachments/assets/064f7ff0-f629-41f7-b950-afb6d767aac5)
Maka pada database phpmyadmin akan ada informasi user baru seperi di gambar
![Screenshot 2025-06-11 230918](https://github.com/user-attachments/assets/7edd17bd-87ef-4a0a-9ff6-4c7e617413fe)

3. Metode `PUT` 
   - Endpoint `/Users/id database`
   - Contoh URL nya `http://localhost/dbapi/index.php?path=users/7`
   - Pada bagian Key tambahkan name dan password untuk meng-update informasi dari id user 7 seperti di gambar
     ![Screenshot 2025-06-11 231142](https://github.com/user-attachments/assets/a26ff12a-b142-4c49-b0bf-33448d94d173)
Maka database name dan email pada id 7 akan berubah seperti di gambar
![Screenshot 2025-06-11 231153](https://github.com/user-attachments/assets/13955e68-c246-4110-a248-cc169fd29071)

4. Metode `DELETE`
   - Endpoint `/users/7`
   - Contoh URL nya `http://localhost/dbapi/index.php?path=users/7`
   - Pada key nya di masukkan id dari id user di database seperti di gambar
     ![Screenshot 2025-06-11 231142](https://github.com/user-attachments/assets/98559885-9e44-43ca-8fca-87c8833fa5a7)
     Maka database id nomor 7 akan terhapus sesuai dengan metode post nya seperti yang ada di gambar
     
