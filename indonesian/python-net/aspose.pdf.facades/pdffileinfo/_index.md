---
title: "PdfFileInfo"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili kelas untuk mengakses informasi meta dokumen PDF."
type: docs
weight: 270
url: /id/python-net/aspose.pdf.facades/pdffileinfo/
---

## PdfFileInfo class

Mewakili kelas untuk mengakses informasi meta dokumen PDF.

Tipe PdfFileInfo menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfFileInfo() | Menginisialisasi instance baru dari kelas Aspose.Pdf.Facades.PdfFileInfo dengan nilai default. |
| PdfFileInfo(input_stream) | Menginisialisasi instance baru dari kelas PdfFileInfo |
| PdfFileInfo(input_stream, password) | Menginisialisasi instance baru dari kelas PdfFileInfo |
| PdfFileInfo(input_file) | Menginisialisasi instance baru dari kelas PdfFileInfo |
| PdfFileInfo(input_file, password) | Menginisialisasi instance baru dari kelas PdfFileInfo |
| PdfFileInfo(document) | Menginisialisasi instance baru dari kelas PdfFileInfo |
## Properti
| Nama | Deskripsi |
| :- | :- |
| document | Mendapatkan facade dokumen yang sedang diproses. |
| author | Mendapatkan atau mengatur informasi Author dari dokumen PDF. |
| is_encrypted | Memeriksa apakah dokumen PDF terenkripsi. |
| is_pdf_file | Memeriksa apakah input sumber adalah file PDF yang valid. |
| use_strict_validation | Menggunakan aturan validasi ketat melalui properti [is_pdf_file](/pdf/python-net/aspose.pdf.facades/pdffileinfo/). |
| creation_date | Mendapatkan atau mengatur informasi CreationDate dari dokumen PDF. |
| creator | Mendapatkan atau mengatur informasi Creator dari dokumen PDF. |
| has_collection | Mengembalikan true jika file input saat ini adalah file 'Portfolio' yang berisi kumpulan file PDF di dalamnya. |
| input_file | Mendapatkan atau mengatur file input. |
| input_stream | Mendapatkan atau mengatur aliran input. |
| keywords | Mendapatkan atau mengatur informasi Keywords dari dokumen PDF. |
| mod_date | Mendapatkan atau mengatur informasi tanggal ModDate dari dokumen PDF. |
| number_of_pages | Mendapatkan jumlah halaman dokumen. |
| producer | Mendapatkan informasi Producer dari dokumen PDF. |
| subject | Mendapatkan atau mengatur informasi Subject dari dokumen PDF. |
| title | Mendapatkan atau mengatur informasi Title dari dokumen PDF. |
| password_type | Mengembalikan jenis kata sandi yang diberikan untuk membuat instance PdfFileInfo. Lihat nilai yang mungkin di [password_type](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            Perhatikan bahwa dokumen pdf dapat dibuka menggunakan kata sandi pengguna (atau buka) dan kata sandi pemilik (atau izin, edit). |
| has_open_password | Mengembalikan true jika kata sandi diperlukan untuk membuka dokumen pdf yang dilindungi kata sandi. |
| has_edit_password | Mengembalikan true jika kata sandi diperlukan untuk mengubah izin atau properti keamanan dokumen.<br/>            Perhatikan bahwa properti ini hanya dapat dibaca jika kata sandi yang valid diberikan dalam konstruktor [PdfFileInfo](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            Jika PasswordType adalah Inaccessible (berarti kata sandi tidak valid) membaca properti ini akan gagal dengan [InvalidPasswordException](/pdf/python-net/aspose.pdf/invalidpasswordexception/). |
## Metode
| Nama | Deskripsi |
| :- | :- |
| bind_pdf(src_doc) | Menginisialisasi facade. |
| bind_pdf(src_file) | Menginisialisasi facade. |
| bind_pdf(src_stream) | Menginisialisasi facade. |
| save(dest_stream) | Simpan dokumen PDF yang diperbarui ke aliran yang ditentukan. |
| save(dest_file) | Simpan dokumen PDF yang diperbarui ke file yang ditentukan. |
| save_new_info(output_stream) | Simpan dokumen PDF yang diperbarui ke aliran yang ditentukan. |
| save_new_info(output_file) | Simpan dokumen PDF yang diperbarui ke file yang ditentukan. |
| close() | Mendeinisialisasi instance. |
| clear_info() | Menghapus semua informasi meta dari dokumen PDF. |
| get_document_privilege() | Mendapatkan pengaturan hak istimewa dokumen PDF. |
| get_meta_info(name) | Mendapatkan informasi yang disesuaikan dari dokumen PDF dengan nama properti. Jika tidak ada properti yang cocok dengan nama tersebut, akan mengembalikan string kosong. |
| get_page_height(page_num) | Mendapatkan tinggi halaman yang ditentukan. |
| get_page_rotation(page_num) | Mendapatkan rotasi halaman yang ditentukan. |
| get_page_width(page_num) | Mendapatkan lebar halaman yang ditentukan. |
| get_page_x_offset(page_num) | Mendapatkan offset horizontal dari area tampilan halaman yang ditentukan. |
| get_page_y_offset(page_num) | Mendapatkan offset vertikal dari area tampilan halaman yang ditentukan. |
| get_pdf_version() | Mendapatkan info versi dokumen PDF. |
| set_meta_info(name, value) | Mengatur informasi yang disesuaikan dari dokumen PDF. |
| save_new_info_with_xmp(output_file_name) | Mengubah properti yang ditentukan secara eksplisit dengan mengatur informasi file, properti lainnya tetap. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

