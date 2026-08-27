---
title: "TextAbsorber"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili objek absorber dari teks.<br/>            Melakukan ekstraksi teks dan menyediakan akses ke hasil melalui objek [text](/pdf/python-net/aspose.pdf.text/textabsorber/)."
type: docs
weight: 320
url: /id/python-net/aspose.pdf.text/textabsorber/
---

## TextAbsorber class

Mewakili objek absorber dari teks.<br/>            Melakukan ekstraksi teks dan menyediakan akses ke hasil melalui objek [text](/pdf/python-net/aspose.pdf.text/textabsorber/).

Tipe TextAbsorber mengekspos anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| TextAbsorber() | Menginisialisasi instance baru dari [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/). |
| TextAbsorber(extraction_options) | Menginisialisasi instance baru dari kelas TextAbsorber |
| TextAbsorber(extraction_options, text_search_options) | Menginisialisasi instance baru dari kelas TextAbsorber |
| TextAbsorber(text_search_options) | Menginisialisasi instance baru dari kelas TextAbsorber |
## Properti
| Nama | Deskripsi |
| :- | :- |
| text | Mendapatkan teks yang diekstrak yang diambil oleh [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) pada dokumen atau halaman PDF. |
| has_errors | Nilai menunjukkan apakah kesalahan ditemukan selama ekstraksi teks.<br/>            Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan hal ini dapat menurunkan kinerja. |
| errors | Daftar objek [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/). Ini berisi informasi tentang kesalahan yang ditemukan selama ekstraksi teks.<br/>            Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan hal ini dapat menurunkan kinerja. |
| extraction_options | Mendapatkan atau mengatur opsi ekstraksi teks. |
| text_search_options | Mendapatkan atau mengatur opsi pencarian teks. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| visit(page) | Mengekstrak teks pada halaman yang ditentukan |
| visit(form) | Mengekstrak teks pada XForm yang ditentukan. |
| visit(pdf) | Mengekstrak teks pada dokumen yang ditentukan |

### Lihat Juga

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

