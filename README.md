# Praktikum-8

Kode di atas adalah contoh dari aplikasi berbasis Java yang memanfaatkan konsep MVC (Model-View-Controller) untuk mengelola data mahasiswa. Berikut adalah penjelasan detail dari masing-masing bagian program:
Penjelasan Struktur Program
1.	Database
•	Kelas Database bertanggung jawab untuk menangani koneksi ke database.
•	Metode getConnection() dalam kelas ini mengembalikan objek Connection yang akan digunakan untuk interaksi dengan database.
2.	MahasiswaModel (Model)
•	Kelas ini mewakili lapisan model dari MVC, yang menangani logika bisnis dan manipulasi data.
•	Dalam konteks ini, MahasiswaModel berisi metode untuk melakukan operasi CRUD (Create, Read, Update, Delete) pada tabel mahasiswa di database.
3.	FormMahasiswa (View)
•	Kelas ini berfungsi sebagai antarmuka pengguna (UI), di mana pengguna dapat berinteraksi dengan aplikasi.
•	Contohnya, FormMahasiswa dapat berupa form dengan input untuk nama, NIM, atau tombol untuk menyimpan, mengedit, dan menghapus data mahasiswa.
4.	MahasiswaController (Controller)
•	Kelas ini bertindak sebagai penghubung antara View dan Model.
•	Fungsi utama:
	Mendengarkan tindakan pengguna di FormMahasiswa.
	Menginstruksikan MahasiswaModel untuk memproses data sesuai permintaan.
	Memperbarui tampilan di FormMahasiswa berdasarkan data dari MahasiswaModel.
5.	Main
•	Kelas ini adalah entry point dari aplikasi.
Fungsi main() bertanggung jawab untuk:
	Membuat koneksi ke database.
	Menginisialisasi objek Model, View, dan Controller.
	Menjalankan aplikasi dengan membuat antarmuka pengguna terlihat.

