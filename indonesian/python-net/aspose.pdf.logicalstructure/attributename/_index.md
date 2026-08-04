---
title: "AttributeName"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili kelas untuk Nilai Nama Atribut."
type: docs
weight: 50
url: /id/python-net/aspose.pdf.logicalstructure/attributename/
---

## AttributeName class

Mewakili kelas untuk Nilai Nama Atribut.

Tipe AttributeName menampilkan anggota-anggota berikut:
## Properti
| Nama | Deskripsi |
| :- | :- |
| name | Mendapatkan nilai nama atribut. |
| attribute_key | Mendapatkan kunci atribut. |
| PLACEMENT_BLOCK | Attribute Placement: Block - Ditumpuk dalam arah blok-progresi di dalam area referensi yang membungkus atau BLSE induk. |
| PLACEMENT_INLINE | Attribute Placement: Inline - Dipadatkan dalam arah inline-progresi di dalam BLSE yang membungkus. |
| PLACEMENT_BEFORE | Attribute Placement: Before - Ditempatkan sehingga tepi sebelum dari persegi alokasi elemen bertepatan dengan tepi sebelum area referensi terdekat yang membungkus. |
| PLACEMENT_START | Attribute Placement: Start - Ditempatkan sehingga tepi mulai dari persegi alokasi elemen bertepatan dengan tepi mulai area referensi terdekat yang membungkus. |
| PLACEMENT_END | Attribute Placement: End - Ditempatkan sehingga tepi akhir dari persegi alokasi elemen bertepatan dengan tepi akhir area referensi terdekat yang membungkus. |
| WRITING_MODE_LR_TB | Attribute WritingMode: LrTb - Progresi inline dari kiri ke kanan; progresi blok dari atas ke bawah. Ini adalah mode penulisan tipikal untuk sistem penulisan Barat. |
| WRITING_MODE_RL_TB | Attribute WritingMode: RlTb - Progresi inline dari kanan ke kiri; progresi blok dari atas ke bawah. Ini adalah mode penulisan tipikal untuk sistem penulisan Arab dan Ibrani. |
| WRITING_MODE_TB_RL | Attribute WritingMode: TbRl - Progresi inline dari atas ke bawah; progresi blok dari kanan ke kiri. Ini adalah mode penulisan tipikal untuk sistem penulisan Cina dan Jepang. |
| BORDER_STYLE_NONE | Attribute BorderStyle: None - Tanpa batas. Memaksa nilai terhitung BorderThicknessto menjadi 0. |
| BORDER_STYLE_HIDDEN | Attribute BorderStyle: Hidden - Sama seperti None, kecuali dalam hal resolusi konflik batas untuk elemen tabel. |
| BORDER_STYLE_DOTTED | Attribute BorderStyle: Dotted - Batasnya berupa rangkaian titik. |
| BORDER_STYLE_DASHED | Atribut BorderStyle: Dashed - Garis batas adalah serangkaian segmen garis pendek. |
| BORDER_STYLE_SOLID | Atribut BorderStyle: Solid - Garis batas adalah satu segmen garis. |
| BORDER_STYLE_DOUBLE | Atribut BorderStyle: Double - Garis batas terdiri dari dua garis solid. Jumlah kedua garis dan ruang di antara keduanya sama dengan nilai BorderThickness. |
| BORDER_STYLE_GROOVE | Atribut BorderStyle: Groove - Garis batas tampak seolah-olah dipahat ke dalam kanvas. |
| BORDER_STYLE_RIDGE | Atribut BorderStyle: Ridge - Garis batas tampak seolah-olah keluar dari kanvas (berlawanan dengan Groove). |
| BORDER_STYLE_INSET | Atribut BorderStyle: Inset - Garis batas membuat seluruh kotak tampak seolah-olah tertanam di dalam kanvas. |
| BORDER_STYLE_OUTSET | Atribut BorderStyle: Outset - Garis batas membuat seluruh kotak tampak seolah-olah keluar dari kanvas (berlawanan dengan Inset). |
| TEXT_ALIGN_START | Atribut TextAlign: Start - Diratakan dengan tepi awal. |
| TEXT_ALIGN_CENTER | Atribut TextAlign: Center - Diposisikan di tengah antara tepi awal dan akhir. |
| TEXT_ALIGN_END | Atribut TextAlign: End - Diratakan dengan tepi akhir. |
| TEXT_ALIGN_JUSTIFY | Atribut TextAlign: Justify - Diratakan dengan kedua tepi awal dan akhir, dengan spasi internal dalam setiap baris diperluas, jika diperlukan, untuk mencapai perataan tersebut. Baris terakhir (atau satu-satunya) hanya akan diratakan dengan tepi awal. |
| WIDTH_AUTO | Atribut Width: Auto - lebar elemen akan ditentukan oleh lebar intrinsik kontennya. |
| HEIGHT_AUTO | Atribut Height: Auto - tinggi elemen akan ditentukan oleh tinggi intrinsik kontennya. |
| BLOCK_ALIGN_BEFORE | Atribut BlockAlign: Before - Tepi sebelum dari persegi alokasi anak pertama diratakan dengan persegi konten sel tabel. |
| BLOCK_ALIGN_MIDDLE | Atribut BlockAlign: Middle- Anak-anak dipusatkan di dalam sel tabel. Jarak antara tepi before dari persegi alokasi anak pertama dan tepi konten sel tabel harus sama dengan jarak antara tepi after dari persegi alokasi anak terakhir dan tepi konten sel tabel. |
| BLOCK_ALIGN_AFTER | Atribut BlockAlign: After - Tepi after dari persegi alokasi anak terakhir diselaraskan dengan tepi konten sel tabel. |
| BLOCK_ALIGN_JUSTIFY | Atribut BlockAlign: Justify - Anak-anak diselaraskan dengan kedua tepi before dan after dari persegi konten sel tabel. Anak pertama ditempatkan seperti yang dijelaskan untuk Before dan anak terakhir seperti yang dijelaskan untuk After, dengan jarak yang sama antar anak. Jika hanya ada satu anak, ia akan diselaraskan hanya dengan tepi before, seperti pada Before. |
| INLINE_ALIGN_START | Atribut InlineAlign: Start - Tepi start dari setiap persegi alokasi anak diselaraskan dengan tepi konten sel tabel. |
| INLINE_ALIGN_CENTER | Atribut InlineAlign: Center - Setiap anak dipusatkan di dalam sel tabel. Jarak antara tepi start dari persegi alokasi anak dan tepi konten sel tabel harus sama dengan jarak antara tepi end mereka. |
| INLINE_ALIGN_END | Atribut InlineAlign: End - Tepi end dari setiap persegi alokasi anak diselaraskan dengan tepi konten sel tabel. |
| LINE_HEIGHT_NORMAL | Atribut LineHeight: Normal - Sesuaikan tinggi baris untuk menyertakan nilai nonzero apa pun yang ditentukan untuk BaselineShift. |
| LINE_HEIGHT_AUTO | Atribut LineHeight: Auto - Penyesuaian untuk nilai BaselineShift tidak akan dilakukan. |
| TEXT_DECORATION_TYPE_NONE | Atribut TextDecorationType: None - Tidak ada dekorasi teks. |
| TEXT_DECORATION_TYPE_UNDERLINE | Atribut TextDecorationType: Underline - Garis di bawah teks. |
| TEXT_DECORATION_TYPE_OVERLINE | Atribut TextDecorationType: Overline - Garis di atas teks. |
| TEXT_DECORATION_TYPE_LINE_THROUGH | Atribut TextDecorationType: LineThrough - Garis melalui tengah teks. |
| RUBY_ALIGN_START | Attribute RubyAlign: Start - Konten harus disejajarkan pada tepi awal dalam arah inline-progression. |
| RUBY_ALIGN_CENTER | Attribute RubyAlign: Center - Konten harus dipusatkan dalam arah inline-progression. |
| RUBY_ALIGN_END | Attribute RubyAlign: End - Konten harus disejajarkan pada tepi akhir dalam arah inline-progression. |
| RUBY_ALIGN_JUSTIFY | Attribute RubyAlign: Justify - Konten harus diperluas untuk mengisi lebar yang tersedia dalam arah inline-progression. |
| RUBY_ALIGN_DISTRIBUTE | Attribute RubyAlign: Distribute - Konten harus diperluas untuk mengisi lebar yang tersedia dalam arah inline-progression. Namun, spasi juga harus disisipkan pada tepi awal dan tepi akhir teks. Jarak spasi harus didistribusikan menggunakan rasio 1:2:1 (start:infix:end). Rasio tersebut akan diubah menjadi 0:1:1 jika ruby muncul di awal baris teks atau menjadi 1:1:0 jika ruby muncul di akhir baris teks. |
| RUBY_POSITION_BEFORE | Attribute RubyPosition: Before - Konten RT harus disejajarkan sepanjang tepi before elemen. |
| RUBY_POSITION_AFTER | Attribute RubyPosition: After - Konten RT harus disejajarkan sepanjang tepi after elemen. |
| RUBY_POSITION_WARICHU | Attribute RubyPosition: Warichu - Elemen RT dan RP terkait harus diformat sebagai warichu, mengikuti elemen RB. |
| RUBY_POSITION_INLINE | Attribute RubyPosition: Inline - Elemen RT dan RP terkait harus diformat sebagai komentar dalam kurung, mengikuti elemen RB. |
| GLYPH_ORIENTATION_VERTICAL_AUTO | Attribute GlyphOrientationVertical: Auto - Menentukan orientasi default untuk teks, tergantung apakah teks tersebut fullwidth (seluas tingginya). |
| LIST_NUMBERING_NONE | Attribute ListNumbering: None - Tidak ada penomoran otomatis; elemen Lbl (jika ada) berisi teks sewenang-wenang yang tidak tunduk pada skema penomoran apa pun. |
| LIST_NUMBERING_DISC | Attribute ListNumbering: Disc - Bullet bulat padat. |
| LIST_NUMBERING_CIRCLE | Attribute ListNumbering: Circle - Bullet bulat terbuka. |
| LIST_NUMBERING_SQUARE | Atribut ListNumbering: Square - Peluru kotak padat. |
| LIST_NUMBERING_DECIMAL | Atribut ListNumbering: Decimal - Angka Arab desimal (1-9, 10-99, ...). |
| LIST_NUMBERING_UPPER_ROMAN | Atribut ListNumbering: UpperRoman - Numeral Romawi huruf besar (I, II, III, IV, ...). |
| LIST_NUMBERING_LOWER_ROMAN | Atribut ListNumbering: LowerRoman - Numeral Romawi huruf kecil (i, ii, iii, iv, ...). |
| LIST_NUMBERING_UPPER_ALPHA | Atribut ListNumbering: UpperAlpha - Huruf kapital (A, B, C, ...). |
| LIST_NUMBERING_LOWER_ALPHA | Atribut ListNumbering: LowerAlpha - Huruf kecil (a, b, c, ...). |
| ROLE_RB | Atribut Role: rb - Tombol radio. |
| ROLE_CB | Atribut Role: cb - Kotak centang. |
| ROLE_PB | Atribut Role: pb - Tombol tekan. |
| ROLE_TV | Atribut Role: tv - Kolom nilai teks. |
| CHECKED_ON | Atribut checked: On - Status tombol radio atau kotak centang. |
| CHECKED_OFF | Atribut checked: Off - Status tombol radio atau kotak centang. |
| CHECKED_NEUTRAL | Atribut diperiksa: Netral - Status tombol radio atau kotak centang. |
| SCOPE_ROW | Cakupan Atribut: Baris. |
| SCOPE_COLUMN | Cakupan Atribut: Kolom. |
| SCOPE_BOTH | Cakupan Atribut: Kedua. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| from_name_attribute_key(name, attribute_key) | Mendapatkan nama atribut untuk kunci atribut. |

### Lihat Juga

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

