---
title: "Tabel"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili tabel yang dapat ditambahkan ke halaman."
type: docs
weight: 1480
url: /id/python-net/aspose.pdf/table/
---

## Table class

Mewakili tabel yang dapat ditambahkan ke halaman.

Tipe Tabel menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| Table() | Menginisialisasi instance baru dari kelas Tabel |
## Properti
| Nama | Deskripsi |
| :- | :- |
| vertical_alignment | Mendapatkan atau mengatur perataan vertikal paragraf |
| horizontal_alignment | Mendapatkan atau mengatur perataan horizontal paragraf |
| margin | Mendapatkan atau mengatur margin luar untuk paragraf (untuk pembuatan pdf) |
| is_first_paragraph_in_column | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya.<br/>            Defaultnya false. (untuk pembuatan pdf) |
| is_kept_with_next | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya.<br/>            Defaultnya false. (untuk pembuatan pdf) |
| is_in_new_page | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru.<br/>            Defaultnya false. (untuk pembuatan pdf) |
| is_in_line_paragraph | Mendapatkan atau mengatur apakah paragraf bersifat inline.<br/>            Defaultnya false. (untuk pembuatan pdf) |
| hyperlink | Mendapatkan atau mengatur hyperlink fragmen (untuk generator pdf). |
| z_index | Mendapatkan atau mengatur nilai int yang menunjukkan urutan Z dari grafik. Grafik dengan ZIndex yang lebih besar <br/>            akan ditempatkan di atas grafik dengan ZIndex yang lebih kecil. ZIndex dapat bernilai negatif. Grafik dengan ZIndex negatif <br/>            akan ditempatkan di belakang teks pada halaman. |
| background_color | Mendapatkan atau mengatur warna latar belakang tabel |
| break_text | Mendapatkan atau mengatur teks jeda untuk tabel |
| corner_style | Mendapatkan atau mengatur gaya sudut batas. |
| repeating_rows_style | Mendapatkan gaya untuk baris yang berulang |
| repeating_columns_count | Mendapatkan atau mengatur jumlah maksimum kolom untuk tabel |
| repeating_rows_count | Mendapatkan jumlah baris pertama yang diulang untuk beberapa halaman |
| column_widths | Mendapatkan lebar kolom tabel. |
| broken | Mendapatkan atau mengatur pecahan vertikal tabel; |
| default_cell_border | Mendapatkan batas sel default; |
| default_column_width | Mendapatkan batas sel default; |
| baris | Mendapatkan baris-baris tabel. |
| batas | Mendapatkan atau mengatur batas. |
| default_cell_padding | Mendapatkan atau mengatur padding sel default. |
| default_cell_text_state | Mendapatkan atau mengatur status teks sel default. |
| perataan | Mendapatkan atau mengatur perataan tabel. |
| left | Mendapatkan atau mengatur koordinat kiri tabel. |
| top | Mendapatkan atau mengatur koordinat atas tabel. |
| is_broken | Mendapatkan atau mengatur apakah tabel rusak - akan dipotong untuk halaman berikutnya. |
| is_borders_included | Mendapatkan atau mengatur batas yang termasuk dalam lebar kolom. |
| column_adjustment | Mendapatkan atau mengatur penyesuaian kolom tabel. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| clone() | Kloning tabel. |
| get_width() | Dapatkan lebar. |
| get_height(parent_page) | Dapatkan tinggi. |
| set_column_text_state(col_number, text_state) | Atur tinggi. |
| import_array(imported_array, first_filled_row, first_filled_column, is_left_columns_filled) | Mengimpor array satu dimensi data ke dalam tabel. Impor menempatkan satu sel untuk setiap item array dan<br/>              mulai dari baris dan kolom yang ditentukan dalam parameter. Selama impor, jika terdeteksi bahwa baris yang diperlukan<br/>              masih tidak ada (misalnya tabel target terlalu kecil untuk menampung semua data), baris yang diperlukan akan dibuat |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

