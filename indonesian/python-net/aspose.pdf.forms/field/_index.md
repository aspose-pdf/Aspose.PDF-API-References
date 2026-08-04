---
title: "Field"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas dasar untuk bidang formulir acro."
type: docs
weight: 90
url: /id/python-net/aspose.pdf.forms/field/
---

## Field class

Kelas dasar untuk bidang formulir acro.

Tipe Field menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| Field(doc) | Menginisialisasi sebuah instance baru dari kelas Field |
## Properti
| Nama | Deskripsi |
| :- | :- |
| vertical_alignment | None |
| horizontal_alignment | Mendapatkan atau mengatur perataan teks untuk anotasi. |
| margin | None |
| is_first_paragraph_in_column | None |
| is_kept_with_next | None |
| is_in_new_page | None |
| is_in_line_paragraph | None |
| hyperlink | None |
| z_index | None |
| perbarui_penampilan_saat_konversi | Jika true, tampilan anotasi akan diperbarui sebelum mengonversi dokumen PF menjadi gambar. Ini memungkinkan konversi bidang secara benar tetapi mungkin membutuhkan lebih banyak waktu. |
| gunakan_subset_font | Jika properti ini diatur ke true, font akan ditambahkan ke dokumen sebagai subset. Nilai default adalah true. |
| bendera | Bendera anotasi. |
| tipe_anotasi | Mendapatkan tipe anotasi. |
| lebar | Mendapatkan atau mengatur lebar anotasi. |
| aksi | Mendapatkan aksi anotasi. |
| tinggi | Mendapatkan atau mengatur tinggi anotasi. |
| rekt | Mendapatkan atau mengatur persegi bidang. |
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
| indeks_halaman | Mendapatkan indeks halaman yang berisi bidang ini. |
| saat_diaktifkan | Sebuah aksi yang akan dilakukan ketika anotasi diaktifkan. |
| highlighting | Mode penyorotan anotasi. |
| parent | Mendapatkan induk anotasi. |
| default_appearance | Mendapatkan atau mengatur tampilan default bidang. |
| read_only | Mendapatkan atau mengatur status hanya-baca bidang. |
| required | Mendapatkan atau mengatur status wajib bidang. |
| exportable | Mendapatkan atau mengatur flag dapat diekspor bidang. |
| partial_name | Mendapatkan atau mengatur nama parsial bidang. |
| alternate_name | Mendapatkan atau mengatur nama alternatif bidang (Sebuah bidang alternatif <br/>            nama yang akan digunakan menggantikan nama bidang sebenarnya <br/>            di mana pun bidang tersebut diidentifikasi dalam antarmuka pengguna).<br/>            Nama alternatif digunakan sebagai tooltip bidang di Adobe Acrobat. |
| mapping_name | Mendapatkan atau mengatur nama pemetaan bidang yang akan digunakan saat mengekspor data bidang formulir interaktif dari dokumen. |
| value | Mendapatkan atau mengatur nilai bidang. |
| is_synchronized | Mengembalikan true jika kamus tersinkronisasi. |
| sync_root | Objek sinkronisasi. |
| is_group | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah bidang ini bukan bidang terminal, yaitu grup bidang. |
| annotation_index | Mendapatkan atau mengatur indeks anotation ini pada halaman. |
| is_shared_field | Properti untuk dukungan Generator. Digunakan ketika bidang ditambahkan ke header atau footer. Jika true, bidang ini akan dibuat sekali dan tampilannya akan terlihat pada semua halaman dokumen. Jika false, bidang terpisah akan dibuat untuk setiap halaman dokumen. |
| fit_into_rectangle | Jika true, ukuran font akan diperkecil agar teks sesuai dengan persegi panjang yang ditentukan. |
| max_font_size | Ukuran font maksimum yang dapat digunakan untuk konten bidang. -1 untuk tidak memeriksa ukuran. |
| min_font_size | Ukuran font minimal yang dapat digunakan untuk konten bidang. -1 untuk tidak memeriksa ukuran. |
| tab_order | Mendapatkan atau mengatur urutan tab bidang. |
## Indexer
| Nama | Deskripsi |
| :- | :- |
| [index] | Mendapatkan subfield yang terdapat dalam bidang ini berdasarkan indeks. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| clone() | None |
| get_rectangle(consider_rotation) | Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman. |
| accept(visitor) | Menerima visitor. |
| flatten() | Menghapus bidang ini dan menempatkan nilainya langsung pada halaman. |
| change_after_resize(transform) | Memperbarui parameter dan tampilan, sesuai dengan transformasi matriks. |
| recalculate() | Menghitung ulang semua bidang yang dihitung pada formulir. |
| copy_to(array, index) | Menyalin subbidang dari bidang ini ke dalam array mulai dari indeks yang ditentukan. |
| set_position(point) | Atur posisi bidang. |

### Lihat Juga

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

