---
title: "PdfAnnotationEditor"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili kelas untuk bekerja dengan anotasi dokumen PDF (komentar)."
type: docs
weight: 170
url: /id/python-net/aspose.pdf.facades/pdfannotationeditor/
---

## PdfAnnotationEditor class

Mewakili kelas untuk bekerja dengan anotasi dokumen PDF (komentar).

Tipe PdfAnnotationEditor menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfAnnotationEditor() | Menginisialisasi objek [PdfAnnotationEditor](/pdf/python-net/aspose.pdf.facades/pdfannotationeditor/) baru. |
| PdfAnnotationEditor(document) | Menginisialisasi instance baru dari kelas PdfAnnotationEditor |
## Properti
| Nama | Deskripsi |
| :- | :- |
| document | Mendapatkan facade dokumen yang sedang diproses. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| bind_pdf(src_file) | Mengikat dokumen PDF untuk diedit. |
| bind_pdf(src_stream) | Mengikat dokumen PDF untuk diedit. |
| bind_pdf(src_doc) | Mengikat dokumen PDF untuk diedit. |
| save(dest_file) | Menyimpan dokumen PDF ke file yang ditentukan. |
| save(dest_stream) | Menyimpan dokumen PDF ke aliran yang ditentukan. |
| import_annotations_from_xfdf(xfdf_file) | Mengimpor semua anotasi dari file XFDF. |
| import_annotations_from_xfdf(xfdf_stream) | Mengimpor semua anotasi dari aliran data XFDF. |
| import_annotation_from_xfdf(xfdf_file) | Mengimpor semua anotasi dari file XFDF. |
| import_annotation_from_xfdf(xfdf_file, annot_type) | Mengimpor anotasi yang ditentukan dari file XFDF. |
| import_annotation_from_xfdf(xfdf_stream, annot_type) | Mengimpor anotasi yang ditentukan dari aliran data XFDF. |
| import_annotation_from_xfdf(xfdf_stream) | Mengimpor anotasi yang ditentukan dari aliran data XFDF. |
| import_annotations(annot_file, annot_type) | Mengimpor anotasi yang ditentukan ke dalam dokumen dari kumpulan dokumen PDF lain. |
| import_annotations(annot_file) | Mengimpor anotasi yang ditentukan ke dalam dokumen dari kumpulan dokumen PDF lain. |
| import_annotations(annot_file_stream, annot_type) | Mengimpor anotasi yang ditentukan ke dalam dokumen dari array aliran dokumen PDF lainnya. |
| import_annotations(annot_file_stream) | Mengimpor anotasi yang ditentukan ke dalam dokumen dari array aliran dokumen PDF lainnya. |
| flattening_annotations() | Meratakan semua anotasi dalam dokumen. |
| flattening_annotations(flatten_settings) | Meratakan semua anotasi dalam dokumen. |
| flattening_annotations(start, end, annot_type) | Meratakan anotasi dari tipe yang ditentukan. |
| delete_annotations() | Menghapus semua anotasi dalam dokumen. |
| delete_annotations(annot_type) | Menghapus semua anotasi dari tipe yang ditentukan dalam dokumen. |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Mengekspor konten dari tipe anotasi yang ditentukan ke dalam XFDF |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Mengekspor konten dari tipe anotasi yang ditentukan ke dalam XFDF |
| extract_annotations(start, end, annot_types) | Mendapatkan daftar anotasi dari tipe yang ditentukan. |
| extract_annotations(start, end, annot_types) | Mendapatkan daftar anotasi dari tipe yang ditentukan. |
| close() | Melepaskan semua sumber daya yang terkait dengan fasad saat ini. |
| modify_annotations_author(start, end, src_author, des_author) | Mengubah penulis anotasi pada rentang halaman yang ditentukan. |
| delete_annotation(annot_name) | Menghapus semua anotasi dari tipe yang ditentukan dalam dokumen. |
| export_annotations_to_xfdf(xml_output_stream) | Mengekspor anotasi ke aliran. |
| modify_annotations(start, end, annotation) | Mengubah anotasi dari tipe yang ditentukan pada rentang halaman yang ditentukan.<br/>            Mendukung untuk mengubah properti anotasi berikut: Modified, Title, Contents, Color, Subject, dan Open. |
| redact_area(page_index, rect, color) | Menyensor area pada halaman yang ditentukan. Semua konten dihapus. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

