# LP5DPBO2025C1

## Janji
Saya Mochamad Zidan Rusdhiana dengan NIM 2305464 mengerjakan Latihan Praktikum 5 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Alur Program  

Program ini adalah aplikasi desktop berbasis Java yang menggunakan Swing untuk interface pengguna. Aplikasi ini dirancang untuk mengelola data mahasiswa, termasuk NIM, nama, jenis kelamin, dan atribut tambahan yaitu kelas dengan menggunakan radio button yang pilihannya adalah C1 atau C2.

### 1. Tampilan Utama  
Saat program dijalankan, pengguna akan melihat interface yang terdiri dari:  
- **Formulir input data**, mencakup NIM, nama, jenis kelamin, dan kelas.  
- **Tabel data mahasiswa**, yang menampilkan daftar mahasiswa yang telah dimasukkan.  
- **Tombol aksi**, yaitu:  
  - **"Add/Update"** – Menambah atau memperbarui data mahasiswa.  
  - **"Delete"** – Menghapus data mahasiswa yang dipilih. Terdapat Alert sebelum menghapus, untuk meminta konfirmasi ulang hapus data
  - **"Cancel"** – Mengosongkan formulir input.  

### 2. Pengelolaan Data Mahasiswa  
- **Menambahkan Data**  
  Pengguna mengisi formulir, memilih jenis kelamin, dan menentukan kelas (menggunakan tombol radio). Setelah itu, klik **"Add/Update"** untuk menyimpan data, yang kemudian akan muncul di tabel.  

- **Mengubah Data**  
  Pengguna dapat mengklik salah satu baris di tabel untuk memuat data ke dalam formulir. Setelah perubahan dilakukan, klik **"Add/Update"** untuk memperbarui data di tabel.  

- **Menghapus Data**  
  Pilih data yang ingin dihapus dari tabel, lalu tekan **"Delete"**. Data akan dihapus secara permanen.  

- **Membatalkan Input**  
  Klik **"Cancel"** untuk mengosongkan formulir tanpa menyimpan perubahan.  

### 3. Informasi Tabel  
- Tabel menampilkan semua data mahasiswa yang telah dimasukkan.  
- Klik salah satu baris di tabel untuk memuat data ke dalam formulir agar bisa diperbarui atau dihapus.  

### 4. Validasi dan Clear Formulir  
- Program memastikan data yang dimasukkan sesuai format sebelum ditambahkan ke tabel.  
- Setelah operasi (menambah, memperbarui, atau menghapus), formulir akan dikosongkan secara otomatis.  

### 5. Struktur Data  
- Data mahasiswa disimpan dalam struktur **`ArrayList`**, yang menyimpan objek **`Mahasiswa`**.  
- Tabel pada interface diperbarui secara dinamis berdasarkan data dalam **`ArrayList`**.  

## Dokumentasi
![Screenshot 2025-03-16 152904](https://github.com/user-attachments/assets/4e94b858-99b2-436f-930a-ac891c159dd3)
![Screenshot 2025-03-16 153157](https://github.com/user-attachments/assets/c3f5146c-a329-4eb2-9988-9c60b4e4e7d9)
![Screenshot 2025-03-16 153350](https://github.com/user-attachments/assets/4d50ed5d-1d40-42d4-a34e-85e4516cce44)
