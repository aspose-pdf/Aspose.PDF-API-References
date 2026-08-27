---
title: "PdfPageEditor"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili kelas untuk mengedit halaman file PDF, termasuk memutar halaman, memperbesar halaman, memindahkan posisi, dan mengubah ukuran halaman."
type: docs
weight: 340
url: /id/python-net/aspose.pdf.facades/pdfpageeditor/
---

## PdfPageEditor class

Mewakili kelas untuk mengedit halaman file PDF, termasuk memutar halaman, memperbesar halaman, memindahkan posisi, dan mengubah ukuran halaman.

Tipe PdfPageEditor menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfPageEditor() | Konstruktor untuk kelas PdfPageEditor. |
| PdfPageEditor(document) | Menginisialisasi instance baru dari kelas PdfPageEditor |
## Properti
| Nama | Deskripsi |
| :- | :- |
| document | Mendapatkan facade dokumen yang sedang diproses. |
| transition_duration | Mendapatkan atau mengatur durasi efek transisi. |
| transition_type | Mendapatkan atau mengatur gaya transisi yang digunakan saat berpindah ke halaman ini dari halaman lain selama presentasi. |
| display_duration | Mendapatkan atau mengatur durasi tampilan untuk halaman. |
| process_pages | Mendapatkan atau mengatur nomor halaman yang akan diedit. Secara default, setiap halaman akan diedit. |
| rotation | Mendapatkan atau mengatur rotasi halaman, rotasi harus 0, 90, 180, atau 270.<br/>            Nilai default adalah 0. |
| zoom | Mendapatkan atau mengatur koefisien zoom. Nilai 1.0 sesuai dengan 100%.<br/>            Nilai default adalah 1.0. |
| page_size | Mendapatkan atau mengatur ukuran halaman file output. |
| perataan | Mendapatkan atau mengatur perataan horizontal konten PDF asli pada halaman hasil, default adalah AlignmentType.Left. |
| horizontal_alignment | Mendapatkan atau mengatur perataan horizontal konten PDF asli pada halaman hasil, default adalah AlignmentType.Left. |
| vertical_alignment | Mendapatkan atau mengatur perataan vertikal konten PDF asli pada halaman hasil, default adalah VerticalAlignmentType.Bottom. |
| vertical_alignment_type | Mendapatkan atau mengatur perataan vertikal konten PDF asli pada halaman hasil, default adalah VerticalAlignmentType.Bottom. |
| SPLITVOUT | Pembagian Vertikal Keluar |
| SPLITHOUT | Pembagian Horizontal Keluar |
| SPLITVIN | Pembagian Vertikal Masuk |
| SPLITHIN | Pembagian Horizontal Masuk |
| BLINDV | Tirai Vertikal |
| BLINDH | Tirai Vertikal |
| INBOX | Kotak Ke Dalam |
| OUTBOX | Kotak Ke Luar |
| LRWIPE | Usapan Kiri-Kanan |
| RLWIPE | Usapan Kanan-Kiri |
| BTWIPE | Usapan Bawah-Atas |
| TBWIPE | Usapan Atas-Bawah |
| DISSOLVE | Halaman lama menghilang |
| LRGLITTER | Gemerlap Kiri-Kanan |
| TBGLITTER | Gemerlap Atas-Bawah |
| DGLITTER | Gemerlap Diagonal |
## Metode
| Nama | Deskripsi |
| :- | :- |
| bind_pdf(src_file) | Mengikat dokumen PDF untuk diedit. |
| bind_pdf(src_stream) | Mengikat dokumen PDF untuk diedit. |
| bind_pdf(src_doc) | Mengikat dokumen PDF untuk diedit. |
| save(output_file) | Menyimpan dokumen yang diubah ke dalam file. |
| save(output_stream) | Menyimpan dokumen yang diubah ke dalam stream. |
| close() | Melepaskan semua sumber daya yang terkait dengan fasad saat ini. |
| move_position(move_x, move_y) | Memindahkan asal dari (0, 0) ke titik yang ditentukan. <br/>            Asal berada di kiri-bawah dan satuannya adalah point (1 inci = 72 poin). |
| get_pages() | Mengembalikan total jumlah halaman. |
| get_page_size(page) | Mengembalikan ukuran halaman dari halaman yang ditentukan. |
| get_page_rotation(page) | Mengembalikan rotasi halaman yang ditentukan. |
| get_page_box_size(page, page_box_name) | Mengembalikan ukuran kotak yang ditentukan dalam dokumen. |
| apply_changes() | Menerapkan perubahan yang dibuat pada halaman dokumen. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

