---
title: "PdfFormatConversionOptions"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "mewakili sekumpulan opsi untuk mengonversi dokumen PDF"
type: docs
weight: 1220
url: /id/python-net/aspose.pdf/pdfformatconversionoptions/
---

## PdfFormatConversionOptions class

mewakili sekumpulan opsi untuk mengonversi dokumen PDF

Tipe PdfFormatConversionOptions menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfFormatConversionOptions(output_log_file_name, format, action) | Menginisialisasi sebuah instance baru dari kelas PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format) | Menginisialisasi sebuah instance baru dari kelas PdfFormatConversionOptions |
| PdfFormatConversionOptions(format) | Menginisialisasi sebuah instance baru dari kelas PdfFormatConversionOptions |
| PdfFormatConversionOptions(format, action) | Menginisialisasi sebuah instance baru dari kelas PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_file_name, format, action, transparency_action) | Menginisialisasi sebuah instance baru dari kelas PdfFormatConversionOptions |
| PdfFormatConversionOptions(output_log_stream, format, action) | Menginisialisasi sebuah instance baru dari kelas PdfFormatConversionOptions |
## Properti
| Nama | Deskripsi |
| :- | :- |
| is_async_image_streams_conversion_mode | Mendapatkan/mengatur jalannya aliran gambar dalam mode async. |
| is_low_memory_mode | Apakah mode konversi memori rendah diaktifkan |
| format | format PDF. |
| log_file_name | Jalur ke file tempat komentar akan disimpan. |
| log_stream | Aliran tempat komentar akan disimpan. |
| error_action | Aksi untuk objek yang tidak dapat dikonversi |
| transparency_action | Aksi untuk objek gambar yang dimasker |
| convert_soft_mask_action | Aksi untuk gambar dengan soft mask. |
| default | Mendapatkan objek PdfFormatConversionOptions dengan parameter default |
| non_specification_cases | Menyimpan flag untuk mengontrol proses konversi PDF/A untuk kasus ketika dokumen sumber<br/>            tidak sesuai dengan spesifikasi PDF/A. |
| symbolic_font_encoding_strategy | Strategi untuk menyalin data enkoding untuk font simbolik jika font TrueType simbolik<br/>            memiliki lebih dari satu subtable enkoding. |
| align_text | Flag ini mengontrol perataan teks dalam dokumen yang dikonversi. Secara default konversi dokumen <br/>            tidak memengaruhi perataan teks dan membiarkan teks apa adanya. Namun dalam beberapa kasus substitusi font<br/>            menyebabkan teks saling tumpang tindih atau spasi ekstra dalam dokumen yang dikonversi. Ketika flag ini diatur<br/>            operasi perataan khusus akan dilakukan. Flag ini sebaiknya diatur hanya untuk dokumen<br/>            yang memiliki masalah dengan teks yang tumpang tindih atau spasi teks ekstra karena penggunaan flag ini dapat menurunkan<br/>            kinerja dan dalam beberapa kasus dapat merusak isi teks. |
| pua_text_processing_strategy | Strategi untuk memproses simbol dari Private Use Area (PUA) Unicode. |
| optimize_file_size | Mendapatkan atau mengatur sebuah flag yang mengaktifkan/menonaktifkan mode konversi khusus untuk menghasilkan dokumen PDF/A dengan ukuran file yang lebih kecil.<br/>            Sekarang flag ini memengaruhi optimisasi font yang digunakan dalam dokumen PDF, kemungkinan, di masa depan, flag ini <br/>            juga akan digunakan untuk mengaktifkan optimisasi untuk struktur data lain, seperti grafik.  <br/>            Pengaturan flag dan mode ini dapat secara signifikan mengurangi ukuran file tetapi pada saat yang sama dapat<br/>            secara signifikan menurunkan kinerja konversi. |
| exclude_fonts_strategy | Strategi untuk mengecualikan font yang berlebih dan mengurangi ukuran file dokumen. <br/>            Parameter ini hanya bermakna ketika flag [optimize_file_size](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) diatur ke true.<br/>            Secara default kombinasi strategi [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) dan<br/>            [None](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) digunakan. |
| font_embedding_options | Opsi untuk kasus ketika tidak memungkinkan menyematkan beberapa font ke dalam dokumen PDF. |
| unicode_processing_rules | Aturan untuk menyelesaikan masalah dengan pemetaan unicode. Bisa bernilai null. |
| icc_profile_file_name | Mendapatkan atau mengatur nama file profil icc. Jika null, profil icc default akan digunakan. |
| not_accessible_fonts | Properti ini adalah out-property. Ia menyimpan semua font (nama font) yang tidak ditemukan di komputer <br/>            pada konversi PDF/A terakhir. |
| is_transfer_info | Mendapatkan atau mengatur apakah data harus dipindahkan dari Info ke Metadata saat dikonversi ke PDF 2.0. True secara default. |
| align_strategy | Strategi untuk meratakan teks. Parameter ini hanya bermakna ketika flag [align_text](/pdf/python-net/aspose.pdf/pdfformatconversionoptions/) diatur ke true. |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

