# Penjelasan Class dan Method

1. Class NilaiMahasiswa
   - Tujuan: Class ini digunakan untuk menyimpan data mahasiswa dan mengelola operasinya.
   - Atribut:
     - self.data_mahasiswa: Dictionary yang menyimpan pasangan nama mahasiswa dan nilai mereka.
   - Method:
     - tambah(nama, nilai):
       - Menambahkan data baru ke dictionary.
       - Jika nama sudah ada, data akan langsung ditimpa.
     - tampilkan():
       - Menampilkan semua data mahasiswa.
       - Jika dictionary kosong, program memberi pesan bahwa tidak ada data.
     - hapus(nama):
       - Menghapus data berdasarkan nama.
       - Jika nama tidak ditemukan, pesan kesalahan akan ditampilkan.
     - ubah(nama, nilai_baru):
       - Memperbarui nilai mahasiswa berdasarkan nama.
       - Jika nama tidak ditemukan, pesan kesalahan akan ditampilkan.

# Cara Kerja Program

1. Menambahkan Data:
   - Ketika pengguna memanggil method tambah, nama dan nilai mahasiswa ditambahkan ke dictionary.
   - Contoh: 
     python
     app.tambah("Zico", 90)
     
     Output:
     
     Data zico dengan nilai 90 berhasil ditambahkan.
     

2. Menampilkan Data:
   - Method tampilkan akan menampilkan semua data mahasiswa dengan format yang rapi.
   - Contoh:
     python
     app.tampilkan()
     
     Output:
     
     Daftar Nilai Mahasiswa:
     - zico: 90
     - rizky: 85
     - febrian: 80
     

3. Menghapus Data:
   - Pengguna memanggil method hapus dengan memasukkan nama mahasiswa.
   - Jika nama ditemukan, data akan dihapus. Jika tidak, akan muncul pesan kesalahan.
   - Contoh:
     python
     app.hapus("febrian")
     
     Output:
     
     Data febrian berhasil dihapus.
     

4. Mengubah Data:
   - Pengguna memanggil method ubah dengan nama mahasiswa dan nilai baru.
   - Jika nama ditemukan, nilai akan diperbarui. Jika tidak, pesan kesalahan ditampilkan.
   - Contoh:
     python
     app.ubah("zico", 95)
     app.ubah("rizky", 90)
     
     Output:
     
     Data zico berhasil diubah menjadi 95.
     Data rizky berhasil diubah menjadi 90
     

5. Mengakhiri Program:
   - Program selesai setelah semua operasi dilakukan.
