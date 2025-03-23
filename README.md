# TP4DPBO2025C1

Saya Yazid Madarizel dengan NIM 2305328 mengerjakan soal TP 4 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

---

### **Desain Program**  

##### **Struktur Kelas**  
- **Kelas Mahasiswa**: Model yang merepresentasikan data mahasiswa  
  - **Atribut**: `nim` (NIM mahasiswa), `nama` (nama mahasiswa), `jenisKelamin` (jenis kelamin), `jurusan` (jurusan)  
  - **Metode**: Getter dan setter untuk semua atribut  

- **Kelas Menu**: Kelas utama yang mengelola tampilan antarmuka dan logika program  
  - **Atribut**: Komponen UI, `listMahasiswa` (ArrayList untuk menyimpan data mahasiswa)  
  - **Metode**: Operasi CRUD, manajemen tabel, dan event handling  

##### **Komponen Antarmuka Pengguna**  
- JFrame utama yang berisi:  
  - Form input data mahasiswa  
  - Tombol untuk tambah/perbarui, hapus, dan batal  
  - Tabel untuk menampilkan daftar mahasiswa  
  - Combo box untuk memilih jenis kelamin dan jurusan  

---

### **Alur Program**  

#### **1. Inisialisasi Aplikasi**  
1. Membuat instance kelas `Menu`  
2. Mengatur properti jendela (ukuran, posisi, dll.)  
3. Menginisialisasi `listMahasiswa` untuk menyimpan data mahasiswa  
4. Menambahkan data awal mahasiswa
5. 
6. Menginisialisasi komponen UI  
7. Menyiapkan event listener untuk tombol dan tabel  
8. Menampilkan jendela utama  

#### **2. Operasi Manajemen Data**  

##### **Tambah Data Mahasiswa**  
1. Pengguna mengisi form input mahasiswa  
2. Pengguna menekan tombol **Tambah**  
3. Sistem memvalidasi input:  
   - Jika ada data kosong, tampilkan pesan kesalahan  
   - Jika valid, lanjutkan proses  
4. Sistem membuat objek `Mahasiswa` dengan data yang dimasukkan  
5. Objek `Mahasiswa` ditambahkan ke `listMahasiswa`  
6. Sistem memperbarui tampilan tabel  
7. Sistem mengosongkan form input  
8. Sistem menampilkan pesan sukses  

##### **Tampilkan Data Mahasiswa**  
1. Sistem menampilkan daftar mahasiswa dari `listMahasiswa` ke tabel  
2. Pengguna dapat melihat semua data mahasiswa tanpa interaksi tambahan  

##### **Perbarui Data Mahasiswa**  
1. Pengguna memilih baris mahasiswa dari tabel  
2. Sistem menampilkan data mahasiswa pada form input  
3. Sistem mengubah tombol **Tambah** menjadi **Perbarui**  
4. Sistem menampilkan tombol **Hapus**  
5. Pengguna mengubah data pada form input  
6. Pengguna menekan tombol **Perbarui**  
7. Sistem memvalidasi input:  
   - Jika ada data kosong, tampilkan pesan kesalahan  
   - Jika valid, lanjutkan proses  
8. Sistem memperbarui objek `Mahasiswa` di `listMahasiswa`  
9. Sistem memperbarui tampilan tabel  
10. Sistem mengosongkan form input  
11. Sistem menampilkan pesan sukses  

##### **Hapus Data Mahasiswa**  
1. Pengguna memilih baris mahasiswa dari tabel  
2. Sistem menampilkan data mahasiswa pada form input  
3. Sistem menampilkan tombol **Hapus**  
4. Pengguna menekan tombol **Hapus**  
5. Sistem menampilkan dialog konfirmasi:  
   - Jika pengguna mengonfirmasi, lanjutkan proses  
   - Jika tidak, batalkan operasi  
6. Sistem menghapus objek `Mahasiswa` dari `listMahasiswa`  
7. Sistem memperbarui tampilan tabel  
8. Sistem mengosongkan form input  
9. Sistem menampilkan pesan sukses  

##### **Batalkan Operasi**  
1. Pengguna menekan tombol **Batal**  
2. Sistem mengosongkan form input  
3. Sistem mengembalikan tombol **Perbarui** menjadi **Tambah**  
4. Sistem menyembunyikan tombol **Hapus**

---

### **Dokumentasi Program**  

![desain form](https://github.com/user-attachments/assets/99f7c02b-17b9-44fb-a1bb-c129e3d6116f)

![data berhasil ditambah](https://github.com/user-attachments/assets/cd14c36c-c241-438c-93ce-40b69c96f359)

![tambah data](https://github.com/user-attachments/assets/7f054fbc-a59e-4e02-878e-4de398f64c56)

![update data](https://github.com/user-attachments/assets/b4cff311-4998-4bb5-b676-6aa192bc652a)

![data berhasil diubah](https://github.com/user-attachments/assets/fd3cf41c-8183-4f30-be3e-88ca6a896d52)



![data berhasil dihapus](https://github.com/user-attachments/assets/b5da68bc-fc5d-4523-b9aa-1e5b43e2d30f)

![error semua field harus diisi](https://github.com/user-attachments/assets/ff02b63d-b930-4f37-b1b7-6784ddc852ba)


