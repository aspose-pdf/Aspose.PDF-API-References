---
title: "TextSearchOptions"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili opsi pencarian teks"
type: docs
weight: 460
url: /id/python-net/aspose.pdf.text/textsearchoptions/
---

## TextSearchOptions class

Mewakili opsi pencarian teks

Tipe TextSearchOptions menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| TextSearchOptions(is_regular_expression_used) | Menginisialisasi instance baru dari kelas TextSearchOptions |
| TextSearchOptions(rectangle) | Menginisialisasi instance baru dari kelas TextSearchOptions |
| TextSearchOptions(rectangle, is_regular_expression_used) | Menginisialisasi instance baru dari kelas TextSearchOptions |
## Properti
| Nama | Deskripsi |
| :- | :- |
| is_regular_expression_used | Mendapatkan atau mengatur indikasi bahwa ekspresi reguler digunakan. |
| limit_to_page_bounds | Mendapatkan atau mengatur indikasi bahwa teks dicari dalam batas halaman. |
| rectangle | Mendapatkan atau mengatur persegi panjang yang membatasi teks yang dicari. |
| use_font_engine_encoding | Mendapatkan atau mengatur indikasi bahwa teks akan dicari menggunakan enkoding mesin font.<br/>            true - berarti enkoding mesin font akan digunakan (coba ini jika pencarian teks gagal karena enkoding yang tidak sempurna dalam dokumen)<br/>            false - berarti enkoding font dokumen akan digunakan (nilai default) |
| ignore_shadow_text | Mendapatkan atau mengatur indikasi bahwa fragmen teks yang mewakili bayangan teks normal akan diabaikan selama pencarian.<br/>            true - berarti teks bayangan tidak akan ditemukan (coba ini jika pencarian teks mengembalikan fragmen duplikat pada posisi yang berdekatan)<br/>            false - berarti teks bayangan akan ditemukan bersama teks normal (nilai default) |
| log_text_extraction_errors | Mendapatkan atau mengatur indikasi bahwa kesalahan ekstraksi teks (dekoding) akan dicatat dalam penyerap teks (fragmen).<br/>            true - berarti kesalahan ekstraksi teks (dekoding) akan dicatat. Hal ini dapat menurunkan kinerja.<br/>            false (default) - tidak ada pencatatan kesalahan. |
| ignore_resource_font_errors | Mendapatkan atau mengatur indikasi bahwa kesalahan yang terkait dengan tidak adanya font akan diabaikan oleh penyerap teks (fragmen).<br/>            true - berarti bahwa kesalahan tidak adanya font akan diabaikan. Segmen teks yang merujuk ke sumber yang tidak tepat akan dilewati selama pemrosesan.<br/>            false (default) - kesalahan tidak adanya font akan menghentikan pemrosesan dengan melemparkan pengecualian. |
| search_for_text_related_graphics | Mendapatkan atau mengatur nilai yang memungkinkan pencarian grafik terkait teks (garis bawah, latar belakang, dll.) selama pencarian teks.<br/>            true - pencarian grafik terkait teks akan dilakukan (nilai default).<br/>            false - elemen grafis yang mungkin ada dalam dokumen sumber akan diabaikan. Atur ini jika terdapat masalah kinerja atau tidak perlu menangani garis bawah, latar belakang, atau pemotongan. |
| stored_graphic_elements_max_count | Mendapatkan atau mengatur nilai yang membatasi pencarian grafik terkait teks (garis bawah, latar belakang, dll.) pada sebuah halaman untuk jumlah elemen yang ditentukan.<br/>            Nilai default adalah 250. Tetapkan nilai yang lebih kecil jika ada masalah kinerja, coba nilai yang lebih besar jika beberapa elemen grafis tidak ditemukan. |
| search_in_annotations | Mendapatkan atau mengatur nilai yang memungkinkan pencarian teks dalam Anotasi.<br/>            true - teks akan dicari dalam Anotasi.<br/>            false - teks dalam Anotasi tidak akan diparsing oleh TextFragmentAbsorber. |

### Lihat Juga

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

