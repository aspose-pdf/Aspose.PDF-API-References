---
title: "PdfBookmarkEditor"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili kelas untuk bekerja dengan penanda buku file PDF termasuk membuat, memodifikasi, mengekspor, mengimpor, dan menghapus."
type: docs
weight: 180
url: /id/python-net/aspose.pdf.facades/pdfbookmarkeditor/
---

## PdfBookmarkEditor class

Mewakili kelas untuk bekerja dengan penanda buku file PDF termasuk membuat, memodifikasi, mengekspor, mengimpor, dan menghapus.

Tipe PdfBookmarkEditor menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfBookmarkEditor() | Menginisialisasi objek [PdfBookmarkEditor](/pdf/python-net/aspose.pdf.facades/pdfbookmarkeditor/) baru. |
| PdfBookmarkEditor(document) | Menginisialisasi instance baru dari kelas PdfBookmarkEditor |
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
| create_bookmarks() | Membuat bookmark untuk semua halaman. |
| create_bookmarks(bookmark) | Membuat bookmark untuk semua halaman. |
| create_bookmarks(color, bold_flag, italic_flag) | Buat penanda untuk semua halaman dengan warna dan gaya yang ditentukan (tebal, miring). |
| create_bookmark_of_page(bookmark_name, page_number) | Membuat penanda untuk halaman yang ditentukan. |
| create_bookmark_of_page(bookmark_name, page_number) | Membuat penanda untuk halaman-halaman yang ditentukan. |
| delete_bookmarks() | Menghapus semua penanda dari dokumen PDF. |
| delete_bookmarks(title) | Menghapus penanda dari dokumen PDF. |
| extract_bookmarks() | Mengekstrak penanda dari semua level dalam dokumen. |
| extract_bookmarks(upper_level) | Mengekstrak penanda dari semua level dalam dokumen. |
| extract_bookmarks(title) | Mengekstrak penanda dengan judul yang ditentukan. |
| extract_bookmarks(bookmark) | Mengekstrak penanda dari semua level dalam dokumen. |
| export_bookmarks_to_xml(xml_file) | Mengekspor penanda ke file XML. |
| export_bookmarks_to_xml(stream) | Mengekspor penanda ke aliran XML. |
| import_bookmarks_with_xml(xml_file) | Mengimpor penanda ke dokumen dari file XML. |
| import_bookmarks_with_xml(stream) | Mengimpor penanda ke dokumen dari file XML. |
| close() | Melepaskan semua sumber daya yang terkait dengan fasad saat ini. |
| modify_bookmarks(s_title, d_title) | Mengubah judul penanda sesuai dengan judul penanda yang ditentukan. |
| extract_bookmarks_to_html(pdf_file, css_file) | Mengekspor penanda ke file HTML. |
| export_bookmarks_to_html(in_pdf_file, out_html_file) | Mengekspor penanda ke file HTML. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

