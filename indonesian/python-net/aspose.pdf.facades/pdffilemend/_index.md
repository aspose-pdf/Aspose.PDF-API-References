---
title: "PdfFileMend"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili kelas untuk menambahkan teks dan gambar pada halaman dokumen PDF yang ada."
type: docs
weight: 280
url: /id/python-net/aspose.pdf.facades/pdffilemend/
---

## PdfFileMend class

Mewakili kelas untuk menambahkan teks dan gambar pada halaman dokumen PDF yang ada.

Tipe PdfFileMend menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfFileMend() | Konstruktor. |
| PdfFileMend(input_file_name, output_file_name) | Menginisialisasi instance baru dari kelas PdfFileMend |
| PdfFileMend(input_stream, output_stream) | Menginisialisasi instance baru dari kelas PdfFileMend |
| PdfFileMend(document) | Menginisialisasi instance baru dari kelas PdfFileMend |
| PdfFileMend(document, output_file_name) | Menginisialisasi instance baru dari kelas PdfFileMend |
| PdfFileMend(document, dest_stream) | Menginisialisasi instance baru dari kelas PdfFileMend |
## Properti
| Nama | Deskripsi |
| :- | :- |
| document | Mendapatkan facade dokumen yang sedang diproses. |
| input_stream | Mengatur aliran masukan. |
| output_stream | Mengatur aliran keluaran. |
| input_file | Mengatur berkas masukan. |
| output_file | Mengatur berkas keluaran. |
| wrap_mode | Mengatur atau mendapatkan algoritma pembungkus kata. Lihat WordWrapMode dan IsWordWrap. |
| text_positioning_mode | Mengatur atau mendapatkan strategi penempatan teks. [PositioningMode](/pdf/python-net/aspose.pdf.facades/positioningmode/)<br/>            Mode default adalah Legacy. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| bind_pdf(src_file) | Mengikat dokumen PDF untuk diedit. |
| bind_pdf(src_stream) | Mengikat dokumen PDF untuk diedit. |
| bind_pdf(src_doc) | Mengikat dokumen PDF untuk diedit. |
| save(dest_file) | Menyimpan dokumen PDF ke file yang ditentukan. |
| save(dest_stream) | Menyimpan dokumen PDF ke aliran yang ditentukan. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Menambahkan gambar ke halaman-halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Menambahkan gambar ke halaman-halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Menambahkan gambar ke halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Menambahkan gambar ke halaman-halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Menambahkan gambar ke halaman-halaman yang ditentukan dari dokumen PDF pada koordinat yang ditentukan. |
| add_text(text, page_num, lower_left_x, lower_left_y) | Belum diimplementasikan. |
| add_text(text, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Belum diimplementasikan. |
| add_text(text, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Belum diimplementasikan. |
| close() | Menutup objek PdfFileMend. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

