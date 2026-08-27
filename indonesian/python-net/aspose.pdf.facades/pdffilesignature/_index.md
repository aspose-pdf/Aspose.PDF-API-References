---
title: "PdfFileSignature"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili kelas untuk menandatangani file PDF dengan sertifikat."
type: docs
weight: 310
url: /id/python-net/aspose.pdf.facades/pdffilesignature/
---

## PdfFileSignature class

Mewakili kelas untuk menandatangani file PDF dengan sertifikat.

Tipe PdfFileSignature menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfFileSignature() | Konstruktor kelas PdfFileSignature. |
| PdfFileSignature(input_file) | Menginisialisasi instance baru dari kelas PdfFileSignature |
| PdfFileSignature(input_file, output_file) | Menginisialisasi instance baru dari kelas PdfFileSignature |
| PdfFileSignature(document) | Menginisialisasi instance baru dari kelas PdfFileSignature |
| PdfFileSignature(document, output_file) | Menginisialisasi instance baru dari kelas PdfFileSignature |
## Properti
| Nama | Deskripsi |
| :- | :- |
| document | Mendapatkan facade dokumen yang sedang diproses. |
| signature_appearance | Mengatur atau mengambil tampilan grafis untuk tanda tangan. Nilai properti mewakili nama file gambar. |
| is_ltv_enabled | Mengambil flag LTV yang diaktifkan. |
| is_certified | Mengambil flag yang menentukan apakah dokumen disertifikasi atau tidak. |
| signature_appearance_stream | Mengatur atau mengambil tampilan grafis untuk tanda tangan. Nilai properti mewakili aliran gambar. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| bind_pdf(input_file) | Mengikat file Pdf untuk diedit. |
| bind_pdf(input_stream) | Mengikat aliran Pdf untuk diedit. |
| bind_pdf(src_doc) | Mengikat dokumen PDF untuk diedit. |
| save(output_file) | Menyimpan PDF hasil ke file. |
| save(output_stream) | Menyimpan PDF hasil ke aliran. |
| save() | Menyimpan PDF hasil ke file. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect) | Buat tanda tangan pada dokumen pdf. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Tandatangani dokumen dengan tanda tangan tipe yang diberikan. |
| sign(page, visible, annot_rect, sig) | Tandatangani dokumen dengan tanda tangan tipe yang diberikan. |
| sign(sig_name, sig_reason, sig_contact, sig_location, sig) | Tandatangani dokumen dengan tanda tangan tipe yang diberikan. |
| sign(page, sig_name, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | Tandatangani dokumen dengan tanda tangan tipe yang diberikan. |
| sign(sig_name, sig) | Tandatangani dokumen dengan tanda tangan tipe yang diberikan. |
| certify(page, sig_reason, sig_contact, sig_location, visible, annot_rect, doc_mdp_signature) | Sertifikasi dokumen dengan tanda tangan MDP.<br/>            Data seperti alasan tanda tangan, kontak, dan lokasi harus disediakan oleh properti yang sesuai dari objek Signature sig. |
| certify(sig_name, doc_mdp_signature) | Sertifikasi dokumen dengan tanda tangan MDP.<br/>            Data seperti alasan tanda tangan, kontak, dan lokasi harus disediakan oleh properti yang sesuai dari objek Signature sig. |
| remove_signature(sign_name) | Hapus tanda tangan berdasarkan nama tanda tangan. |
| remove_signature(sign_name, remove_field) | Menghapus tanda tangan berdasarkan nama tanda tangan. |
| close() | Menutup antarmuka. |
| get_access_permissions() | Mengembalikan nilai izin akses dokumen yang disertifikasi oleh tipe tanda tangan MDP. |
| get_sign_names(only_active) | Mendapatkan nama semua tanda tangan yang tidak kosong. |
| get_blank_sign_names() | Mendapatkan nama semua bidang tanda tangan yang kosong. |
| is_contain_signature() | Memeriksa apakah pdf memiliki tanda tangan digital atau tidak. |
| contains_signature() | Memeriksa apakah pdf memiliki tanda tangan digital atau tidak. |
| contains_usage_rights() | Memeriksa apakah pdf memiliki hak penggunaan atau tidak. |
| is_covers_whole_document(sign_name) | Memeriksa apakah tanda tangan mencakup seluruh dokumen. |
| covers_whole_document(sign_name) | Memeriksa apakah tanda tangan mencakup seluruh dokumen. |
| get_revision(sign_name) | Mendapatkan revisi dari sebuah tanda tangan. |
| get_total_revision() | Mendapatkan total revisi. |
| remove_usage_rights() | Menghapus entri hak penggunaan. |
| verify_signed(sign_name) | Memeriksa keabsahan sebuah tanda tangan. |
| get_signer_name(sign_name) | Mendapatkan nama orang atau organisasi yang menandatangani dokumen pdf. |
| get_date_time(sign_name) | Mendapatkan tanggal dan waktu tanda tangan. |
| get_reason(sign_name) | Mendapatkan alasan sebuah tanda tangan. |
| get_location(sign_name) | Mendapatkan lokasi sebuah tanda tangan. |
| get_contact_info(sign_name) | Mendapatkan informasi kontak sebuah tanda tangan. |
| verify_signature(sign_name) | Memeriksa keabsahan sebuah tanda tangan. |
| extract_image(sign_name) | Mengekstrak gambar tanda tangan. |
| extract_certificate(sign_name) | Mengekstrak sertifikat X.509 tunggal tanda tangan sebagai aliran. |
| set_certificate(pfx, pass) | Mengatur file sertifikat dan kata sandi untuk prosedur penandatanganan. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

