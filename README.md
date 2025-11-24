# Live Notes
**Nama    : Ajeng Maulida Puspita**
**NIM     : 362458302012**

Project ini merupakan hasil praktikum Mobile Programming yang bertujuan mengenalkan integrasi Flutter dengan Firebase, khususnya penggunaan Cloud Firestore sebagai database real-time. Aplikasi ini memungkinkan pengguna menambahkan, mengedit, dan menghapus catatan, lalu otomatis tersinkronisasi ke semua perangkat yang menjalankan aplikasi.

## Deskripsi Praktikum
Pada praktikum ini, mahasiswa diminta membangun aplikasi Flutter sederhana yang terhubung ke Firebase. Fokus utama adalah:
- Inisialisasi proyek Flutter dengan Firebase Core
- Membuat koleksi Firestore untuk menyimpan data catatan
- Menampilkan data menggunakan StreamBuilder (real-time listener)
- Menerapkan fitur Create, Read, Update, Delete (CRUD)
- Menguji sinkronisasi data pada dua device secara bersamaan

Melalui praktikum ini, mahasiswa memahami konsep reactive UI dan real-time database pada mobile apps.

## Tugas Praktikum
1. Update Feature: Tambahkan fitur edit. Ketika ListTile ditekan (onTap), munculkan formulir yang sudah terisi data lama, dan update data tersebut di Firebase menggunakan perintah .update().
2. Testing: Jalankan aplikasi di 2 device berbeda (Emulator HP Fisik atau 2 Emulator). Buktikan bahwa data tersinkronisasi secara otomatis

## Hasil

### 1. Aplikasi di dua device
<p align="center">
  <img src="https://github.com/user-attachments/assets/9dcbfa1a-7e51-4c3c-ad78-9bf2b2bb0233" width="300">
</p>

### 2. Proses tambah
<p align="center">
  <img src="https://github.com/user-attachments/assets/118176de-2f05-4457-887d-54c7f746c909" width="300">
</p>

### 3. Proses update
<p align="center">
  <img src="https://github.com/user-attachments/assets/33beb0ed-006b-4a50-b573-8afa5e5a21f2" width="300">
</p>

### 4. Proses delete
<p align="center">
  <img src="https://github.com/user-attachments/assets/fd45c33f-1fe8-428a-8508-286ceb790d02" width="300">
</p>
