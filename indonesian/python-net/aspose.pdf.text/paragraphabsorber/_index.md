---
title: "ParagraphAbsorber"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili objek absorber dari objek struktur halaman seperti bagian dan paragraf.<br/>            Melakukan pencarian untuk bagian dan paragraf teks serta menyediakan akses ke persegi panjang dan polydons yang menggambarkannya dalam ruang koordinat teks. <br/>            Juga melakukan pencarian segmen teks dan menyediakan akses ke hasil pencarian melalui koleksi TextFragments yang dikelompokkan berdasarkan elemen struktur."
type: docs
weight: 240
url: /id/python-net/aspose.pdf.text/paragraphabsorber/
---

## ParagraphAbsorber class

Mewakili objek absorber dari objek struktur halaman seperti bagian dan paragraf.<br/>            Melakukan pencarian untuk bagian dan paragraf teks serta menyediakan akses ke persegi panjang dan polydons yang menggambarkannya dalam ruang koordinat teks. <br/>            Juga melakukan pencarian segmen teks dan menyediakan akses ke hasil pencarian melalui koleksi TextFragments yang dikelompokkan berdasarkan elemen struktur.

Tipe ParagraphAbsorber menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| ParagraphAbsorber() | Menginisialisasi instance baru dari [ParagraphAbsorber](/pdf/python-net/aspose.pdf.text/paragraphabsorber/) yang melakukan pencarian bagian/paragraf dari dokumen atau halaman. |
| ParagraphAbsorber(sections_search_depth) | Menginisialisasi instance baru dari kelas ParagraphAbsorber |
## Properti
| Nama | Deskripsi |
| :- | :- |
| page_markups | Mendapatkan koleksi [PageMarkup](/pdf/python-net/aspose.pdf.text/pagemarkup/) yang telah diserap. |
| sections_search_depth | Mendapatkan atau mengatur nilai yang menentukan berapa kali pencarian berurutan untuk elemen struktur yang lebih halus akan dilakukan.<br/>            Kedalaman pencarian default adalah 3.<br/>            Artinya tiga pencarian untuk bagian yang dibagi secara horizontal (header, paragraf, dll) dan tiga pencarian untuk bagian yang dibagi secara vertikal (kolom). |
| is_multicolumn_paragraphs_allowed | Mendapatkan atau mengatur nilai yang menunjukkan apakah baris teks awal dari bagian berikutnya dapat diperlakukan sebagai kelanjutan dari paragraf terakhir pada bagian sebelumnya. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| visit(doc) | Melakukan pencarian bagian dan paragraf pada [Document](/pdf/python-net/aspose.pdf/document/) yang ditentukan. |
| visit(page) | Melakukan pencarian pada [Page](/pdf/python-net/aspose.pdf/page/) yang ditentukan. |

### Lihat Juga

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

