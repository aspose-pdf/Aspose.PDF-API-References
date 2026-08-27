---
title: "PDF3DAnnotation"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas PDF3DAnnotation. Kelas ini tidak dapat diwarisi."
type: docs
weight: 510
url: /id/python-net/aspose.pdf.annotations/pdf3dannotation/
---

## PDF3DAnnotation class

Kelas PDF3DAnnotation. Kelas ini tidak dapat diwarisi.

Tipe PDF3DAnnotation menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PDF3DAnnotation(page, rect, pdf_3d_artwork) | Menginisialisasi instance baru dari kelas PDF3DAnnotation |
| PDF3DAnnotation(page, rect, pdf_3d_artwork, activation) | Menginisialisasi instance baru dari kelas PDF3DAnnotation |
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
| pdf_3d_artwork | Mendapatkan 3D Artwork. |
| lighting_scheme | Mendapatkan skema pencahayaan. |
| konten | Mendapatkan atau mengatur konten. |
| render_mode | Mendapatkan mode render. |
| view_array | Mendapatkan array tampilan. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| set_image_preview(filename) | Mengatur pratinjau gambar. |
| set_image_preview(image) | Mengatur pratinjau gambar. |
| clone() | Mengkloning instance ini.<br/>            Metode virtual. Selalu mengembalikan null. |
| get_rectangle(consider_rotation) | Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman. |
| accept(visitor) | Menerima pengunjung untuk pemrosesan anotasi. |
| flatten() | Menempatkan konten anotasi langsung pada halaman,<br/>            objek anotasi akan dihapus. |
| change_after_resize(transform) | Memperbarui parameter dan tampilan, sesuai dengan transformasi matriks. |
| set_default_view_index(index) | Mengatur indeks tampilan default. |
| clear_image_preview() | Menghapus pratinjau gambar. |
| get_image_preview() | Mendapatkan pratinjau gambar. |

### Lihat Juga

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

