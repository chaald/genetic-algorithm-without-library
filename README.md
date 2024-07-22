# genetic-algorithm-without-library
Proyek ini mengimplementasikan Algoritma Genetika (GA) dari awal untuk menyelesaikan masalah optimasi tanpa bergantung pada library eksternal.

## Deskripsi Proyek

Proyek ini adalah tugas akhir untuk mata kuliah Kecerdasan Buatan. Tujuannya adalah mengimplementasikan Algoritma Genetika (GA) dari awal untuk menyelesaikan masalah optimasi tanpa bergantung pada library eksternal. GA digunakan untuk menemukan solusi optimal untuk suatu fungsi matematis menggunakan populasi solusi potensial. Algoritma ini mencakup komponen kunci seperti inisialisasi, seleksi, crossover, mutasi, dan penggantian.

## Fitur
- Inisialisasi: Menghasilkan populasi awal dari kromosom biner.
- Perhitungan Fitness: Mengevaluasi fitness kromosom berdasarkan fungsi matematis khusus.
- Seleksi: Menggunakan seleksi turnamen untuk memilih orang tua bagi generasi berikutnya.
- Crossover: Menerapkan crossover satu titik untuk menghasilkan keturunan dari orang tua.
- Mutasi: Memutasi kromosom dengan probabilitas tertentu untuk mempertahankan keragaman.
- Seleksi Survivor: Memilih individu terbaik untuk membentuk generasi berikutnya.

## Daftar Isi
- Penggunaan
- Detail Algoritma
	- Inisialisasi
	- Fungsi Fitness
	- Seleksi
	- Crossover
	- Mutasi
 	- Seleksi Survivor
- Hasil

## Penggunaan
1. Simpan kode yang disediakan ke dalam sebuah file.
2. Jalankan kode tersebut.

## Detail Algoritma
- Inisialisasi: Algoritma dimulai dengan menginisialisasi populasi kromosom biner. Setiap kromosom mewakili solusi potensial dalam ruang pencarian.
- Fungsi Fitness: Fitness setiap kromosom dievaluasi menggunakan fungsi matematis. Tujuannya adalah meminimalkan fungsi ini, sehingga fitness didefinisikan sebagai kebalikan dari nilai fungsi.
- Seleksi: Seleksi turnamen digunakan untuk memilih orang tua bagi generasi berikutnya. Sebuah subset individu dipilih secara acak, dan individu terbaik dalam subset ini dipilih sebagai orang tua.
- Crossover: Crossover satu titik diterapkan untuk membuat keturunan dari dua kromosom orang tua. Titik crossover dipilih secara acak, dan materi genetik dipertukarkan antara orang tua.
- Mutasi: Mutasi dilakukan pada keturunan dengan probabilitas tertentu untuk memperkenalkan keragaman genetik. Setiap bit dalam kromosom memiliki kemungkinan untuk dibalik.
- Seleksi Survivor: Generasi baru kromosom dibentuk dengan memilih individu terbaik dari populasi gabungan orang tua dan keturunan.

## Hasil

Skrip mencetak nilai fitness dari kromosom terbaik yang ditemukan, bersama dengan nilai x1 dan x2 yang sesuai. Hasil menunjukkan solusi terbaik yang ditemukan setelah menjalankan algoritma genetika selama jumlah generasi yang ditentukan.
