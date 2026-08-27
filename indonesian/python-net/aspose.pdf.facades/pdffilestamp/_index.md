---
title: "PdfFileStamp"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas untuk menambahkan stempel (tanda air atau latar belakang) ke file PDF."
type: docs
weight: 320
url: /id/python-net/aspose.pdf.facades/pdffilestamp/
---

## PdfFileStamp class

Kelas untuk menambahkan stempel (tanda air atau latar belakang) ke file PDF.

Tipe PdfFileStamp menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfFileStamp(input_file, output_file) | Menginisialisasi sebuah instance baru dari kelas PdfFileStamp |
| PdfFileStamp(input_stream, output_stream) | Menginisialisasi sebuah instance baru dari kelas PdfFileStamp |
| PdfFileStamp(input_file, output_file, keep_security) | Menginisialisasi sebuah instance baru dari kelas PdfFileStamp |
| PdfFileStamp(input_stream, output_stream, keep_security) | Menginisialisasi sebuah instance baru dari kelas PdfFileStamp |
| PdfFileStamp() | Konstruktor dari PdfFileStamp.<br/>            File input dan file output dapat ditentukan melalui properti yang bersesuaian. |
| PdfFileStamp(document) | Menginisialisasi sebuah instance baru dari kelas PdfFileStamp |
| PdfFileStamp(document, output_file) | Menginisialisasi sebuah instance baru dari kelas PdfFileStamp |
| PdfFileStamp(document, output_stream) | Menginisialisasi sebuah instance baru dari kelas PdfFileStamp |
## Properti
| Nama | Deskripsi |
| :- | :- |
| document | Mendapatkan facade dokumen yang sedang diproses. |
| optimize_size | Mendapatkan atau mengatur flag optimisasi. Aliran sumber daya yang sama dalam file hasil digabungkan menjadi satu objek PDF jika flag ini diatur. <br/>            Ini memungkinkan mengurangi ukuran file hasil tetapi dapat menyebabkan eksekusi lebih lambat dan kebutuhan memori yang lebih besar.<br/>            Nilai default: false. |
| keep_security | Menjaga keamanan jika true. (Fitur ini akan diimplementasikan pada versi berikutnya). |
| input_file | Mendapatkan atau mengatur nama dan jalur file input. |
| input_stream | Mendapatkan atau mengatur aliran input. |
| output_file | Mendapatkan atau mengatur nama dan jalur file output. |
| output_stream | Mendapatkan atau mengatur aliran output. |
| page_number_rotation | Mendapatkan atau mengatur rotasi nomor halaman. Rotasi dalam derajat. Default adalah 0. |
| page_height | Mendapatkan tinggi halaman pertama dalam file sumber. |
| page_width | Mendapatkan lebar halaman pertama dalam file input. |
| starting_number | Mendapatkan atau mengatur nomor awal untuk halaman pertama dalam file input. Halaman berikutnya akan diberi nomor mulai dari nilai ini. <br/>            Misalnya jika StartingNumber diatur ke 100, halaman dokumen akan memiliki nomor 100, 101, 102... |
| numbering_style | Mendapatkan atau mengatur gaya penomoran halaman. Nilai yang mungkin: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| stamp_id | ID Stempel dari stempel berikutnya yang ditambahkan (termasuk header/footer halaman/nomor halaman). |
| POS_BOTTOM_MIDDLE | Posisi tengah bawah. |
| POS_BOTTOM_RIGHT | Posisi kanan bawah. |
| POS_UPPER_RIGHT | Posisi kanan atas. |
| POS_SIDES_RIGHT | Posisi kanan. |
| POS_UPPER_MIDDLE | Posisi tengah atas. |
| POS_BOTTOM_LEFT | Posisi kiri bawah. |
| POS_SIDES_LEFT | Posisi kiri. |
| POS_UPPER_LEFT | Posisi let atas. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| bind_pdf(src_file) | Mengikat dokumen PDF untuk diedit. |
| bind_pdf(src_stream) | Mengikat dokumen PDF untuk diedit. |
| bind_pdf(src_doc) | Mengikat dokumen PDF untuk diedit. |
| save(dest_file) | Menyimpan hasil ke file yang ditentukan. |
| save(dest_stream) | Menyimpan dokumen ke aliran yang ditentukan. |
| add_page_number(format_string) | Menambahkan nomor halaman ke file. Teks nomor halaman dapat berisi tanda # yang akan diganti dengan nomor halaman. <br/>            Nomor halaman ditempatkan di bagian bawah halaman secara horizontal di tengah. |
| add_page_number(formatted_text) | Menambahkan nomor halaman ke halaman. Nomor halaman dapat berisi tanda # yang akan diganti dengan nomor halaman.<br/>            Nomor halaman ditempatkan di bagian bawah halaman secara horizontal di tengah. |
| add_page_number(format_string, position, left_margin, right_margin, top_margin, bottom_margin) | Menambahkan nomor halaman ke halaman-halaman dokumen. |
| add_page_number(format_string, x, y) | Menambahkan nomor halaman ke halaman-halaman dokumen. |
| add_page_number(formatted_text, position, left_margin, right_margin, top_margin, bottom_margin) | Menambahkan nomor halaman ke halaman-halaman dokumen. |
| add_page_number(formatted_text, x, y) | Menambahkan nomor halaman ke halaman-halaman dokumen. |
| add_page_number(format_string, position) | Menambahkan nomor halaman ke halaman-halaman dokumen. |
| add_page_number(formatted_text, position) | Menambahkan nomor halaman ke halaman-halaman dokumen. |
| add_header(formatted_text, top_margin) | Menambahkan header ke halaman. |
| add_header(formatted_text, top_margin, left_margin, right_margin) | Menambahkan header ke halaman. |
| add_header(image_file, top_margin) | Menambahkan gambar sebagai header ke halaman-halaman file. |
| add_header(image_file, top_margin, left_margin, right_margin) | Menambahkan gambar sebagai header ke halaman-halaman file. |
| add_header(image_stream, top_margin) | Menambahkan gambar sebagai header pada halaman. |
| add_header(input_stream, top_margin, left_margin, right_margin) | Menambahkan gambar sebagai header pada halaman. |
| add_footer(formatted_text, bottom_margin) | Menambahkan footer ke halaman-halaman dokumen. |
| add_footer(formatted_text, bottom_margin, left_margin, right_margin) | Menambahkan footer ke halaman-halaman dokumen. |
| add_footer(image_file, bottom_margin) | Menambahkan gambar sebagai footer ke halaman-halaman dokumen. |
| add_footer(image_file, bottom_margin, left_margin, right_margin) | Menambahkan gambar sebagai footer ke halaman-halaman dokumen. |
| add_footer(image_stream, bottom_margin) | Menambahkan gambar sebagai footer halaman. |
| add_footer(image_stream, bottom_margin, left_margin, right_margin) | Menambahkan gambar sebagai footer halaman. |
| close() | Menutup file yang dibuka dan menyimpan perubahan. <br/>            Peringatan. Jika aliran input atau output ditentukan, mereka tidak ditutup oleh metode Close(). |
| add_stamp(stamp) | Menambahkan stempel ke file. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

