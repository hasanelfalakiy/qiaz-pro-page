## v1.0 (1 Januari 2024)
- Rilis pertama
Fitur:
- Waktu sholat halaman depan dengan algoritma Irsyadul Murid
- Konversi tanggal Hijriyah - Masehi dan sebaliknya
- Konversi Julian Day ke Hijriyah dan Masehi
- Grafik visibilitas hilal 1 tahun
- Waktu sholat
- Hisab awal bulan Hijriyah
- dll 

## v2.0 (12 Januari 2024)
Fixs:

- Perbaikan UI
- Format jadwal waktu sholat halaman depan diubah menjadi HH:mm dengan pembulatan detik ke menit, jika detik sama atau lebih dari 30 detik
- Elevasi/tinggi tempat diatur ke 0 m, jika elevasi terdeteksi dibawah 0 (minus) dihalaman depan
- Tipe input pada TextFiled disesuaikan agar tidak terjadi potensi salah input tipe data yang bisa menyebabkan crash
Ketika tinggi hilal hakiki dibawah 0 (minus), data-data lain tidak perlu ditampilkan
- Perbaikan pada library lib-hisab-irsyadulmurid & lib-konversi

Additions:

- Penambahan fitur hisab gerhana bulan & gerhana matahari global