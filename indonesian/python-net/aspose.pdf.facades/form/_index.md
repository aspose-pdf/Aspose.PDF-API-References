---
title: "Form"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas yang merepresentasikan objek formulir Acro."
type: docs
weight: 80
url: /id/python-net/aspose.pdf.facades/form/
---

## Form class

Kelas yang merepresentasikan objek formulir Acro.

Tipe Form menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| Form(src_stream, dest_stream) | Menginisialisasi instance baru dari kelas Form |
| Form() | Konstruktor Form tanpa parameter. |
| Form(src_file_name) | Menginisialisasi instance baru dari kelas Form |
| Form(src_stream) | Menginisialisasi instance baru dari kelas Form |
| Form(src_file_name, dest_file_name) | Menginisialisasi instance baru dari kelas Form |
| Form(src_file_name, dest_stream) | Menginisialisasi instance baru dari kelas Form |
| Form(src_stream, dest_file_name) | Menginisialisasi instance baru dari kelas Form |
| Form(document) | Menginisialisasi instance baru dari kelas Form |
| Form(document, dest_file_name) | Menginisialisasi instance baru dari kelas Form |
| Form(document, dest_stream) | Menginisialisasi instance baru dari kelas Form |
## Properti
| Nama | Deskripsi |
| :- | :- |
| document | Mendapatkan facade dokumen yang sedang diproses. |
| import_result | Hasil dari operasi impor terakhir. Array objek yang menjelaskan hasil impor untuk setiap bidang. |
| src_file_name | Mendapatkan atau mengatur nama file sumber. |
| dest_file_name | Mendapatkan atau mengatur nama file tujuan. |
| src_stream | Mendapatkan atau mengatur aliran sumber. |
| dest_stream | Mendapatkan atau mengatur aliran tujuan. |
| field_names | Mendapatkan daftar nama bidang pada formulir. |
| form_submit_button_names | Mendapatkan semua nama tombol kirim formulir. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| bind_pdf(src_file) | Mengikat dokumen PDF untuk diedit. |
| bind_pdf(src_stream) | Mengikat dokumen PDF untuk diedit. |
| bind_pdf(src_doc) | Mengikat dokumen PDF untuk diedit. |
| save() | Menyimpan nilai bidang yang diisi dan menutup dokumen Pdf yang terbuka. |
| save(dest_file) | Menyimpan dokumen ke file yang ditentukan. |
| save(dest_stream) | Menyimpan dokumen ke aliran yang ditentukan. |
| fill_field(field_name, field_value) | Mengisi bidang dengan nilai yang valid sesuai dengan nama bidang yang sepenuhnya memenuhi syarat.<br/>            Sebelum mengisi bidang, semua nama bidang dan nilai valid yang bersesuaian harus diketahui.<br/>            Baik nama maupun nilai bidang bersifat case sensitive.<br/>            Harap perhatikan bahwa Aspose.Pdf.Facades hanya mendukung nama bidang lengkap dan tidak bekerja dengan nama parsial <br/>            dibandingkan dengan Aspose.Pdf.Kit;<br/>            Misalnya jika bidang memiliki nama lengkap \"Form.Subform.TextField\" Anda harus menentukan nama lengkap dan bukan \"TextField\". <br/>            Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya. |
| fill_field(field_name, index) | Mengisi bidang kotak radio dengan nilai indeks yang valid sesuai dengan nama bidang yang sepenuhnya memenuhi syarat.<br/>            Sebelum mengisi bidang, hanya nama bidang yang harus diketahui. Nilai dapat ditentukan melalui indeksnya.<br/>            Catatan: Hanya berlaku untuk bidang Radio Box, Combo Box, dan List Box.<br/>            Harap perhatikan bahwa Aspose.Pdf.Facades hanya mendukung nama bidang lengkap dan tidak bekerja dengan nama parsial <br/>            dibandingkan dengan Aspose.Pdf.Kit;<br/>            Misalnya jika bidang memiliki nama lengkap \"Form.Subform.ListBoxField\" Anda harus menentukan nama lengkap dan bukan \"ListBoxField\". <br/>            Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya. |
| fill_field(field_name, be_checked) | Mengisi bidang kotak centang dengan nilai boolean.<br/>            Catatan: Hanya berlaku untuk Check Box.<br/>            Harap perhatikan bahwa Aspose.Pdf.Facades hanya mendukung nama bidang lengkap dan tidak bekerja dengan nama parsial <br/>            dibandingkan dengan Aspose.Pdf.Kit;<br/>            Misalnya jika bidang memiliki nama lengkap \"Form.Subform.CheckBoxField\" Anda harus menentukan nama lengkap dan bukan \"CheckBoxField\". <br/>            Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya. |
| fill_field(field_name, field_values) | Mengisi bidang kotak teks dengan nilai teks dan menyimpan dokumen.<br/>            Relevan untuk dokumen yang ditandatangani.<br/>            Catatan: Hanya berlaku untuk Text Box.<br/>            Baik nama maupun nilai bidang bersifat case sensitive. |
| fill_field(field_name, value, fit_font_size) | Mengisi bidang kotak centang dengan nilai boolean.<br/>            Catatan: Hanya berlaku untuk Check Box.<br/>            Harap perhatikan bahwa Aspose.Pdf.Facades hanya mendukung nama bidang lengkap dan tidak bekerja dengan nama parsial <br/>            dibandingkan dengan Aspose.Pdf.Kit;<br/>            Misalnya jika bidang memiliki nama lengkap \"Form.Subform.CheckBoxField\" Anda harus menentukan nama lengkap dan bukan \"CheckBoxField\". <br/>            Anda dapat menggunakan properti FieldNames untuk menjelajahi nama bidang yang ada dan mencari bidang yang diperlukan berdasarkan nama parsialnya. |
| import_xml(input_xml_stream) | Mengimpor konten bidang dari file xml dan menempatkannya ke dalam pdf baru. |
| import_xml(input_xml_stream, ignore_form_template_changes) | Mengimpor konten bidang dari file xml dan menempatkannya ke dalam pdf baru. |
| fill_image_field(field_name, image_file_name) | Menempelkan gambar ke bidang tombol yang ada sebagai penampilannya sesuai dengan <br/>            nama bidang yang sepenuhnya memenuhi syarat. |
| fill_image_field(field_name, image_stream) | Fungsi overload dari FillImageField.<br/>            Inputnya adalah aliran gambar. |
| close() | Menutup file yang dibuka tanpa perubahan apa pun. |
| get_field_facade(field_name) | Mengembalikan objek FrogmFieldFacade yang berisi semua atribut tampilan. |
| fill_fields(field_names, field_values, output) | Mengisi bidang kotak teks dengan nilai teks dan menyimpan dokumen.<br/>            Relevan untuk dokumen yang ditandatangani.<br/>            Catatan: Hanya berlaku untuk Text Box.<br/>            Baik nama maupun nilai bidang bersifat case sensitive. |
| get_button_option_current_value(field_name) | Mengembalikan nilai saat ini untuk bidang opsi tombol radio. |
| get_field(field_name) | Mengembalikan objek FrogmFieldFacade yang berisi semua atribut tampilan. |
| get_full_field_name(field_name) | Mendapatkan nama bidang lengkap sesuai dengan nama bidang singkatnya. |
| get_field_limit(field_name) | Dapatkan batasan bidang teks. |
| flatten_all_fields() | Membuat semua bidang menjadi datar. |
| flatten_field(field_name) | Membuat bidang tertentu menjadi datar dengan nama bidang yang sepenuhnya memenuhi syarat.<br/>            Semua bidang lain akan tetap tidak dapat diubah. Jika fieldName tidak valid, <br/>            semua bidang akan tetap tidak dapat diubah. |
| fill_barcode_field(field_name, data) | Isi bidang kode batang sesuai dengan nama bidang yang sepenuhnya memenuhi syarat. |
| import_fdf(input_fdf_stream) | Mengimpor konten bidang dari file fdf dan menempatkannya ke dalam pdf baru. |
| export_fdf(output_fdf_stream) | Mengekspor konten bidang pdf ke dalam aliran fdf. |
| export_xml(output_xml_stream) | Mengekspor konten bidang pdf ke dalam aliran xml.<br/>            Nilai bidang tombol tidak akan diekspor. |
| extract_xfa_data(output_xml_stream) | Mengekstrak paket data XFA |
| set_xfa_data(input_xml_stream) | Mengganti data XFA dengan paket data yang ditentukan. Paket data dapat diekstrak menggunakan ExtractXfaData. |
| import_xfdf(input_xfdf_stream) | Mengimpor konten bidang dari file xfdf(xml) dan menaruhnya ke dalam PDF baru. |
| export_xfdf(output_xfdf_stream) | Mengekspor konten bidang pdf ke dalam aliran xml.<br/>            Nilai bidang tombol tidak akan diekspor. |
| rename_field(field_name, new_field_name) | Mengganti nama sebuah bidang. Baik bidang AcroForm maupun XFA diperbolehkan. |
| get_rich_text(field_name) | Dapatkan nilai bidang Rich Text, termasuk informasi pemformatan setiap karakter. |
| get_submit_flags(field_name) | Mengembalikan flag pengiriman tombol submit |
| get_field_type(field_name) | Mengembalikan tipe bidang. |
| is_required_field(field_name) | Menentukan apakah bidang wajib atau tidak. |
| get_field_flag(field_name) | Mengembalikan flag bidang. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

