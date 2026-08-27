---
title: "Heading"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili heading."
type: docs
weight: 460
url: /id/python-net/aspose.pdf/heading/
---

## Heading class

Mewakili heading.

Tipe Heading memperlihatkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| Heading(level) | Menginisialisasi instance baru dari kelas Heading |
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
| toc_page | Mendapatkan halaman yang berisi judul ini. |
| top | Mendapatkan Y atas dari judul-judul ini. |
| start_number | Mendapatkan nomor awal judul. |
| is_auto_sequence | Mendapatkan apakah judul harus dinomori secara otomatis. |
| is_in_list | Mendapatkan apakah judul harus berada dalam daftar isi. |
| destination_page | Mendapatkan halaman tujuan. |
| level | Mendapatkan tingkat. |
| style | Mendapatkan atau mengatur gaya. |
| user_label | Mendapatkan atau mengatur label pengguna. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| clone() | Menggandakan judul. |
| isolate_text_segments(start_index, length) | Mendapatkan [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(s) yang mewakili bagian tertentu dari teks [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| clone_with_segments() | Menggandakan judul dengan semua segmen. |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

