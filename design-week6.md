# Fitur Filter Pencarian Lowongan  

Kelompok 3 :
- Aisyah Alimah Lesmono 1251420002
- Aura Alifia Maulana 1251420004
- Khansa Dayana 1251420129

## 1. Pencarian Lowongan

Fitur ini memungkinkan pengguna untuk menyaring daftar lowongan
berdasarkan kriteria tertentu agar dapat menemukan lowongan yang
sesuai dengan kebutuhan dan preferensi pengguna.

## 2. Kebutuhan

- Mahasiswa dapat melihat daftar lowongan yang tersedia.
- Mahasiswa dapat memfilter lowongan berdasarkan lokasi.
- Mahasiswa dapat memfilter lowongan berdasarkan bidang pekerjaan.
- Mahasiswa dapat memfilter lowongan berdasarkan periode magang.
- Mahasiswa dapat menggunakan lebih dari satu filter secara bersamaan.
- Sistem menampilkan lowongan yang sesuai dengan filter yang dipilih.
- Sistem menampilkan informasi bahwa lowongan tidak ditemukan jika
  tidak terdapat lowongan yang sesuai dengan kriteria.

## 3. Asumsi

- Setiap lowongan memiliki informasi lokasi, bidang pekerjaan,
  dan periode magang.
- Pengguna dapat memilih satu atau beberapa kriteria filter.
- Filter yang tidak dipilih tidak digunakan sebagai kriteria pencarian.
- Data lowongan tersimpan di dalam database.
- Pengguna tidak harus login untuk menggunakan fitur pencarian
  dan filter lowongan.

## 4. Keputusan Desain

### 4.1 Kombinasi Beberapa Filter

Sistem memungkinkan pengguna menggunakan beberapa filter
secara bersamaan.

Penggunaan beberapa filter membantu pengguna mempersempit
hasil pencarian sehingga lowongan yang ditampilkan lebih
sesuai dengan kebutuhan mereka.

### 4.2 Filter Menggunakan Data Terstruktur

Sistem menggunakan atribut yang telah ditentukan pada data
lowongan, seperti lokasi, bidang pekerjaan, dan periode magang.

Data yang terstruktur membuat proses filtering lebih konsisten
dan memudahkan sistem mencocokkan lowongan dengan kriteria
yang dipilih pengguna.
