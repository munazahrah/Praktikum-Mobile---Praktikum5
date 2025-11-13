# Praktikum5

Project Modul 5 - Widget SizedBox, Spacer, dan Card

📖 Deskripsi

Project ini berfokus pada tiga widget penting untuk mengatur jarak dan tampilan elemen secara terorganisir: SizedBox, Spacer, dan Card.

Anda akan belajar perbedaan antara SizedBox (untuk jarak/ukuran tetap) dan Spacer (untuk jarak proporsional/fleksibel), serta cara menggunakan Card untuk membungkus informasi dalam sebuah panel yang rapi dengan bayangan dan sudut membulat.

🎯 Tujuan Utama Project

Memahami Fungsi: Mengerti kegunaan SizedBox, Spacer, dan Card.

Membedakan Jarak: Mampu membedakan kapan harus menggunakan SizedBox (jarak tetap) vs Spacer (jarak proporsional/fleksibel).

Membuat UI Card: Mampu membuat antarmuka (UI) sederhana menggunakan Card untuk menampilkan informasi seperti ikon, teks, dan tombol.

Layout Rapi: Menggabungkan ketiga widget untuk menghasilkan tata letak yang bersih dan elegan.

✅ Daftar Tugas (To-Do List)

Berikut adalah hal-hal yang harus Anda kerjakan berdasarkan modul:

Buat Project Baru:

[ ] Buat "New Flutter Project" dengan nama music_card.

Latihan Dasar (Sangat Disarankan):

[ ] Ikuti Percobaan 1 (SizedBox) dan Percobaan 2 (Spacer) dari modul untuk memahami perbedaan perilaku kedua widget ini.

Tugas Utama: Membuat UI Kartu Musik

[ ] Atur tema aplikasi Anda menjadi gelap di main.dart: theme: ThemeData.dark().

[ ] Buat AppBar dengan judul "Sedang memutar" dan atur agar posisinya di tengah (centerTitle: true).

[ ] Di dalam body, gunakan widget Center untuk menempatkan sebuah Card di tengah layar.

[ ] Atur properti Card:

elevation: 4 (untuk bayangan)

shape: RoundedRectangleBorder() (untuk sudut membulat)

padding: EdgeInsets.all(12) (untuk memberi jarak dalam)

[ ] Isi Card dengan elemen-elemen berikut:

Icon (sebagai cover album)

Text (sebagai Judul Lagu)

Text (sebagai Nama Artis)

Icon (sebagai tombol "Like", misal: Icons.favorite)

[ ] Atur Layout di dalam Card:

Gunakan SizedBox untuk memberi jarak tetap antar elemen (misal: antara Judul Lagu dan Nama Artis).

Gunakan Spacer untuk memberi jarak proporsional (fleksibel) agar tombol "Like" bisa terdorong ke sisi kanan.

(Petunjuk: Anda mungkin perlu membungkus elemen-elemen ini dalam Row atau Column).
