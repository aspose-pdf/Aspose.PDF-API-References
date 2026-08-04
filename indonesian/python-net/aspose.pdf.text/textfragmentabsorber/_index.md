---
title: "TextFragmentAbsorber"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili objek absorber dari fragmen teks.<br/>            Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/)."
type: docs
weight: 400
url: /id/python-net/aspose.pdf.text/textfragmentabsorber/
---

## TextFragmentAbsorber class

Mewakili objek absorber dari fragmen teks.<br/>            Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/).

Tipe TextFragmentAbsorber menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| TextFragmentAbsorber() | Menginisialisasi instance baru dari [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) yang melakukan pencarian semua segmen teks pada dokumen atau halaman. |
| TextFragmentAbsorber(text_edit_options) | Menginisialisasi instance baru dari kelas TextFragmentAbsorber |
| TextFragmentAbsorber(phrase) | Menginisialisasi instance baru dari kelas TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options) | Menginisialisasi instance baru dari kelas TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_search_options, text_edit_options) | Menginisialisasi instance baru dari kelas TextFragmentAbsorber |
| TextFragmentAbsorber(phrase, text_edit_options) | Menginisialisasi instance baru dari kelas TextFragmentAbsorber |
## Properti
| Nama | Deskripsi |
| :- | :- |
| text | Mendapatkan teks yang diekstrak yang diambil oleh [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) pada dokumen atau halaman PDF. |
| has_errors | Nilai menunjukkan apakah kesalahan ditemukan selama ekstraksi teks.<br/>            Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan hal ini dapat menurunkan kinerja. |
| errors | Daftar objek [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/). Ini berisi informasi tentang kesalahan yang ditemukan selama ekstraksi teks.<br/>            Pencarian kesalahan hanya akan dilakukan jika TextSearchOptions.LogTextExtractionErrors = true; Dan hal ini dapat menurunkan kinerja. |
| extraction_options | Mendapatkan atau mengatur opsi ekstraksi teks. |
| text_search_options | Mendapatkan atau mengatur opsi pencarian. Opsi tersebut memungkinkan pencarian menggunakan ekspresi reguler. |
| text_fragments | Mendapatkan koleksi kemunculan pencarian yang disajikan dengan objek [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| phrase | Mendapatkan atau mengatur frasa yang dicari oleh [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) pada dokumen PDF atau halaman. |
| text_edit_options | Mendapatkan atau mengatur opsi penyuntingan teks. Opsi tersebut mendefinisikan perilaku khusus ketika simbol yang diminta tidak dapat ditulis dengan font. |
| text_replace_options | Mendapatkan atau mengatur opsi penggantian teks. Opsi tersebut mendefinisikan perilaku ketika teks fragmen diganti menjadi lebih pendek/panjang. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| visit(page) | Melakukan pencarian pada halaman yang ditentukan. |
| visit(pdf) | Melakukan pencarian pada dokumen yang ditentukan. |
| visit(x_form) | Melakukan pencarian pada objek formulir yang ditentukan. |
| apply_for_all_fragments(font) | Menerapkan font untuk semua fragmen teks yang telah diserap. Ini bekerja lebih cepat daripada melakukan perulangan melalui fragmen jika semua fragmen pada halaman(s) telah diserap. Jika tidak, cara kerjanya mirip dengan perulangan. |
| apply_for_all_fragments(font_size) | Menerapkan ukuran font untuk semua fragmen teks yang telah diserap. Ini bekerja lebih cepat daripada melakukan perulangan melalui fragmen jika semua fragmen pada halaman(s) telah diserap. Jika tidak, cara kerjanya mirip dengan perulangan. |
| apply_for_all_fragments(font, font_size) | Menerapkan font dan ukuran untuk semua fragmen teks yang telah diserap. Ini bekerja lebih cepat daripada melakukan perulangan melalui fragmen jika semua fragmen pada halaman(s) telah diserap. Jika tidak, cara kerjanya mirip dengan perulangan. |
| remove_all_text(page) | Menghapus semua teks dari halaman yang ditentukan. |
| remove_all_text(page, rect) | Menghapus teks di dalam persegi panjang yang ditentukan dari halaman yang ditentukan. |
| remove_all_text(document) | Menghapus semua teks dari dokumen. |
| reset() | Menghapus koleksi TextFragments dari objek [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) ini. |

### Lihat Juga

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

