---
title: "TextFragment"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili fragmen teks Pdf."
type: docs
weight: 390
url: /id/python-net/aspose.pdf.text/textfragment/
---

## TextFragment class

Mewakili fragmen teks Pdf.

Tipe TextFragment menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| TextFragment() | Menginisialisasi instance baru dari objek [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| TextFragment(tab_stops) | Menginisialisasi instance baru dari kelas TextFragment |
| TextFragment(text) | Menginisialisasi instance baru dari kelas TextFragment |
| TextFragment(text, tab_stops) | Menginisialisasi instance baru dari kelas TextFragment |
## Properti
| Nama | Deskripsi |
| :- | :- |
| vertical_alignment | Mendapatkan atau mengatur perataan vertikal fragmen teks. |
| horizontal_alignment | Mendapatkan atau mengatur perataan horizontal fragmen teks. |
| margin | Mendapatkan atau mengatur margin luar untuk paragraf (untuk pembuatan pdf) |
| is_first_paragraph_in_column | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya.<br/>            Defaultnya false. (untuk pembuatan pdf) |
| is_kept_with_next | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya.<br/>            Defaultnya false. (untuk pembuatan pdf) |
| is_in_new_page | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru.<br/>            Defaultnya false. (untuk pembuatan pdf) |
| is_in_line_paragraph | Mendapatkan atau mengatur apakah paragraf bersifat inline.<br/>            Defaultnya false. (untuk pembuatan pdf) |
| hyperlink | Mengatur hyperlink fragmen |
| z_index | Mendapatkan atau mengatur nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar <br/>            akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif <br/>            akan ditempatkan di belakang teks pada halaman. |
| replace_options | Mendapatkan opsi penggantian teks. Opsi-opsi tersebut menentukan perilaku ketika teks fragmen diganti menjadi lebih pendek/panjang. |
| text | Mendapatkan atau mengatur objek teks string yang direpresentasikan oleh objek [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| text_state | Mendapatkan atau mengatur keadaan teks untuk teks yang direpresentasikan oleh objek [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| segments | Mendapatkan segmen teks untuk [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) saat ini. |
| position | Mendapatkan atau mengatur posisi teks untuk teks, yang direpresentasikan dengan objek [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| baseline_position | Mendapatkan posisi teks untuk teks, yang direpresentasikan dengan objek [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/).<br/>            YIndent dari struktur Position mewakili koordinat baseline fragmen teks. |
| rectangle | Mendapatkan persegi panjang TextFragment |
| halaman | Mendapatkan halaman yang berisi TextFragment |
| formulir | Mendapatkan objek formulir yang berisi TextFragment |
| wrap_lines_count | Mendapatkan atau mengatur wrap lines count untuk paragraf ini (hanya untuk pembuatan pdf) |
| end_note | Mendapatkan atau mengatur catatan akhir paragraf (hanya untuk pembuatan pdf) |
| foot_note | Mendapatkan atau mengatur catatan kaki paragraf (hanya untuk pembuatan pdf) |
## Metode
| Nama | Deskripsi |
| :- | :- |
| clone() | Klon fragmen. |
| isolate_text_segments(start_index, length) | Mendapatkan [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(s) yang mewakili bagian tertentu dari teks [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| clone_with_segments() | Klon fragmen dengan semua segmen. |

### Lihat Juga

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

