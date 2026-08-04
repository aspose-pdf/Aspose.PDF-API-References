---
title: "PdfContentEditor"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili kelas untuk mengedit konten file PDF."
type: docs
weight: 190
url: /id/python-net/aspose.pdf.facades/pdfcontenteditor/
---

## PdfContentEditor class

Mewakili kelas untuk mengedit konten file PDF.

Tipe PdfContentEditor menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfContentEditor() | Konstruktor objek PdfContentEditor. |
| PdfContentEditor(document) | Menginisialisasi sebuah instance baru dari kelas PdfContentEditor |
## Properti
| Nama | Deskripsi |
| :- | :- |
| document | Mendapatkan facade dokumen yang sedang diproses. |
| text_search_options | Mendapatkan atau mengatur opsi pencarian teks. |
| text_edit_options | Mendapatkan atau mengatur opsi penyuntingan teks. |
| text_replace_options | Mendapatkan atau mengatur opsi penggantian teks. |
| replace_text_strategy | Sekumpulan parameter untuk operasi penggantian teks |
| DOCUMENT_OPEN | Tipe peristiwa dokumen. Membuka sebuah dokumen. |
| DOCUMENT_CLOSE | Tipe peristiwa dokumen. Menutup sebuah dokumen. |
| DOCUMENT_WILL_SAVE | Tipe peristiwa dokumen. Menjalankan aksi sebelum menyimpan. |
| DOCUMENT_SAVED | Tipe peristiwa dokumen. Menjalankan aksi setelah menyimpan. |
| DOCUMENT_WILL_PRINT | Tipe peristiwa dokumen. Menjalankan aksi sebelum mencetak. |
| DOCUMENT_PRINTED | Tipe peristiwa dokumen. Menjalankan aksi setelah mencetak. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| bind_pdf(input_file) | Mengikat file PDF untuk diedit. |
| bind_pdf(input_stream) | Mengikat aliran PDF untuk diedit. |
| bind_pdf(src_doc) | Mengikat dokumen PDF untuk diedit. |
| save(dest_file) | Menyimpan dokumen PDF ke file yang ditentukan. |
| save(dest_stream) | Menyimpan dokumen PDF ke aliran yang ditentukan. |
| create_web_link(rect, url, original_page, clr) | Membuat tautan web dalam dokumen PDF. |
| create_web_link(rect, url, original_page) | Membuat tautan web dalam dokumen PDF. |
| create_local_link(rect, des_page, original_page, clr) | Membuat tautan lokal dalam dokumen PDF. |
| create_local_link(rect, des_page, original_page) | Membuat tautan lokal dalam dokumen PDF. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page, clr) | Membuat tautan ke halaman dokumen PDF lain. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page) | Membuat tautan ke halaman dokumen PDF lain. |
| create_application_link(rect, application, page, clr) | Membuat tautan untuk meluncurkan aplikasi dalam dokumen PDF. |
| create_application_link(rect, application, page) | Membuat tautan untuk meluncurkan aplikasi dalam dokumen PDF. |
| create_file_attachment(rect, contents, file_path, page, name) | Membuat anotasi lampiran file. |
| create_file_attachment(rect, contents, file_path, page, name, opacity) | Membuat anotasi lampiran file. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name) | Membuat anotasi lampiran file. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name, opacity) | Membuat anotasi lampiran file. |
| add_document_attachment(file_attachment_path, description) | Menambahkan lampiran dokumen tanpa anotasi. |
| add_document_attachment(file_attachment_stream, file_attachment_name, description) | Menambahkan lampiran dokumen tanpa anotasi. |
| create_rubber_stamp(page, annot_rect, icon, annot_contents, color) | Membuat anotasi stempel karet. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_file) | Membuat anotasi stempel karet. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_stream) | Membuat anotasi stempel karet. |
| delete_image(page_number, index) | Menghapus gambar yang ditentukan pada halaman yang ditentukan. |
| delete_image() | Menghapus gambar yang ditentukan pada halaman yang ditentukan. |
| replace_text(src_string, the_page, dest_string, text_state) | Mengganti teks dalam file PDF pada halaman yang ditentukan. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) objek (keluarga font, warna) dapat ditentukan untuk teks yang akan diganti. |
| replace_text(src_string, dest_string) | Mengganti teks dalam file PDF pada halaman yang ditentukan. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) objek (keluarga font, warna) dapat ditentukan untuk teks yang akan diganti. |
| replace_text(src_string, the_page, dest_string) | Mengganti teks dalam file PDF pada halaman yang ditentukan. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) objek (keluarga font, warna) dapat ditentukan untuk teks yang akan diganti. |
| replace_text(src_string, dest_string, text_state) | Mengganti teks dalam file PDF pada halaman yang ditentukan. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) objek (keluarga font, warna) dapat ditentukan untuk teks yang akan diganti. |
| replace_text(src_string, dest_string, font_size) | Mengganti teks dalam file PDF pada halaman yang ditentukan. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) objek (keluarga font, warna) dapat ditentukan untuk teks yang akan diganti. |
| delete_stamp_by_ids(stamp_ids) | Menghapus stempel dengan ID yang ditentukan dari semua halaman dokumen. |
| delete_stamp_by_ids(page_number, stamp_ids) | Menghapus stempel dengan ID yang ditentukan dari semua halaman dokumen. |
| delete_stamp_by_id(page_number, stamp_id) | Menghapus stempel dengan ID yang ditentukan dari semua halaman dokumen. |
| delete_stamp_by_id(stamp_id) | Menghapus stempel dengan ID yang ditentukan dari semua halaman dokumen. |
| close() | Menutup dokumen yang dibuka. |
| extract_link() | Mengekstrak koleksi instance Link yang terdapat dalam dokumen PDF. |
| create_java_script_link(code, rect, original_page, color) | Membuat tautan ke JavaScript dalam dokumen PDF. |
| create_text(rect, title, contents, open, icon, page) | Membuat anotasi teks dalam dokumen PDF |
| create_free_text(rect, contents, page) | Membuat anotasi teks bebas dalam dokumen PDF |
| create_markup(rect, contents, type, page, clr) | Membuat anotasi markup di dokumen PDF |
| create_popup(rect, contents, open, page) | Membuat anotasi popup dalam dokumen PDF |
| delete_attachments() | Menghapus semua lampiran dalam dokumen PDF. |
| create_line(rect, contents, x1, y1, x2, y2, page, border, clr, border_style, dash_array, le_array) | Membuat anotasi garis. |
| create_square_circle(rect, contents, clr, square, page, border_width) | Membuat anotasi persegi-lingkaran. |
| draw_curve(line_info, page, annot_rect, annot_contents) | Membuat anotasi kurva. |
| create_polygon(line_info, page, annot_rect, annot_contents) | Membuat anotasi poligon. |
| create_poly_line(line_info, page, annot_rect, annot_contents) | Membuat anotasi polyline. |
| create_caret(page, annot_rect, caret_rect, symbol, annot_contents, color) | Membuat anotasi caret. |
| create_bookmarks_action(title, color, bold_flag, italic_flag, file, action_type, destination) | Membuat bookmark dengan aksi yang ditentukan. |
| add_document_additional_action(event_type, code) | Menambahkan aksi tambahan untuk peristiwa dokumen. |
| remove_document_open_action() | Menghapus aksi buka dari dokumen. Operasi ini berguna saat menggabungkan beberapa dokumen yang menggunakan aksi 'GoTo' eksplisit saat startup. |
| change_viewer_preference(viewer_attribution) | Mengubah preferensi tampilan. |
| get_viewer_preference() | Mengembalikan preferensi tampilan. |
| replace_image(page_number, index, image_file) | Mengganti gambar yang ditentukan pada halaman yang ditentukan dalam dokumen PDF dengan gambar lain. |
| create_movie(rect, file_path, page) | Membuat Anotasi Film. |
| create_sound(rect, file_path, name, page, rate) | Membuat Anotasi Suara. |
| delete_stamp(page_number, index) | Menghapus beberapa stempel pada halaman yang ditentukan berdasarkan indeks stempel. |
| hide_stamp_by_id(page_number, stamp_id) | Menyembunyikan stempel. Setelah disembunyikan, visibilitas stempel dapat dipulihkan dengan metode ShowStampById. |
| show_stamp_by_id(page_number, stamp_id) | Menampilkan stempel yang disembunyikan oleh HiddenStampById. |
| move_stamp_by_id(page_number, stamp_id, x, y) | Mengubah posisi stempel pada halaman. |
| move_stamp(page_number, stamp_index, x, y) | Mengubah posisi stempel pada halaman. |
| get_stamps(page_number) | Mengembalikan array stempel pada halaman. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

