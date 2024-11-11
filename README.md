# OOP_DIMASPUTRANUGROHO_2311103054

Sistem Manajemen Warnet

Proyek ini adalah simulasi sistem manajemen untuk sebuah warnet yang menyediakan berbagai jenis komputer untuk pelanggan: komputer reguler, komputer gaming, dan komputer premium dengan layanan tambahan.

Struktur Proyek

Proyek ini terdiri dari tiga kelas utama:
1. Komputer - Kelas dasar yang mewakili komputer reguler.
2. KomputerGame - Turunan dari Komputer yang menambahkan fitur khusus untuk komputer gaming.
3. KomputerDewa - Turunan dari Komputer yang menambahkan fitur untuk komputer premium dengan layanan ekstra.

Deskripsi Kelas

Kelas Komputer

- Atribut:
  - jumlahKomputer (int): Jumlah komputer yang tersedia.
  - namaWarnet (String): Nama warnet.
  - hargaPerJam (float): Biaya per jam untuk penggunaan komputer.

- Metode:
  - informasi(): Menampilkan informasi dasar tentang komputer.

### Kelas KomputerGame (extends Komputer)

- Atribut:
  - `vipCard (boolean): Menunjukkan apakah pengguna memiliki kartu VIP untuk mendapatkan manfaat gaming tambahan.

- Metode:
  - informasi(): Menampilkan informasi tentang komputer gaming.
  - login(String username)`: Mensimulasikan proses login untuk sesi gaming.
  - bermain(int jam)`: Mensimulasikan bermain game selama beberapa jam.
  - bermain(int jam, int menitTambahan)`: Mensimulasikan bermain game dengan tambahan menit.

Kelas KomputerDewa (extends Komputer)

- Atribut:
  - ruangPrivat (boolean): Menunjukkan apakah komputer berada di ruangan privat.

- Metode:
  - informasi(): Menampilkan informasi tentang komputer premium.
  - pesan(int nomorKomputer): Mengizinkan pengguna untuk memesan komputer tertentu.
  - tambahLayanan(String makanan): Menambahkan satu layanan makanan untuk pengguna.
  - tambahLayanan(String makanan, String minuman): Menambahkan layanan makanan dan minuman.

Cara Menjalankan Program

1. Kompilasi Proyek: Pastikan semua kelas berhasil dikompilasi.
2. Jalankan Kelas Utama: Kelas utama adalah OOP2311103054DIMASPUTRANUGROHO. Kelas ini membuat objek dari setiap tipe komputer dan memanggil berbagai metode untuk mendemonstrasikan fungsionalitasnya.

Di NetBeans, Anda dapat menjalankan proyek dengan memilih Run Project.

Persyaratan
- Java Development Kit (JDK) versi 8 atau lebih tinggi.
- IDE Java seperti NetBeans (opsional, untuk kemudahan kompilasi dan eksekusi).

Catatan

- Proyek ini mendemonstrasikan konsep inheritance (pewarisan) dan polymorphism (polimorfisme) melalui sistem manajemen sederhana untuk sebuah warnet.
- Setiap kelas menimpa (override) metode dari kelas induknya untuk menambahkan fungsionalitas khusus berdasarkan tipe komputer.

Penulis
- Dimas Putra Nugroho - NIM: 2311103054
