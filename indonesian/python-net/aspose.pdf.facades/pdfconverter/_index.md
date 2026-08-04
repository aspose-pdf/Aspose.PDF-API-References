---
title: "PdfConverter"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili kelas untuk mengonversi setiap halaman file pdf menjadi gambar, kini mendukung BMP, JPEG, PNG, dan TIFF.<br/> Konten yang didukung dalam pdf berupa gambar, formulir, komentar."
type: docs
weight: 200
url: /id/python-net/aspose.pdf.facades/pdfconverter/
---

## PdfConverter class

Mewakili kelas untuk mengonversi setiap halaman file pdf menjadi gambar, kini mendukung BMP, JPEG, PNG, dan TIFF.<br/>            Konten yang didukung dalam pdf: gambar, formulir, komentar.

Tipe PdfConverter menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfConverter() | Menginisialisasi objek [PdfConverter](/pdf/python-net/aspose.pdf.facades/pdfconverter/) baru. |
| PdfConverter(document) | Menginisialisasi instance baru dari kelas PdfConverter |
## Properti
| Nama | Deskripsi |
| :- | :- |
| document | Mendapatkan facade dokumen yang sedang diproses. |
| coordinate_type | Mendapatkan atau mengatur tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| show_hidden_areas | Mendapatkan atau mengatur flag yang mengontrol visibilitas area tersembunyi pada halaman. |
| rendering_options | Mendapatkan atau mengatur opsi rendering. |
| form_presentation_mode | Mendapatkan atau mengatur mode presentasi formulir. |
| resolution | Mendapatkan atau mengatur resolusi selama konversi. Semakin tinggi resolusi, semakin lambat kecepatan konversi. Nilai default adalah 150. |
| start_page | Mendapatkan atau mengatur posisi awal yang ingin Anda konversi. Nilai minimum adalah 1. |
| end_page | Mendapatkan atau mengatur posisi akhir yang ingin Anda konversi. |
| password | Mendapatkan atau mengatur OwnerPassword dokumen. |
| user_password | Mendapatkan atau mengatur UserPassword dokumen. |
| page_count | Mendapatkan jumlah halaman. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| bind_pdf(input_file) | Mengikat file Pdf untuk konversi. |
| bind_pdf(input_stream) | Mengikat Stream Pdf untuk konversi. |
| bind_pdf(src_doc) | Menginisialisasi facade. |
| save_as_tiff(output_file) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF. |
| save_as_tiff(output_file, compression_type) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF. |
| save_as_tiff(output_file, image_width, image_height) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF. |
| save_as_tiff(output_file, page_size) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke satu file TIFF. |
| save_as_tiff(output_file, page_size, settings) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke satu file TIFF. |
| save_as_tiff(output_file, image_width, image_height, compression_type) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF. |
| save_as_tiff(output_file, image_width, image_height, settings) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF. |
| save_as_tiff(output_file, image_width, image_height, settings, converter) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF. |
| save_as_tiff(output_stream) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu stream TIFF ClassF. |
| save_as_tiff(output_stream, compression_type) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF. |
| save_as_tiff(output_stream, page_size) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu stream TIFF ClassF. |
| save_as_tiff(output_stream, page_size, settings) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke satu aliran TIFF. |
| save_as_tiff(output_stream, image_width, image_height) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu stream TIFF ClassF. |
| save_as_tiff(output_stream, image_width, image_height, compression_type) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu aliran TIFF. |
| save_as_tiff(output_stream, image_width, image_height, settings) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu aliran TIFF. |
| save_as_tiff(output_stream, image_width, image_height, settings, converter) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu aliran TIFF. |
| save_as_tiff(output_file, settings) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke satu file TIFF. |
| save_as_tiff(output_file, settings, converter) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF. |
| save_as_tiff(output_stream, settings) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke satu aliran TIFF. |
| save_as_tiff(output_stream, settings, converter) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu aliran TIFF. |
| save_as_tiff_class_f(output_file, image_width, image_height) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF ClassF. |
| save_as_tiff_class_f(output_file, page_size) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF ClassF. |
| save_as_tiff_class_f(output_stream, image_width, image_height) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu stream TIFF ClassF. |
| save_as_tiff_class_f(output_stream, page_size) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu stream TIFF ClassF. |
| save_as_tiff_class_f(output_file) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF ClassF. |
| save_as_tiff_class_f(output_stream) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu stream TIFF ClassF. |
| get_next_image(output_file) | Menyimpan gambar ke file dengan format gambar default - jpeg. |
| get_next_image(output_file, page_size) | Menyimpan gambar ke file dengan ukuran halaman ke-i yang diberikan dan format gambar default - jpeg. |
| get_next_image(output_file, format) | Menyimpan gambar ke file dengan format gambar yang diberikan. |
| get_next_image(output_file, page_size, format) | Menyimpan gambar ke file dengan ukuran halaman dan format gambar yang diberikan. |
| get_next_image(output_stream) | Menyimpan gambar ke stream dengan format gambar default - jpeg. |
| get_next_image(output_stream, page_size) | Menyimpan gambar ke stream dengan ukuran halaman yang diberikan. |
| get_next_image(output_stream, format) | Menyimpan gambar ke stream dengan format gambar yang diberikan. |
| get_next_image(output_stream, page_size, format) | Menyimpan gambar ke stream dengan ukuran halaman yang diberikan. |
| get_next_image(output_file, format, image_width, image_height, quality) | Menyimpan gambar ke file dengan format gambar, dimensi, dan kualitas yang diberikan. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Menyimpan gambar ke stream dengan format gambar, dimensi, dan kualitas yang diberikan. |
| get_next_image(output_file, format, image_width, image_height, quality) | Menyimpan gambar ke file dengan format gambar, ukuran gambar, dan kualitas yang diberikan. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Menyimpan gambar ke stream dengan format gambar, ukuran, dan kualitas yang diberikan. |
| get_next_image(output_file, format, image_width, image_height) | Menyimpan gambar ke file dengan format gambar, dimensi, dan kualitas yang diberikan. |
| get_next_image(output_stream, format, image_width, image_height) | Menyimpan gambar ke stream dengan format gambar, dimensi, dan kualitas yang diberikan. |
| get_next_image(output_stream, format, quality) | Menyimpan gambar ke stream dengan format gambar, dimensi, dan kualitas yang diberikan. |
| get_next_image(output_stream, page_size, format, quality) | Menyimpan gambar ke stream dengan ukuran halaman, format gambar, dan kualitas yang diberikan. |
| get_next_image(output_file, format, quality) | Menyimpan gambar ke file dengan format gambar, dimensi, dan kualitas yang diberikan. |
| get_next_image(output_file, page_size, format, quality) | Menyimpan gambar ke file dengan ukuran halaman, format gambar, dan kualitas yang diberikan. |
| close() | Tutup instance PdfConverter dan bebaskan sumber daya. |
| do_convert() | Lakukan beberapa pekerjaan awal untuk mengonversi dokumen pdf menjadi gambar. |
| has_next_image() | Menunjukkan apakah file pdf memiliki lebih banyak gambar atau tidak. |
| merge_images(input_images_streams, output_image_format, merge_mode, horizontal, vertical) | None |
| merge_images_as_tiff(input_images_streams) | Menggabungkan daftar aliran tiff menjadi satu aliran tiff dengan beberapa frame. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

