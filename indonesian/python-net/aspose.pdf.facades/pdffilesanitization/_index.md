---
title: "PdfFileSanitization"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili API sanitasi dan pemulihan.<br/>            Gunakan jika Anda tidak dapat membuat/membuka dokumen dengan cara lain."
type: docs
weight: 290
url: /id/python-net/aspose.pdf.facades/pdffilesanitization/
---

## PdfFileSanitization class

Mewakili API sanitasi dan pemulihan.<br/>            Gunakan jika Anda tidak dapat membuat/membuka dokumen dengan cara lain.

Tipe PdfFileSanitization menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfFileSanitization() | Menginisialisasi instance baru dari kelas PdfFileSanitization |
## Properti
| Nama | Deskripsi |
| :- | :- |
| document | Mendapatkan facade dokumen yang sedang diproses. |
| log | Setelah file disimpan Anda dapat memeriksa apa yang telah dilakukan pada file. |
| use_trim_top | Mengizinkan penghapusan data sebelum data pdf. |
| use_trim_bottom | Mengizinkan penghapusan data setelah data pdf |
| use_rebuild_xref_and_trailer | Mengizinkan pembuatan xref dan trailer baru untuk dokumen. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| bind_pdf(input_file) | Mengikat file Pdf untuk Sanitasi. |
| bind_pdf(input_stream) | Mengikat aliran Pdf untuk Sanitasi. |
| bind_pdf(src_doc) | Menginisialisasi facade. |
| save(output_file) | Menyimpan PDF hasil ke file. |
| save(output_stream) | Menyimpan PDF hasil ke aliran. |
| close() | Menutup antarmuka. |
| recover() | Memulihkan dokumen.<br/>            Gunakan properti untuk menyesuaikan. |
| trim_top() | Menghapus data sebelum %PDF. |
| trim_bottom() | Menghapus data setelah %%EOF terakhir. |
| rebuild_xref_and_trailer() | Menghapus xref lama dengan trailer dan membuat xref baru dengan trailer. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

