---
title: "AttributeName"
linktitle: "AttributeName"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk Nilai Nama Atribut."
type: docs
weight: 20
url: /id/java/com.aspose.pdf.tagged.logicalstructure/attributename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.AttributeName

```
public final class AttributeName extends Object
```

Mewakili kelas untuk Nilai Nama Atribut.

## Fields

| Field | Deskripsi |
| --- | --- |
| [BlockAlign_After](#BlockAlign_After) | Attribute BlockAlign: After - Tepi setelah dari persegi alokasi anak terakhir selaras dengan tepi konten sel tabel. |
| [BlockAlign_Before](#BlockAlign_Before) | Attribute BlockAlign: Before - Tepi sebelum dari persegi alokasi anak pertama selaras dengan tepi konten sel tabel. |
| [BlockAlign_Justify](#BlockAlign_Justify) | Attribute BlockAlign: Justify - Anak-anak selaras dengan kedua tepi sebelum dan setelah dari persegi konten sel tabel. Anak pertama harus ditempatkan seperti yang dijelaskan untuk Before dan anak terakhir seperti yang dijelaskan untuk After, dengan jarak yang sama antar anak. Jika hanya ada satu anak, ia harus selaras hanya dengan tepi sebelum, seperti pada Before. |
| [BlockAlign_Middle](#BlockAlign_Middle) | Attribute BlockAlign: Middle- Anak-anak diposisikan di tengah sel tabel. Jarak antara tepi sebelum persegi alokasi anak pertama dan persegi konten sel tabel harus sama dengan jarak antara tepi setelah persegi alokasi anak terakhir dan persegi konten sel tabel. |
| [BorderStyle_Dashed](#BorderStyle_Dashed) | Attribute BorderStyle: Dashed - Garis batas adalah serangkaian segmen garis pendek. |
| [BorderStyle_Dotted](#BorderStyle_Dotted) | Attribute BorderStyle: Dotted - Garis batas adalah serangkaian titik. |
| [BorderStyle_Double](#BorderStyle_Double) | Attribute BorderStyle: Double - Garis batas terdiri dari dua garis padat. Jumlah kedua garis dan ruang di antara keduanya sama dengan nilai BorderThickness. |
| [BorderStyle_Groove](#BorderStyle_Groove) | Attribute BorderStyle: Groove - Garis batas tampak seolah-olah dipahat ke dalam kanvas. |
| [BorderStyle_Hidden](#BorderStyle_Hidden) | Attribute BorderStyle: Hidden - Sama seperti None, kecuali dalam hal resolusi konflik batas untuk elemen tabel. |
| [BorderStyle_Inset](#BorderStyle_Inset) | Attribute BorderStyle: Inset - Garis batas membuat seluruh kotak tampak seolah-olah tertanam dalam kanvas. |
| [BorderStyle_None](#BorderStyle_None) | Attribute BorderStyle: None - Tidak ada batas. Memaksa nilai yang dihitung dari BorderThicknessto menjadi 0. |
| [BorderStyle_Outset](#BorderStyle_Outset) | Attribute BorderStyle: Outset - Garis batas membuat seluruh kotak tampak seolah-olah keluar dari kanvas (berlawanan dengan Inset). |
| [BorderStyle_Ridge](#BorderStyle_Ridge) | Attribute BorderStyle: Ridge - Garis batas tampak seolah-olah keluar dari kanvas (berlawanan dengan Groove). |
| [BorderStyle_Solid](#BorderStyle_Solid) | Attribute BorderStyle: Solid - Garis batas adalah satu segmen garis tunggal. |
| [Checked_neutral](#Checked_neutral) | Attribute checked: Neutral - Status tombol radio atau kotak centang. |
| [Checked_off](#Checked_off) | Atribut checked: Off - Status tombol radio atau bidang kotak centang. |
| [Checked_on](#Checked_on) | Atribut checked: On - Status tombol radio atau bidang kotak centang. |
| [GlyphOrientationVertical_Auto](#GlyphOrientationVertical_Auto) | Atribut GlyphOrientationVertical: Auto - Menentukan orientasi default untuk teks, tergantung apakah teks tersebut lebar penuh (sepanjang tingginya). |
| [Height_Auto](#Height_Auto) | Atribut Height: Auto - Tinggi elemen akan ditentukan oleh tinggi intrinsik kontennya. |
| [InlineAlign_Center](#InlineAlign_Center) | Atribut InlineAlign: Center - Setiap anak dipusatkan di dalam sel tabel. Jarak antara tepi mulai persegi alokasi anak dan persegi konten sel tabel harus sama dengan jarak antara tepi akhir mereka. |
| [InlineAlign_End](#InlineAlign_End) | Atribut InlineAlign: End - Tepi akhir persegi alokasi setiap anak diselaraskan dengan tepi persegi konten sel tabel. |
| [InlineAlign_Start](#InlineAlign_Start) | Atribut InlineAlign: Start - Tepi mulai persegi alokasi setiap anak diselaraskan dengan tepi persegi konten sel tabel. |
| [LineHeight_Auto](#LineHeight_Auto) | Atribut LineHeight: Auto - Penyesuaian nilai BaselineShift tidak akan dilakukan. |
| [LineHeight_Normal](#LineHeight_Normal) | Atribut LineHeight: Normal - Sesuaikan tinggi baris untuk menyertakan nilai nonnol yang ditentukan untuk BaselineShift. |
| [ListNumbering_Circle](#ListNumbering_Circle) | Atribut ListNumbering: Circle - Bullet bulat terbuka. |
| [ListNumbering_Decimal](#ListNumbering_Decimal) | Atribut ListNumbering: Decimal - Numerik Arab desimal (1-9, 10-99, ...). |
| [ListNumbering_Disc](#ListNumbering_Disc) | Atribut ListNumbering: Disc - Bullet bulat padat. |
| [ListNumbering_LowerAlpha](#ListNumbering_LowerAlpha) | Atribut ListNumbering: LowerAlpha - Huruf kecil (a, b, c, ...). |
| [ListNumbering_LowerRoman](#ListNumbering_LowerRoman) | Atribut ListNumbering: LowerRoman - Numeral Romawi kecil (i, ii, iii, iv, ...). |
| [ListNumbering_None](#ListNumbering_None) | Atribut ListNumbering: None - Tidak ada penomoran otomatis; elemen Lbl (jika ada) berisi teks arbitrer yang tidak tunduk pada skema penomoran apa pun. |
| [ListNumbering_Square](#ListNumbering_Square) | Atribut ListNumbering: Square - Bullet kotak padat. |
| [ListNumbering_UpperAlpha](#ListNumbering_UpperAlpha) | Atribut ListNumbering: UpperAlpha - Huruf kapital (A, B, C, ...). |
| [ListNumbering_UpperRoman](#ListNumbering_UpperRoman) | Atribut ListNumbering: UpperRoman - Numeral Romawi kapital (I, II, III, IV, ...). |
| [Placement_Before](#Placement_Before) | Atribut Placement: Before - Ditempatkan sehingga tepi sebelum persegi alokasi elemen bertepatan dengan tepi area referensi terdekat yang mengelilinginya. |
| [Placement_Block](#Placement_Block) | Atribut Placement: Block - Ditumpuk dalam arah blok-progresi di dalam area referensi yang mengelilingi atau BLSE induk. |
| [Placement_End](#Placement_End) | Atribut Placement: End - Ditempatkan sehingga tepi akhir persegi alokasi elemen bertepatan dengan tepi area referensi terdekat yang mengelilinginya. |
| [Placement_Inline](#Placement_Inline) | Atribut Placement: Inline - Dipadatkan dalam arah inline-progresi di dalam BLSE yang mengelilingi. |
| [Placement_Start](#Placement_Start) | Atribut Placement: Start - Ditempatkan sehingga tepi mulai persegi alokasi elemen bertepatan dengan tepi area referensi terdekat yang mengelilinginya. |
| [Role_cb](#Role_cb) | Atribut Role: cb - Kotak centang. |
| [Role_pb](#Role_pb) | Atribut Role: pb - Tombol tekan. |
| [Role_rb](#Role_rb) | Atribut Role: rb - Tombol radio. |
| [Role_tv](#Role_tv) | Atribut Role: tv - Bidang nilai-teks. |
| [RubyAlign_Center](#RubyAlign_Center) | Atribut RubyAlign: Center - Konten harus dipusatkan dalam arah inline-progression. |
| [RubyAlign_Distribute](#RubyAlign_Distribute) | Atribut RubyAlign: Distribute - Konten harus diperluas untuk mengisi lebar yang tersedia dalam arah inline-progression. Namun, spasi juga harus disisipkan pada tepi awal dan tepi akhir teks. Spasi harus didistribusikan menggunakan rasio 1:2:1 (awal:infix:akhir). Rasio akan diubah menjadi 0:1:1 jika ruby muncul di awal baris teks atau menjadi 1:1:0 jika ruby muncul di akhir baris teks. |
| [RubyAlign_End](#RubyAlign_End) | Atribut RubyAlign: End - Konten harus disejajarkan pada tepi akhir dalam arah inline-progression. |
| [RubyAlign_Justify](#RubyAlign_Justify) | Atribut RubyAlign: Justify - Konten harus diperluas untuk mengisi lebar yang tersedia dalam arah inline-progression. |
| [RubyAlign_Start](#RubyAlign_Start) | Atribut RubyAlign: Start - Konten harus disejajarkan pada tepi awal dalam arah inline-progression. |
| [RubyPosition_After](#RubyPosition_After) | Atribut RubyPosition: After - Konten RT harus disejajarkan sepanjang tepi after elemen. |
| [RubyPosition_Before](#RubyPosition_Before) | Atribut RubyPosition: Before - Konten RT harus disejajarkan sepanjang tepi before elemen. |
| [RubyPosition_Inline](#RubyPosition_Inline) | Atribut RubyPosition: Inline - Elemen RT dan RP terkait harus diformat sebagai komentar dalam tanda kurung, mengikuti elemen RB. |
| [RubyPosition_Warichu](#RubyPosition_Warichu) | Atribut RubyPosition: Warichu - Elemen RT dan RP terkait harus diformat sebagai warichu, mengikuti elemen RB. |
| [Scope_Both](#Scope_Both) | Atribut Scope: Both. |
| [Scope_Column](#Scope_Column) | Atribut Scope: Column. |
| [Scope_Row](#Scope_Row) | Atribut Scope: Row. |
| [TextAlign_Center](#TextAlign_Center) | Atribut TextAlign: Center - Dipusatkan antara tepi awal dan tepi akhir. |
| [TextAlign_End](#TextAlign_End) | Atribut TextAlign: End - Disejajarkan dengan tepi akhir. |
| [TextAlign_Justify](#TextAlign_Justify) | Atribut TextAlign: Justify - Disejajarkan dengan kedua tepi awal dan akhir, dengan spasi internal pada setiap baris diperluas, jika diperlukan, untuk mencapai penyelarasan tersebut. Baris terakhir (atau satu-satunya) harus disejajarkan hanya dengan tepi awal. |
| [TextAlign_Start](#TextAlign_Start) | Atribut TextAlign: Start - Disejajarkan dengan tepi awal. |
| [TextDecorationType_LineThrough](#TextDecorationType_LineThrough) | Atribut TextDecorationType: LineThrough - Garis melalui tengah teks. |
| [TextDecorationType_None](#TextDecorationType_None) | Atribut TextDecorationType: None - Tidak ada dekorasi teks. |
| [TextDecorationType_Overline](#TextDecorationType_Overline) | Atribut TextDecorationType: Overline - Garis di atas teks. |
| [TextDecorationType_Underline](#TextDecorationType_Underline) | Atribut TextDecorationType: Underline - Garis di bawah teks. |
| [Width_Auto](#Width_Auto) | Atribut Width: Auto - lebar elemen akan ditentukan oleh lebar intrinsik kontennya. |
| [WritingMode_LrTb](#WritingMode_LrTb) | Atribut WritingMode: LrTb - Progresi inline dari kiri ke kanan; progresi blok dari atas ke bawah. Ini adalah mode penulisan khas untuk sistem penulisan Barat. |
| [WritingMode_RlTb](#WritingMode_RlTb) | Atribut WritingMode: RlTb - Progresi inline dari kanan ke kiri; progresi blok dari atas ke bawah. Ini adalah mode penulisan khas untuk sistem penulisan Arab dan Ibrani. |
| [WritingMode_TbRl](#WritingMode_TbRl) | Atribut WritingMode: TbRl - Progresi inline dari atas ke bawah; progresi blok dari kanan ke kiri. Ini adalah mode penulisan tipikal untuk sistem penulisan Cina dan Jepang. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [fromNameAttributeKey](#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | Mendapatkan nama atribut untuk kunci atribut. |
| [getAttributeKey](#getAttributeKey--) | Mendapatkan kunci atribut. |
| [getName](#getName--) | Mendapatkan nilai nama atribut. |
| [toString](#toString--) | Mengembalikan string yang mewakili objek saat ini. |

### BlockAlign_After {#BlockAlign_After}
```
public static final AttributeName BlockAlign_After
```

Attribute BlockAlign: After - Tepi setelah dari persegi alokasi anak terakhir selaras dengan tepi konten sel tabel.

### BlockAlign_Before {#BlockAlign_Before}
```
public static final AttributeName BlockAlign_Before
```

Attribute BlockAlign: Before - Tepi sebelum dari persegi alokasi anak pertama selaras dengan tepi konten sel tabel.

### BlockAlign_Justify {#BlockAlign_Justify}
```
public static final AttributeName BlockAlign_Justify
```

Attribute BlockAlign: Justify - Anak-anak selaras dengan kedua tepi sebelum dan setelah dari persegi konten sel tabel. Anak pertama harus ditempatkan seperti yang dijelaskan untuk Before dan anak terakhir seperti yang dijelaskan untuk After, dengan jarak yang sama antar anak. Jika hanya ada satu anak, ia harus selaras hanya dengan tepi sebelum, seperti pada Before.

### BlockAlign_Middle {#BlockAlign_Middle}
```
public static final AttributeName BlockAlign_Middle
```

Attribute BlockAlign: Middle- Anak-anak diposisikan di tengah sel tabel. Jarak antara tepi sebelum persegi alokasi anak pertama dan persegi konten sel tabel harus sama dengan jarak antara tepi setelah persegi alokasi anak terakhir dan persegi konten sel tabel.

### BorderStyle_Dashed {#BorderStyle_Dashed}
```
public static final AttributeName BorderStyle_Dashed
```

Attribute BorderStyle: Dashed - Garis batas adalah serangkaian segmen garis pendek.

### BorderStyle_Dotted {#BorderStyle_Dotted}
```
public static final AttributeName BorderStyle_Dotted
```

Attribute BorderStyle: Dotted - Garis batas adalah serangkaian titik.

### BorderStyle_Double {#BorderStyle_Double}
```
public static final AttributeName BorderStyle_Double
```

Attribute BorderStyle: Double - Garis batas terdiri dari dua garis padat. Jumlah kedua garis dan ruang di antara keduanya sama dengan nilai BorderThickness.

### BorderStyle_Groove {#BorderStyle_Groove}
```
public static final AttributeName BorderStyle_Groove
```

Attribute BorderStyle: Groove - Garis batas tampak seolah-olah dipahat ke dalam kanvas.

### BorderStyle_Hidden {#BorderStyle_Hidden}
```
public static final AttributeName BorderStyle_Hidden
```

Attribute BorderStyle: Hidden - Sama seperti None, kecuali dalam hal resolusi konflik batas untuk elemen tabel.

### BorderStyle_Inset {#BorderStyle_Inset}
```
public static final AttributeName BorderStyle_Inset
```

Attribute BorderStyle: Inset - Garis batas membuat seluruh kotak tampak seolah-olah tertanam dalam kanvas.

### BorderStyle_None {#BorderStyle_None}
```
public static final AttributeName BorderStyle_None
```

Attribute BorderStyle: None - Tidak ada batas. Memaksa nilai yang dihitung dari BorderThicknessto menjadi 0.

### BorderStyle_Outset {#BorderStyle_Outset}
```
public static final AttributeName BorderStyle_Outset
```

Attribute BorderStyle: Outset - Garis batas membuat seluruh kotak tampak seolah-olah keluar dari kanvas (berlawanan dengan Inset).

### BorderStyle_Ridge {#BorderStyle_Ridge}
```
public static final AttributeName BorderStyle_Ridge
```

Attribute BorderStyle: Ridge - Garis batas tampak seolah-olah keluar dari kanvas (berlawanan dengan Groove).

### BorderStyle_Solid {#BorderStyle_Solid}
```
public static final AttributeName BorderStyle_Solid
```

Attribute BorderStyle: Solid - Garis batas adalah satu segmen garis tunggal.

### Checked_neutral {#Checked_neutral}
```
public static final AttributeName Checked_neutral
```

Attribute checked: Neutral - Status tombol radio atau kotak centang.

### Checked_off {#Checked_off}
```
public static final AttributeName Checked_off
```

Atribut checked: Off - Status tombol radio atau bidang kotak centang.

### Checked_on {#Checked_on}
```
public static final AttributeName Checked_on
```

Atribut checked: On - Status tombol radio atau bidang kotak centang.

### GlyphOrientationVertical_Auto {#GlyphOrientationVertical_Auto}
```
public static final AttributeName GlyphOrientationVertical_Auto
```

Atribut GlyphOrientationVertical: Auto - Menentukan orientasi default untuk teks, tergantung apakah teks tersebut lebar penuh (sepanjang tingginya).

### Height_Auto {#Height_Auto}
```
public static final AttributeName Height_Auto
```

Atribut Height: Auto - Tinggi elemen akan ditentukan oleh tinggi intrinsik kontennya.

### InlineAlign_Center {#InlineAlign_Center}
```
public static final AttributeName InlineAlign_Center
```

Atribut InlineAlign: Center - Setiap anak dipusatkan di dalam sel tabel. Jarak antara tepi mulai persegi alokasi anak dan persegi konten sel tabel harus sama dengan jarak antara tepi akhir mereka.

### InlineAlign_End {#InlineAlign_End}
```
public static final AttributeName InlineAlign_End
```

Atribut InlineAlign: End - Tepi akhir persegi alokasi setiap anak diselaraskan dengan tepi persegi konten sel tabel.

### InlineAlign_Start {#InlineAlign_Start}
```
public static final AttributeName InlineAlign_Start
```

Atribut InlineAlign: Start - Tepi mulai persegi alokasi setiap anak diselaraskan dengan tepi persegi konten sel tabel.

### LineHeight_Auto {#LineHeight_Auto}
```
public static final AttributeName LineHeight_Auto
```

Atribut LineHeight: Auto - Penyesuaian nilai BaselineShift tidak akan dilakukan.

### LineHeight_Normal {#LineHeight_Normal}
```
public static final AttributeName LineHeight_Normal
```

Atribut LineHeight: Normal - Sesuaikan tinggi baris untuk menyertakan nilai nonnol yang ditentukan untuk BaselineShift.

### ListNumbering_Circle {#ListNumbering_Circle}
```
public static final AttributeName ListNumbering_Circle
```

Atribut ListNumbering: Circle - Bullet bulat terbuka.

### ListNumbering_Decimal {#ListNumbering_Decimal}
```
public static final AttributeName ListNumbering_Decimal
```

Atribut ListNumbering: Decimal - Numerik Arab desimal (1-9, 10-99, ...).

### ListNumbering_Disc {#ListNumbering_Disc}
```
public static final AttributeName ListNumbering_Disc
```

Atribut ListNumbering: Disc - Bullet bulat padat.

### ListNumbering_LowerAlpha {#ListNumbering_LowerAlpha}
```
public static final AttributeName ListNumbering_LowerAlpha
```

Atribut ListNumbering: LowerAlpha - Huruf kecil (a, b, c, ...).

### ListNumbering_LowerRoman {#ListNumbering_LowerRoman}
```
public static final AttributeName ListNumbering_LowerRoman
```

Atribut ListNumbering: LowerRoman - Numeral Romawi kecil (i, ii, iii, iv, ...).

### ListNumbering_None {#ListNumbering_None}
```
public static final AttributeName ListNumbering_None
```

Atribut ListNumbering: None - Tidak ada penomoran otomatis; elemen Lbl (jika ada) berisi teks arbitrer yang tidak tunduk pada skema penomoran apa pun.

### ListNumbering_Square {#ListNumbering_Square}
```
public static final AttributeName ListNumbering_Square
```

Atribut ListNumbering: Square - Bullet kotak padat.

### ListNumbering_UpperAlpha {#ListNumbering_UpperAlpha}
```
public static final AttributeName ListNumbering_UpperAlpha
```

Atribut ListNumbering: UpperAlpha - Huruf kapital (A, B, C, ...).

### ListNumbering_UpperRoman {#ListNumbering_UpperRoman}
```
public static final AttributeName ListNumbering_UpperRoman
```

Atribut ListNumbering: UpperRoman - Numeral Romawi kapital (I, II, III, IV, ...).

### Placement_Before {#Placement_Before}
```
public static final AttributeName Placement_Before
```

Atribut Placement: Before - Ditempatkan sehingga tepi sebelum persegi alokasi elemen bertepatan dengan tepi area referensi terdekat yang mengelilinginya.

### Placement_Block {#Placement_Block}
```
public static final AttributeName Placement_Block
```

Atribut Placement: Block - Ditumpuk dalam arah blok-progresi di dalam area referensi yang mengelilingi atau BLSE induk.

### Placement_End {#Placement_End}
```
public static final AttributeName Placement_End
```

Atribut Placement: End - Ditempatkan sehingga tepi akhir persegi alokasi elemen bertepatan dengan tepi area referensi terdekat yang mengelilinginya.

### Placement_Inline {#Placement_Inline}
```
public static final AttributeName Placement_Inline
```

Atribut Placement: Inline - Dipadatkan dalam arah inline-progresi di dalam BLSE yang mengelilingi.

### Placement_Start {#Placement_Start}
```
public static final AttributeName Placement_Start
```

Atribut Placement: Start - Ditempatkan sehingga tepi mulai persegi alokasi elemen bertepatan dengan tepi area referensi terdekat yang mengelilinginya.

### Role_cb {#Role_cb}
```
public static final AttributeName Role_cb
```

Atribut Role: cb - Kotak centang.

### Role_pb {#Role_pb}
```
public static final AttributeName Role_pb
```

Atribut Role: pb - Tombol tekan.

### Role_rb {#Role_rb}
```
public static final AttributeName Role_rb
```

Atribut Role: rb - Tombol radio.

### Role_tv {#Role_tv}
```
public static final AttributeName Role_tv
```

Atribut Role: tv - Bidang nilai-teks.

### RubyAlign_Center {#RubyAlign_Center}
```
public static final AttributeName RubyAlign_Center
```

Atribut RubyAlign: Center - Konten harus dipusatkan dalam arah inline-progression.

### RubyAlign_Distribute {#RubyAlign_Distribute}
```
public static final AttributeName RubyAlign_Distribute
```

Atribut RubyAlign: Distribute - Konten harus diperluas untuk mengisi lebar yang tersedia dalam arah inline-progression. Namun, spasi juga harus disisipkan pada tepi awal dan tepi akhir teks. Spasi harus didistribusikan menggunakan rasio 1:2:1 (awal:infix:akhir). Rasio akan diubah menjadi 0:1:1 jika ruby muncul di awal baris teks atau menjadi 1:1:0 jika ruby muncul di akhir baris teks.

### RubyAlign_End {#RubyAlign_End}
```
public static final AttributeName RubyAlign_End
```

Atribut RubyAlign: End - Konten harus disejajarkan pada tepi akhir dalam arah inline-progression.

### RubyAlign_Justify {#RubyAlign_Justify}
```
public static final AttributeName RubyAlign_Justify
```

Atribut RubyAlign: Justify - Konten harus diperluas untuk mengisi lebar yang tersedia dalam arah inline-progression.

### RubyAlign_Start {#RubyAlign_Start}
```
public static final AttributeName RubyAlign_Start
```

Atribut RubyAlign: Start - Konten harus disejajarkan pada tepi awal dalam arah inline-progression.

### RubyPosition_After {#RubyPosition_After}
```
public static final AttributeName RubyPosition_After
```

Atribut RubyPosition: After - Konten RT harus disejajarkan sepanjang tepi after elemen.

### RubyPosition_Before {#RubyPosition_Before}
```
public static final AttributeName RubyPosition_Before
```

Atribut RubyPosition: Before - Konten RT harus disejajarkan sepanjang tepi before elemen.

### RubyPosition_Inline {#RubyPosition_Inline}
```
public static final AttributeName RubyPosition_Inline
```

Atribut RubyPosition: Inline - Elemen RT dan RP terkait harus diformat sebagai komentar dalam tanda kurung, mengikuti elemen RB.

### RubyPosition_Warichu {#RubyPosition_Warichu}
```
public static final AttributeName RubyPosition_Warichu
```

Atribut RubyPosition: Warichu - Elemen RT dan RP terkait harus diformat sebagai warichu, mengikuti elemen RB.

### Scope_Both {#Scope_Both}
```
public static final AttributeName Scope_Both
```

Atribut Scope: Both.

### Scope_Column {#Scope_Column}
```
public static final AttributeName Scope_Column
```

Atribut Scope: Column.

### Scope_Row {#Scope_Row}
```
public static final AttributeName Scope_Row
```

Atribut Scope: Row.

### TextAlign_Center {#TextAlign_Center}
```
public static final AttributeName TextAlign_Center
```

Atribut TextAlign: Center - Dipusatkan antara tepi awal dan tepi akhir.

### TextAlign_End {#TextAlign_End}
```
public static final AttributeName TextAlign_End
```

Atribut TextAlign: End - Disejajarkan dengan tepi akhir.

### TextAlign_Justify {#TextAlign_Justify}
```
public static final AttributeName TextAlign_Justify
```

Atribut TextAlign: Justify - Disejajarkan dengan kedua tepi awal dan akhir, dengan spasi internal pada setiap baris diperluas, jika diperlukan, untuk mencapai penyelarasan tersebut. Baris terakhir (atau satu-satunya) harus disejajarkan hanya dengan tepi awal.

### TextAlign_Start {#TextAlign_Start}
```
public static final AttributeName TextAlign_Start
```

Atribut TextAlign: Start - Disejajarkan dengan tepi awal.

### TextDecorationType_LineThrough {#TextDecorationType_LineThrough}
```
public static final AttributeName TextDecorationType_LineThrough
```

Atribut TextDecorationType: LineThrough - Garis melalui tengah teks.

### TextDecorationType_None {#TextDecorationType_None}
```
public static final AttributeName TextDecorationType_None
```

Atribut TextDecorationType: None - Tidak ada dekorasi teks.

### TextDecorationType_Overline {#TextDecorationType_Overline}
```
public static final AttributeName TextDecorationType_Overline
```

Atribut TextDecorationType: Overline - Garis di atas teks.

### TextDecorationType_Underline {#TextDecorationType_Underline}
```
public static final AttributeName TextDecorationType_Underline
```

Atribut TextDecorationType: Underline - Garis di bawah teks.

### Width_Auto {#Width_Auto}
```
public static final AttributeName Width_Auto
```

Atribut Width: Auto - lebar elemen akan ditentukan oleh lebar intrinsik kontennya.

### WritingMode_LrTb {#WritingMode_LrTb}
```
public static final AttributeName WritingMode_LrTb
```

Atribut WritingMode: LrTb - Progresi inline dari kiri ke kanan; progresi blok dari atas ke bawah. Ini adalah mode penulisan khas untuk sistem penulisan Barat.

### WritingMode_RlTb {#WritingMode_RlTb}
```
public static final AttributeName WritingMode_RlTb
```

Atribut WritingMode: RlTb - Progresi inline dari kanan ke kiri; progresi blok dari atas ke bawah. Ini adalah mode penulisan khas untuk sistem penulisan Arab dan Ibrani.

### WritingMode_TbRl {#WritingMode_TbRl}
```
public static final AttributeName WritingMode_TbRl
```

Atribut WritingMode: TbRl - Progresi inline dari atas ke bawah; progresi blok dari kanan ke kiri. Ini adalah mode penulisan tipikal untuk sistem penulisan Cina dan Jepang.

### fromNameAttributeKey {#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
Mendapatkan nama atribut untuk kunci atribut.

### getAttributeKey {#getAttributeKey--}
```
public final AttributeKey getAttributeKey()
```

Mendapatkan kunci atribut.

**Returns:**
Instansi AttributeKey

### getName {#getName--}
```
public final String getName()
```

Mendapatkan nilai nama atribut.

**Returns:**
nilai String

### toString {#toString--}
```
public String toString()
```

Mengembalikan string yang mewakili objek saat ini.

**Returns:**
String yang mewakili objek saat ini.
