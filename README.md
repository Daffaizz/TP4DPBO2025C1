# Janji
Saya Daffa Faiz Restu Oktavian dengan NIM 2309013 mengerjakan Tugas Praktikum 3 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.
# Desain Program
<img src = "Desain Program.png">

# Alur Program
### Tampilan dan Interaksi
1. Menambahkan Data Mahasiswa
- Pengguna mengisi NIM, Nama, Jenis Kelamin, dan Program Studi.
- Klik tombol "Add", maka program akan:
    - Mengambil input dari pengguna.
    - Menambah data ke listMahasiswa.
    - Memperbarui tabel mahasiswa.
    - Membersihkan form input.
    - Menampilkan pesan "Data berhasil ditambahkan".
2. Memilih Data dari Tabel untuk Diedit atau Dihapus
- Pengguna memilih baris data di tabel.
- Data dari baris yang dipilih akan muncul di form input.
- Tombol "Add" berubah menjadi "Update".
- Tombol "Delete" menjadi terlihat.
3. Memperbarui Data Mahasiswa
- Setelah memilih data dari tabel, pengguna bisa mengubah informasi di form input.
- Klik tombol "Update", maka program akan:
    - Mengupdate data di listMahasiswa berdasarkan baris yang dipilih.
    - Memperbarui tabel mahasiswa.
    - Membersihkan form input.
    - Menampilkan pesan "Data berhasil diubah".
4. Menghapus Data Mahasiswa
- Setelah memilih data dari tabel, pengguna bisa mengklik tombol "Delete".
- Program akan menampilkan konfirmasi penghapusan melalui JOptionPane.      showConfirmDialog.
- Jika pengguna memilih "Yes", maka:
    - Data dihapus dari listMahasiswa.
    - Tabel diperbarui.
    - Form input dikosongkan.
    - Menampilkan pesan "Data berhasil dihapus".
- Jika memilih "No", penghapusan dibatalkan.
5. Membersihkan Form Input
- Jika pengguna mengklik tombol "Cancel", program akan:
    - Mengosongkan semua input (NIM, Nama, Jenis Kelamin, dan Program Studi).
    - Mengubah tombol "Update" kembali menjadi "Add".
    - Menyembunyikan tombol "Delete".
    - Mengembalikan selectedIndex ke -1 (tidak ada baris yang dipilih).
# Dokumentasi Program
<img src = "Dokumentasi/Screenshot 2025-03-19 222309.png">
<img src = "Dokumentasi/Screenshot 2025-03-19 222329.png">
<img src = "Dokumentasi/Screenshot 2025-03-19 222341.png">