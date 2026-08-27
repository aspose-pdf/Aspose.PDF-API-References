---
title: "MovieAnnotation"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Merepresentasikan anotasi film yang berisi grafik animasi dan suara yang akan ditampilkan di layar komputer dan melalui speaker. Ketika anotasi diaktifkan, film diputar."
type: docs
weight: 480
url: /id/python-net/aspose.pdf.annotations/movieannotation/
---

## MovieAnnotation class

Merepresentasikan anotasi film yang berisi grafik animasi dan suara yang akan ditampilkan di layar komputer dan melalui speaker. Ketika anotasi diaktifkan, film diputar.

Tipe MovieAnnotation menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| MovieAnnotation(document, movie_file) | Menginisialisasi sebuah instance baru dari kelas MovieAnnotation |
| MovieAnnotation(page, rect, movie_file) | Menginisialisasi sebuah instance baru dari kelas MovieAnnotation |
## Properti
| Nama | Deskripsi |
| :- | :- |
| vertical_alignment | Mendapatkan atau mengatur perataan vertikal paragraf |
| horizontal_alignment | Mendapatkan atau mengatur perataan teks untuk anotasi. |
| margin | Mendapatkan atau mengatur margin luar untuk paragraf (untuk pembuatan pdf) |
| is_first_paragraph_in_column | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya.<br/>            Defaultnya false. (untuk pembuatan pdf) |
| is_kept_with_next | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya.<br/>            Defaultnya false. (untuk pembuatan pdf) |
| is_in_new_page | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru.<br/>            Defaultnya false. (untuk pembuatan pdf) |
| is_in_line_paragraph | Mendapatkan atau mengatur apakah paragraf bersifat inline.<br/>            Defaultnya false. (untuk pembuatan pdf) |
| hyperlink | Mendapatkan atau mengatur hyperlink fragmen (untuk generator pdf). |
| z_index | Mendapatkan atau mengatur nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar <br/>            akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif <br/>            akan ditempatkan di belakang teks pada halaman. |
| perbarui_penampilan_saat_konversi | Jika true, tampilan anotasi akan diperbarui sebelum mengonversi dokumen PF menjadi gambar. Ini memungkinkan konversi bidang secara benar tetapi mungkin membutuhkan lebih banyak waktu. |
| gunakan_subset_font | Jika properti ini diatur ke true, font akan ditambahkan ke dokumen sebagai subset. Nilai default adalah true. |
| bendera | Bendera anotasi. |
| tipe_anotasi | Mendapatkan tipe anotasi. |
| lebar | Mendapatkan atau mengatur lebar anotasi. |
| aksi | Mendapatkan daftar tindakan anotasi. |
| tinggi | Mendapatkan atau mengatur tinggi anotasi. |
| rekt | Mendapatkan atau mengatur persegi panjang anotasi. |
| konten | Mendapatkan atau mengatur teks anotasi. |
| name | Mendapatkan atau mengatur nama anotasi pada halaman. |
| dimodifikasi | Mendapatkan atau mengatur tanggal dan waktu ketika anotasi terakhir dimodifikasi. |
| warna | Mendapatkan atau mengatur warna anotasi. |
| border | Mendapatkan atau mengatur karakteristik batas anotasi. [border](/pdf/python-net/aspose.pdf.annotations/annotation/) |
| status_aktif | Mendapatkan atau mengatur status tampilan anotasi saat ini. |
| karakteristik | Mendapatkan karakteristik anotasi. |
| status | Mendapatkan kamus tampilan anotasi. |
| perataan | Penjajaran anotasi. Properti ini sudah usang. Gunakan HorizontalAligment sebagai gantinya. |
| perataan_horizontal_teks | Mendapatkan atau mengatur perataan teks untuk anotasi. |
| nama_lengkap | Mendapatkan nama lengkap anotasi. |
| penampilan | Mendapatkan kamus tampilan anotasi. |
| indeks_halaman | Mendapatkan indeks halaman yang berisi anotasi. |
| title | Mendapatkan atau mengatur judul anotasi film. |
| file | Mendapatkan atau mengatur spesifikasi file yang mengidentifikasi file film yang dapat mendeskripsikan dirinya sendiri. |
| poster | Mendapatkan atau mengatur flag atau aliran yang menentukan apakah dan bagaimana gambar poster yang mewakili film akan ditampilkan. Jika true, gambar poster akan diambil dari file film; jika false, tidak ada poster yang akan ditampilkan. |
| aspect | Mendapatkan atau mengatur lebar dan tinggi kotak pembatas film, dalam piksel. |
| putar | Mendapatkan atau mengatur jumlah derajat di mana film akan diputar searah jarum jam relatif terhadap halaman. Nilainya harus kelipatan 90. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| clone() | Mengkloning instance ini.<br/>            Metode virtual. Selalu mengembalikan null. |
| get_rectangle(consider_rotation) | Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman. |
| accept(visitor) | Menerima objek pengunjung untuk memproses anotasi. |
| flatten() | Menempatkan konten anotasi langsung pada halaman,<br/>            objek anotasi akan dihapus. |
| change_after_resize(transform) | Memperbarui parameter dan tampilan, sesuai dengan transformasi matriks. |

### Lihat Juga

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

