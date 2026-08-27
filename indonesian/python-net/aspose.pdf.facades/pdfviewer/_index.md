---
title: "PdfViewer"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili kelas untuk melihat atau mencetak PDF."
type: docs
weight: 370
url: /id/python-net/aspose.pdf.facades/pdfviewer/
---

## PdfViewer class

Mewakili kelas untuk melihat atau mencetak PDF.

Tipe PdfViewer menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfViewer() | Menginisialisasi objek [PdfViewer](/pdf/python-net/aspose.pdf.facades/pdfviewer/) baru. |
| PdfViewer(document) | Menginisialisasi sebuah instance baru dari kelas PdfViewer |
## Properti
| Nama | Deskripsi |
| :- | :- |
| show_hidden_areas | Mendapatkan atau mengatur flag yang mengontrol visibilitas area tersembunyi pada halaman. |
| print_status | Mendapatkan hasil pekerjaan pencetakan. Jika berhasil maka null; jika tidak, objek pengecualian. |
| use_intermidiate_image | Mendapatkan/mengatur penggunaan konversi halaman pdf menjadi file png intermidiate selama pencetakan dalam mode file. Gunakan ini ketika ukuran file output penting. |
| coordinate_type | Mendapatkan atau mengatur tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| print_as_image | Mengatur atau mendapatkan mode untuk PdfViewer mencetak sebagai gambar. |
| page_count | Mendapatkan jumlah halaman dari file Pdf saat ini. |
| password | Mendapatkan atau mengatur kata sandi dokumen input. |
| print_page_dialog | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah menghasilkan dialog nomor halaman saat mencetak. |
| print_as_grayscale | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah halaman dicetak dalam skala abu-abu. Secara default false. |
| printer_job_name | Mendapatkan atau mengatur nama dokumen dalam antrian printer ketika dokumen dicetak. Nilai default adalah nama file. |
| form_presentation_mode | Mendapatkan atau mengatur mode presentasi formulir. |
| rendering_options | Mendapatkan atau mengatur opsi rendering. |
| vertical_alignment | Mendapatkan atau mengatur nilai yang menunjukkan perataan vertikal |
| horizontal_alignment | Mendapatkan atau mengatur nilai yang menunjukkan perataan horizontal |
| auto_resize | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah file akan dicetak dengan ukuran yang dioptimalkan. |
| auto_rotate | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah file akan dicetak dengan rotasi otomatis |
| auto_rotate_mode | Mendapatkan atau mengatur nilai AutoRotateMode yang menunjukkan arah rotasi |
| resolution | Mendapatkan atau mengatur resolusi selama melihat dan mencetak. Semakin tinggi resolusi, semakin lambat kecepatan. Nilai default adalah 150. |
| scale_factor | Mendapatkan atau mengatur nilai titik mengambang yang menunjukkan faktor skala. Nilai default adalah 1.0. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| `print_large_pdf(file_path)` | Membuka dan mencetak file Pdf besar. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya <br/>             lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. |
| `print_large_pdf(input_stream)` | Membuka dan mencetak aliran Pdf besar. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya <br/>             lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. |
| `print_large_pdf(file_path, printer_settings)` | Membuka dan mencetak file Pdf besar dengan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan <br/>             halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. |
| `print_large_pdf(input_stream, printer_settings)` | Membuka dan mencetak aliran Pdf besar dengan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan <br/>             halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. |
| `print_large_pdf(file_path, page_settings, printer_settings)` | Membuka dan mencetak file Pdf besar dengan pengaturan halaman dan pengaturan printer yang ditentukan. Jika file Pdf <br/>             Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk <br/>             mendapatkan kinerja yang lebih baik. |
| `print_large_pdf(input_stream, page_settings, printer_settings)` | Membuka dan mencetak aliran Pdf besar dengan pengaturan halaman dan printer yang ditentukan. Jika Pdf <br/>             file Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk <br/>             mendapatkan kinerja yang lebih baik. |
| print_document_with_settings(page_settings, printer_settings) | Mencetak dokumen Pdf dengan pengaturan. Jika ukuran dokumen tidak cocok dengan ukuran halaman, pdf.kit akan memperluasnya agar sesuai dengan ukuran halaman. |
| print_document_with_settings(printer_settings) | Mencetak dokumen Pdf dengan pengaturan. Jika ukuran dokumen tidak cocok dengan ukuran halaman, pdf.kit akan memperluasnya agar sesuai dengan ukuran halaman. |
| open_pdf_file(file_path) | Membuka file Pdf, tetapi tidak benar-benar mendekode halaman-halaman file Pdf. |
| open_pdf_file(input_stream) | Membuka aliran file Pdf. Tetapi tidak benar-benar mendekode halaman-halaman file Pdf. |
| bind_pdf(src_file) | Menginisialisasi facade. |
| bind_pdf(src_stream) | Menginisialisasi facade. |
| bind_pdf(src_doc) | Menginisialisasi facade. |
| save(dest_file) | Menyimpan dokumen PDF hasil ke file. |
| save(dest_stream) | Menyimpan dokumen PDF hasil ke aliran. |
| decode_all_pages() | Dapatkan halaman dari file pdf saat ini. |
| decode_page(page_number) | Mendekode satu halaman dari file Pdf. |
| print_document_with_setup() | Mencetak dokumen Pdf dengan dialog pengaturan. Pilih printer menggunakan dialog tersebut. |
| print_document() | Mencetak dokumen Pdf dengan dialog pengaturan. Pilih printer menggunakan dialog tersebut. |
| get_default_page_settings() | Mendapatkan pengaturan halaman default. |
| get_default_printer_settings() | Mendapatkan pengaturan printer default. |
| close_pdf_file() | Menutup file Pdf saat ini. |
| close() | Menutup file Pdf saat ini. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

