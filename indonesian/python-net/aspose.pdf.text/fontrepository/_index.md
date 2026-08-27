---
title: "FontRepository"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Melakukan pencarian font. Mencari di font yang diinstal sistem dan font Pdf standar.<br/>             Juga menyediakan fungsionalitas untuk membuka font khusus."
type: docs
weight: 130
url: /id/python-net/aspose.pdf.text/fontrepository/
---

## FontRepository class

Melakukan pencarian font. Mencari di font yang diinstal sistem dan font Pdf standar.<br/>             Juga menyediakan fungsionalitas untuk membuka font khusus.

Tipe FontRepository menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| FontRepository() | Menginisialisasi instance baru dari kelas FontRepository |
## Properti
| Nama | Deskripsi |
| :- | :- |
| substitutions | Mendapatkan koleksi strategi substitusi font. |
| sources | Mendapatkan koleksi sumber font. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| find_font(font_name) | Mencari dan mengembalikan font dengan nama font yang ditentukan. |
| find_font(font_name, ignore_case) | Mencari dan mengembalikan font dengan nama font yang ditentukan dengan mengabaikan atau menghormati sensitivitas huruf. |
| find_font(font_family_name, stl) | Mencari dan mengembalikan font dengan nama font dan gaya font yang ditentukan. |
| find_font(font_family_name, stl, ignore_case) | Mencari dan mengembalikan font dengan nama font dan gaya font yang ditentukan <br/>             mengabaikan atau menghormati sensitivitas huruf. |
| open_font(font_stream, font_type) | Membuka font dengan aliran font yang ditentukan. |
| open_font(font_file_path) | Membuka font dengan jalur file font yang ditentukan. |
| open_font(font_file_path, metrics_file_path) | Membuka font dengan jalur file font yang ditentukan. |
| load_fonts() | Memuat font yang terpasang di sistem dan font Pdf standar. Metode ini dirancang untuk mempercepat proses pemuatan font.<br/>            Secara default font dimuat pada permintaan pertama untuk setiap font. Penggunaan metode ini memuat font sistem dan font Pdf standar<br/>            segera sebelum dokumen Pdf apa pun dibuka. |
| reload_fonts() | Memuat ulang semua font yang ditentukan oleh properti [sources](/pdf/python-net/aspose.pdf.text/fontrepository/) |

### Lihat Juga

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

