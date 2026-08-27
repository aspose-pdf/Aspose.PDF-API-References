---
title: "RichMediaAnnotation"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas yang menjelaskan RichMediaAnnotation yang memungkinkan penyematan data video/audio ke dalam dokumen PDF."
type: docs
weight: 710
url: /id/python-net/aspose.pdf.annotations/richmediaannotation/
---

## RichMediaAnnotation class

Kelas yang menjelaskan RichMediaAnnotation yang memungkinkan penyematan data video/audio ke dalam dokumen PDF.

Tipe RichMediaAnnotation mengungkapkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| RichMediaAnnotation(page, rect) | Menginisialisasi instance baru dari kelas RichMediaAnnotation |
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
| custom_player | Mengatur atau mengambil pemutar flash khusus untuk memutar data video/audio. |
| custom_flash_variables | Mengatur atau mengambil variabel flash yang diteruskan ke pemutar. |
| konten | Data dari konten Rich Media. |
| type | Mengambil atau mengatur tipe konten. Nilai yang mungkin: Audio, Video. |
| activate_on | Peristiwa yang mengaktifkan aplikasi. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| clone() | Mengkloning instance ini.<br/>            Metode virtual. Selalu mengembalikan null. |
| get_rectangle(consider_rotation) | Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman. |
| accept(visitor) | Menerima pengunjung untuk anotasi ini. |
| flatten() | Menempatkan konten anotasi langsung pada halaman,<br/>            objek anotasi akan dihapus. |
| change_after_resize(transform) | Memperbarui parameter dan tampilan, sesuai dengan transformasi matriks. |
| add_custom_data(name, data) | Menambahkan data bernama khusus (misalnya diperlukan untuk skrip flash). |
| set_content(file_name, audio) | Mengatur aliran konten. |
| set_poster(image_stream) | Mengatur poster anotasi. |
| update() | Memperbarui data dengan parameter yang ditentukan. |

### Lihat Juga

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

