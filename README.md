# LP5DPBO2025C1

## Janji
Saya Mochamad Zidan Rusdhiana dengan NIM 2305464 mengerjakan Latihan Praktikum 5 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Alur Program
Program ini merupakan aplikasi desktop sederhana berbasis Java yang menggunakan Swing untuk antarmuka pengguna. Aplikasi ini dirancang untuk mengelola data mahasiswa, seperti NIM, nama, jenis kelamin, dan kelas. Berikut adalah alur kerja program ini:
1. **Tampilan Utama**
Saat program dijalankan, pengguna akan melihat antarmuka aplikasi yang terdiri dari beberapa komponen, yaitu:
    - Formulir input data (NIM, nama, jenis kelamin, dan kelas)
    - Tabel untuk menampilkan daftar mahasiswa
    - Tombol aksi seperti "Add/Update", "Delete", dan "Cancel"

2. **Pengelolaan Data Mahasiswa**
    - **Menambahkan Data**
Pengguna dapat mengisi formulir di bagian atas, memilih jenis kelamin, dan menentukan kelas mahasiswa (menggunakan tombol radio). Setelah semua data terisi, pengguna dapat mengklik tombol "Add/Update" untuk menyimpan data. Data yang dimasukkan akan ditampilkan dalam tabel.
    - **Mengubah Data**
Pengguna dapat mengklik salah satu baris data di tabel untuk memuat data tersebut ke dalam formulir. Setelah melakukan perubahan, pengguna dapat menekan tombol "Add/Update" untuk memperbarui data di tabel.
    - **Menghapus Data**
Pengguna dapat memilih baris data di tabel yang ingin dihapus, lalu menekan tombol "Delete". Data yang dipilih akan dihapus dari tabel.
    - **Membatalkan Input**
Untuk mengosongkan formulir tanpa menyimpan data, pengguna dapat menekan tombol "Cancel".

3. **Interaksi Tabel**
    - Tabel menampilkan semua data mahasiswa yang telah dimasukkan.
    - Saat pengguna mengklik salah satu baris di tabel, data pada baris tersebut dimuat ke dalam formulir untuk diperbarui atau dihapus.

4. **Validasi dan Pembersihan Formulir**
    - Program akan memastikan data yang dimasukkan memiliki format yang benar sebelum ditambahkan ke tabel.
    - Setelah melakukan operasi (menambah, memperbarui, atau menghapus), formulir akan dikosongkan secara otomatis.

5. **Struktur Data**
    - Data mahasiswa dikelola menggunakan struktur `ArrayList`, yang digunakan untuk menyimpan objek `Mahasiswa`.
    - Tabel pada antarmuka pengguna diperbarui secara dinamis berdasarkan data dalam `ArrayList`.

Program ini dirancang untuk memberikan pengguna fleksibilitas sekaligus kemudahan dalam mengelola daftar mahasiswa dengan antarmuka grafis yang sederhana.

## Dokumentasi
![Screenshot 2025-03-16 152904](https://github.com/user-attachments/assets/4e94b858-99b2-436f-930a-ac891c159dd3)
![Screenshot 2025-03-16 153157](https://github.com/user-attachments/assets/c3f5146c-a329-4eb2-9988-9c60b4e4e7d9)
![Screenshot 2025-03-16 153350](https://github.com/user-attachments/assets/4d50ed5d-1d40-42d4-a34e-85e4516cce44)
