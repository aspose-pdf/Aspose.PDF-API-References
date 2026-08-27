---
title: "StampAnnotation"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili anotasi stempel karet. <br/>             Jenis anotasi ini menampilkan teks atau grafik yang dimaksudkan terlihat seolah-olah dicap pada halaman dengan stempel karet."
type: docs
weight: 790
url: /id/python-net/aspose.pdf.annotations/stampannotation/
---

## StampAnnotation class

Mewakili anotasi stempel karet. <br/>             Jenis anotasi ini menampilkan teks atau grafik yang dimaksudkan terlihat seolah-olah dicap pada halaman dengan stempel karet.

Tipe StampAnnotation menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| StampAnnotation(document) | Menginisialisasi instance baru dari kelas StampAnnotation |
| StampAnnotation(page, rect) | Menginisialisasi instance baru dari kelas StampAnnotation |
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
| title | Mendapatkan atau mengatur teks yang akan ditampilkan di bilah judul anotasi. |
| rich_text | Mendapatkan atau mengatur string teks kaya yang akan ditampilkan di jendela pop-up ketika anotasi dibuka. |
| creation_date | Mendapatkan tanggal dan waktu ketika anotasi dibuat. |
| subject | Mendapatkan teks yang mewakili deskripsi objek. |
| popup | Anotasi pop-up untuk memasukkan atau mengedit teks yang terkait dengan anotasi ini. |
| opasitas | Mendapatkan atau mengatur nilai opasitas konstan yang akan digunakan saat menggambar anotasi. |
| in_reply_to | Referensi ke anotasi yang menjadi "balasan" untuk anotasi ini.<br/>            Kedua anotasi harus berada pada halaman yang sama dalam dokumen. |
| reply_type | String yang menentukan hubungan ("tipe balasan") antara anotasi ini<br/>            dan yang ditentukan oleh InReplyTo. |
| icon | Mendapatkan atau mengatur ikon untuk stempel karet. |
| image | Mendapatkan atau mengatur gambar anotasi. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| clone() | None |
| get_rectangle(consider_rotation) | Mengembalikan persegi panjang anotasi dengan mempertimbangkan rotasi halaman. |
| accept(visitor) | Menerima pengunjung [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) saat menelusuri koleksi anotasi. |
| flatten() | Menempatkan konten anotasi langsung pada halaman,<br/>            objek anotasi akan dihapus. |
| change_after_resize(transform) | Memperbarui parameter dan tampilan, sesuai dengan transformasi matriks. |

### Lihat Juga

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

