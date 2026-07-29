---
title: "StructureTypeStandard"
linktitle: "StructureTypeStandard"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili Tipe Struktur Standar."
type: docs
weight: 130
url: /id/java/com.aspose.pdf.tagged.logicalstructure/structuretypestandard/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard

```
public final class StructureTypeStandard extends Object
```

Mewakili Tipe Struktur Standar.

## Fields

| Field | Deskripsi |
| --- | --- |
| [Annot](#Annot) | (Annotation; PDF 1.5) Sebuah asosiasi antara sebagian konten ILSE dengan anotasi PDF yang bersesuaian. Annot harus digunakan untuk semua anotasi PDF kecuali anotasi tautan dan anotasi widget. |
| [Art](#Art) | (Artikel) Sebuah badan teks yang relatif mandiri yang membentuk satu narasi atau eksposisi. Artikel harus terpisah; yaitu, mereka tidak boleh berisi artikel lain sebagai elemen konstituen. |
| [BibEntry](#BibEntry) | (Entri Bibliografi) Sebuah referensi yang mengidentifikasi sumber eksternal dari konten yang dikutip. Ini dapat berisi label (tipe struktur Lbl) sebagai anak. Meskipun sebuah entri bibliografi kemungkinan mencakup bagian-bagian komponen yang mengidentifikasi penulis, karya, penerbit, dan sebagainya dari konten yang dikutip, tidak ada tipe struktur standar yang didefinisikan pada tingkat detail ini. |
| [BlockQuote](#BlockQuote) | (Kutipan blok) Sebuah bagian teks yang terdiri dari satu atau lebih paragraf yang dikaitkan kepada seseorang selain penulis teks di sekitarnya. |
| [Caption](#Caption) | (Keterangan) Sebuah bagian teks singkat yang menjelaskan sebuah tabel atau gambar. |
| [Code](#Code) | (Kode) Sebuah fragmen teks program komputer. |
| [Div](#Div) | (Divisi) Sebuah elemen tingkat blok generik atau kelompok elemen. |
| [Document](#Document) | (Dokumen) Sebuah dokumen lengkap. Ini adalah elemen akar dari setiap pohon struktur yang berisi beberapa bagian atau beberapa artikel. |
| [Figure](#Figure) | (Gambar) Sebuah item konten grafis. Penempatannya dapat ditentukan dengan atribut tata letak Placement. |
| [Form](#Form) | (Form) Sebuah anotasi widget yang mewakili bidang formulir interaktif. |
| [Formula](#Formula) | (Formula) Sebuah rumus matematika. Tipe struktur ini berguna hanya untuk mengidentifikasi seluruh elemen konten sebagai rumus. Tidak ada tipe struktur standar yang didefinisikan untuk mengidentifikasi komponen individual di dalam rumus. Dari sudut pandang pemformatan, rumus harus diperlakukan serupa dengan gambar (tipe struktur Figure). |
| [H](#H) | (Heading) Sebuah label untuk subdivisi konten dokumen. Itu harus menjadi anak pertama dari divisi yang dipimpinnya. |
| [H1](#H1) | Level 1 Heading, untuk digunakan oleh penulis yang mematuhi standar namun tidak dapat menumpuk secara hierarkis bagian mereka sehingga tidak dapat menentukan level heading dari tingkat penumpukannya. |
| [H2](#H2) | Level 2 Heading, untuk digunakan oleh penulis yang mematuhi standar namun tidak dapat menumpuk secara hierarkis bagian mereka sehingga tidak dapat menentukan level heading dari tingkat penumpukannya. |
| [H3](#H3) | Level 3 Heading, untuk digunakan oleh penulis yang mematuhi standar namun tidak dapat menumpuk secara hierarkis bagian mereka sehingga tidak dapat menentukan level heading dari tingkat penumpukannya. |
| [H4](#H4) | Level 4 Heading, untuk digunakan oleh penulis yang mematuhi standar namun tidak dapat menumpuk secara hierarkis bagian mereka sehingga tidak dapat menentukan level heading dari tingkat penumpukannya. |
| [H5](#H5) | Level 5 Heading, untuk digunakan oleh penulis yang mematuhi standar namun tidak dapat menumpuk secara hierarkis bagian mereka sehingga tidak dapat menentukan level heading dari tingkat penumpukannya. |
| [H6](#H6) | Heading Tingkat 6, untuk digunakan dalam penulis yang mematuhi standar yang tidak dapat menumpuk bagian mereka secara hierarkis sehingga tidak dapat menentukan tingkat heading dari tingkat penumpukannya. |
| [Index](#Index) | (Indeks) Sekumpulan entri yang berisi teks identifikasi disertai elemen referensi yang menunjukkan kemunculan teks yang ditentukan dalam badan utama dokumen. |
| [L](#L) | (Daftar) Sekumpulan item dengan makna dan pentingitas yang sama. Anak langsungnya harus berupa caption opsional (tipe struktur Caption) diikuti oleh satu atau lebih item daftar (tipe struktur LI). |
| [Lbl](#Lbl) | (Label) Nama atau nomor yang membedakan suatu item dari yang lain dalam daftar yang sama atau grup item serupa lainnya. |
| [LBody](#LBody) | (Badan daftar) Konten deskriptif dari sebuah item daftar. Misalnya dalam daftar kamus, berisi definisi istilah. Konten dapat langsung berisi atau memiliki BLSE lain, mungkin termasuk daftar bersarang, sebagai anak. |
| [LI](#LI) | (Item daftar) Anggota individual dari sebuah daftar. Anak‑anaknya dapat berupa satu atau lebih label, badan daftar, atau keduanya (tipe struktur Lbl atau LBody). |
| [Link](#Link) | (Tautan) Asosiasi antara bagian konten ILSE dengan anotasi tautan yang bersesuaian atau anotasi‑anotasi. Anak‑anaknya harus berupa satu atau lebih item konten atau ILSE anak serta satu atau lebih referensi objek yang mengidentifikasi anotasi tautan yang terkait. |
| [NonStruct](#NonStruct) | (Elemen nonstruktural) Elemen pengelompokan yang tidak memiliki signifikansi struktural bawaan; hanya berfungsi untuk tujuan pengelompokan. Tipe elemen ini berbeda dari divisi (tipe struktur Div) karena tidak akan diinterpretasikan atau diekspor ke format dokumen lain; namun, turunannya akan diproses secara normal. |
| [Note](#Note) | (Catatan) Item teks penjelas, seperti catatan kaki atau catatan akhir, yang dirujuk dari dalam badan dokumen. Bisa memiliki label (tipe struktur Lbl) sebagai anak. Catatan dapat dimasukkan sebagai anak elemen struktur dalam teks badan yang merujuknya, atau dapat dimasukkan di tempat lain (misalnya dalam bagian catatan akhir) dan diakses melalui referensi (tipe struktur Reference). Tagged PDF tidak menentukan penempatan catatan kaki dalam urutan konten halaman. Mereka dapat berada secara inline atau di akhir halaman, sesuai kebijakan penulis yang mematuhi standar. |
| [P](#P) | (Paragraf) Pembagian teks tingkat rendah. |
| [Part](#Part) | (Bagian) Pembagian skala besar dari sebuah dokumen. Tipe elemen ini cocok untuk mengelompokkan artikel atau bagian. |
| [Private](#Private) | (Elemen pribadi) Elemen pengelompokan yang berisi konten pribadi milik aplikasi yang menghasilkan. Signifikansi struktural tipe elemen ini tidak ditentukan dan sepenuhnya ditentukan oleh penulis yang mematuhi standar. Baik elemen Pribadi maupun turunannya tidak akan diinterpretasikan atau diekspor ke format dokumen lain. |
| [Quote](#Quote) | (Kutipan) Bagian teks inline yang dikaitkan kepada orang selain penulis teks di sekitarnya. Teks yang dikutip harus berada inline dalam satu paragraf tunggal. Ini berbeda dari elemen blok BlockQuote, yang terdiri dari satu atau lebih paragraf lengkap (atau elemen lain yang disajikan seolah‑seperti paragraf lengkap). |
| [RB](#RB) | (Teks dasar Ruby) Teks berukuran penuh yang menjadi dasar anotasi ruby. RB dapat berisi teks, elemen inline lain, atau campuran keduanya. Bisa memiliki atribut RubyAlign. |
| [Reference](#Reference) | (Referensi) Kutipan ke konten di tempat lain dalam dokumen. |
| [RP](#RP) | (Tanda baca Ruby) Tanda baca yang mengelilingi teks anotasi ruby. Hanya digunakan ketika anotasi ruby tidak dapat diformat dengan gaya ruby dan malah diformat sebagai komentar normal, atau ketika diformat sebagai warichu. Berisi teks (biasanya satu TANDA KURUNG KIRI atau KANAN atau karakter penutup serupa). |
| [RT](#RT) | (Teks anotasi Ruby) Teks berukuran lebih kecil yang harus ditempatkan berdekatan dengan teks dasar ruby. Bisa berisi teks, elemen inline lain, atau campuran keduanya. Bisa memiliki atribut RubyAlign dan RubyPosition. |
| [Ruby](#Ruby) | (Ruby; PDF 1.5) Catatan samping (anotasi) yang ditulis dengan ukuran teks lebih kecil dan ditempatkan berdekatan dengan teks dasar yang menjadi referensinya. Sebuah elemen Ruby juga dapat berisi elemen RB, RT, dan RP. (Ruby) Pembungkus di sekitar seluruh rangkaian ruby. Harus berisi satu elemen RB diikuti oleh elemen RT atau grup tiga elemen yang terdiri dari RP, RT, dan RP. Elemen Ruby dan elemen kontennya tidak boleh terputus melintasi beberapa baris. |
| [Sect](#Sect) | (Section) Sebuah wadah untuk mengelompokkan elemen konten yang terkait. |
| [Span](#Span) | (Span) Sebuah bagian teks inline generik yang tidak memiliki karakteristik khusus. Itu dapat digunakan, misalnya, untuk membatasi rentang teks dengan sekumpulan atribut gaya tertentu. |
| [Table](#Table) | (Table) Tata letak dua dimensi dari sel data berbentuk persegi panjang, yang mungkin memiliki substruktur yang kompleks. Ia berisi satu atau lebih baris tabel (tipe struktur TR) sebagai anak; atau kepala tabel opsional (tipe struktur THead) diikuti oleh satu atau lebih elemen tubuh tabel (tipe struktur TBody) dan kaki tabel opsional (tipe struktur TFoot). Selain itu, sebuah tabel dapat memiliki caption (tipe struktur Caption) sebagai anak pertama atau terakhirnya. |
| [TBody](#TBody) | (Table body row group; PDF 1.5) Sekelompok baris yang membentuk bagian utama tubuh sebuah tabel. Jika tabel terpisah ke beberapa halaman, area tubuh dapat dipisahkan pada batas baris. Sebuah tabel dapat memiliki beberapa elemen TBody untuk memungkinkan penggambaran batas atau latar belakang bagi sekumpulan baris. |
| [TD](#TD) | (Table data cell) Sebuah sel tabel yang berisi data yang merupakan bagian dari konten tabel. |
| [TFoot](#TFoot) | (Table footer row group; PDF 1.5) Sekelompok baris yang membentuk kaki tabel. Jika tabel terpisah ke beberapa halaman, baris-baris ini dapat digambar ulang di bagian bawah setiap fragmen tabel (meskipun hanya ada satu elemen TFoot.) |
| [TH](#TH) | (Table header cell) Sebuah sel tabel yang berisi teks header yang menjelaskan satu atau lebih baris atau kolom tabel. |
| [THead](#THead) | (Table header row group; PDF 1.5) Sekelompok baris yang membentuk header sebuah tabel. Jika tabel terpisah ke beberapa halaman, baris-baris ini dapat digambar ulang di bagian atas setiap fragmen tabel (meskipun hanya ada satu elemen THead). |
| [TOC](#TOC) | (Table of contents) Sebuah daftar yang terdiri dari entri item daftar isi (tipe struktur TOCI) dan/atau entri daftar isi bersarang lainnya (TOC). Entri TOC yang hanya mencakup entri TOCI mewakili hierarki datar. Entri TOC yang mencakup entri TOC bersarang lainnya (dan mungkin entri TOCI) mewakili hierarki yang lebih kompleks. Idealnya, hierarki entri TOC tingkat atas mencerminkan struktur tubuh utama dokumen. |
| [TOCI](#TOCI) | (Table of contents item) Sebuah anggota individu dari daftar isi. Anak-anak entri ini dapat berupa salah satu tipe struktur berikut: Lbl - Sebuah label Reference - Sebuah referensi ke judul dan nomor halaman NonStruct - Elemen non-struktur untuk membungkus artefak pemimpin P - Teks deskriptif TOC - Elemen daftar isi untuk tabel isi hierarkis, seperti yang dijelaskan untuk entri TOC |
| [TR](#TR) | (Table row) Sebuah baris judul atau data dalam sebuah tabel. Ia dapat berisi sel header tabel dan sel data tabel (tipe struktur TH dan TD). |
| [Warichu](#Warichu) | (Warichu; PDF 1.5) Sebuah komentar atau anotasi dengan ukuran teks lebih kecil dan diformat menjadi dua baris kecil dalam tinggi baris teks yang memuatnya serta ditempatkan setelah (inline) teks dasar yang menjadi referensinya. Sebuah elemen Warichu juga dapat berisi elemen WT dan WP. (Warichu) Pembungkus di sekitar seluruh rangkaian warichu. Ia dapat berisi grup tiga elemen yang terdiri dari WP, WT, dan WP. Elemen Warichu (dan elemen kontennya) dapat melilit melintasi beberapa baris, sesuai aturan pemutusan warichu yang dijelaskan dalam Standar Industri Jepang (JIS) X 4051-1995. |
| [WP](#WP) | (Warichu punctuation) Tanda baca yang mengelilingi teks WT. Ia berisi teks (biasanya satu TANDA KURUNG KIRI atau KANAN atau karakter kurung serupa). Menurut JIS X 4051-1995, tanda kurung yang mengelilingi warichu dapat diubah menjadi SPASI (secara nominal 1/4 EM dalam lebar) atas kebijakan formatir. |
| [WT](#WT) | (Warichu text) Teks berukuran lebih kecil dari komentar warichu yang diformat menjadi dua baris dan ditempatkan di antara elemen WP di sekitarnya. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [canBeAppended](#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-) |  |
| [createElement](#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
| [getCategory](#getCategory--) | Mendapatkan kategori dari Standard Structure Type. |
| [getTag](#getTag--) | Mendapatkan nama tag dari {@code StructureElement}. |
| [to_StructureTypeStandard](#to_StructureTypeStandard-java.lang.String-) | Melakukan konversi eksplisit dari {@link String} ke {@link StructureTypeStandard}. |
| [toString](#toString--) | Mengembalikan string yang mewakili objek saat ini. |

### Annot {#Annot}
```
public static final StructureTypeStandard Annot
```

(Annotation; PDF 1.5) Sebuah asosiasi antara sebagian konten ILSE dengan anotasi PDF yang bersesuaian. Annot harus digunakan untuk semua anotasi PDF kecuali anotasi tautan dan anotasi widget.

### Art {#Art}
```
public static final StructureTypeStandard Art
```

(Artikel) Sebuah badan teks yang relatif mandiri yang membentuk satu narasi atau eksposisi. Artikel harus terpisah; yaitu, mereka tidak boleh berisi artikel lain sebagai elemen konstituen.

### BibEntry {#BibEntry}
```
public static final StructureTypeStandard BibEntry
```

(Entri Bibliografi) Sebuah referensi yang mengidentifikasi sumber eksternal dari konten yang dikutip. Ini dapat berisi label (tipe struktur Lbl) sebagai anak. Meskipun sebuah entri bibliografi kemungkinan mencakup bagian-bagian komponen yang mengidentifikasi penulis, karya, penerbit, dan sebagainya dari konten yang dikutip, tidak ada tipe struktur standar yang didefinisikan pada tingkat detail ini.

### BlockQuote {#BlockQuote}
```
public static final StructureTypeStandard BlockQuote
```

(Kutipan blok) Sebuah bagian teks yang terdiri dari satu atau lebih paragraf yang dikaitkan kepada seseorang selain penulis teks di sekitarnya.

### Caption {#Caption}
```
public static final StructureTypeStandard Caption
```

(Keterangan) Sebuah bagian teks singkat yang menjelaskan sebuah tabel atau gambar.

### Code {#Code}
```
public static final StructureTypeStandard Code
```

(Kode) Sebuah fragmen teks program komputer.

### Div {#Div}
```
public static final StructureTypeStandard Div
```

(Divisi) Sebuah elemen tingkat blok generik atau kelompok elemen.

### Document {#Document}
```
public static final StructureTypeStandard Document
```

(Dokumen) Sebuah dokumen lengkap. Ini adalah elemen akar dari setiap pohon struktur yang berisi beberapa bagian atau beberapa artikel.

### Figure {#Figure}
```
public static final StructureTypeStandard Figure
```

(Gambar) Sebuah item konten grafis. Penempatannya dapat ditentukan dengan atribut tata letak Placement.

### Form {#Form}
```
public static final StructureTypeStandard Form
```

(Form) Sebuah anotasi widget yang mewakili bidang formulir interaktif.

### Formula {#Formula}
```
public static final StructureTypeStandard Formula
```

(Formula) Sebuah rumus matematika. Tipe struktur ini berguna hanya untuk mengidentifikasi seluruh elemen konten sebagai rumus. Tidak ada tipe struktur standar yang didefinisikan untuk mengidentifikasi komponen individual di dalam rumus. Dari sudut pandang pemformatan, rumus harus diperlakukan serupa dengan gambar (tipe struktur Figure).

### H {#H}
```
public static final StructureTypeStandard H
```

(Heading) Sebuah label untuk subdivisi konten dokumen. Itu harus menjadi anak pertama dari divisi yang dipimpinnya.

### H1 {#H1}
```
public static final StructureTypeStandard H1
```

Level 1 Heading, untuk digunakan oleh penulis yang mematuhi standar namun tidak dapat menumpuk secara hierarkis bagian mereka sehingga tidak dapat menentukan level heading dari tingkat penumpukannya.

### H2 {#H2}
```
public static final StructureTypeStandard H2
```

Level 2 Heading, untuk digunakan oleh penulis yang mematuhi standar namun tidak dapat menumpuk secara hierarkis bagian mereka sehingga tidak dapat menentukan level heading dari tingkat penumpukannya.

### H3 {#H3}
```
public static final StructureTypeStandard H3
```

Level 3 Heading, untuk digunakan oleh penulis yang mematuhi standar namun tidak dapat menumpuk secara hierarkis bagian mereka sehingga tidak dapat menentukan level heading dari tingkat penumpukannya.

### H4 {#H4}
```
public static final StructureTypeStandard H4
```

Level 4 Heading, untuk digunakan oleh penulis yang mematuhi standar namun tidak dapat menumpuk secara hierarkis bagian mereka sehingga tidak dapat menentukan level heading dari tingkat penumpukannya.

### H5 {#H5}
```
public static final StructureTypeStandard H5
```

Level 5 Heading, untuk digunakan oleh penulis yang mematuhi standar namun tidak dapat menumpuk secara hierarkis bagian mereka sehingga tidak dapat menentukan level heading dari tingkat penumpukannya.

### H6 {#H6}
```
public static final StructureTypeStandard H6
```

Heading Tingkat 6, untuk digunakan dalam penulis yang mematuhi standar yang tidak dapat menumpuk bagian mereka secara hierarkis sehingga tidak dapat menentukan tingkat heading dari tingkat penumpukannya.

### Index {#Index}
```
public static final StructureTypeStandard Index
```

(Indeks) Sekumpulan entri yang berisi teks identifikasi disertai elemen referensi yang menunjukkan kemunculan teks yang ditentukan dalam badan utama dokumen.

### L {#L}
```
public static final StructureTypeStandard L
```

(Daftar) Sekumpulan item dengan makna dan pentingitas yang sama. Anak langsungnya harus berupa caption opsional (tipe struktur Caption) diikuti oleh satu atau lebih item daftar (tipe struktur LI).

### Lbl {#Lbl}
```
public static final StructureTypeStandard Lbl
```

(Label) Nama atau nomor yang membedakan suatu item dari yang lain dalam daftar yang sama atau grup item serupa lainnya.

### LBody {#LBody}
```
public static final StructureTypeStandard LBody
```

(Badan daftar) Konten deskriptif dari sebuah item daftar. Misalnya dalam daftar kamus, berisi definisi istilah. Konten dapat langsung berisi atau memiliki BLSE lain, mungkin termasuk daftar bersarang, sebagai anak.

### LI {#LI}
```
public static final StructureTypeStandard LI
```

(Item daftar) Anggota individual dari sebuah daftar. Anak‑anaknya dapat berupa satu atau lebih label, badan daftar, atau keduanya (tipe struktur Lbl atau LBody).

### Link {#Link}
```
public static final StructureTypeStandard Link
```

(Tautan) Asosiasi antara bagian konten ILSE dengan anotasi tautan yang bersesuaian atau anotasi‑anotasi. Anak‑anaknya harus berupa satu atau lebih item konten atau ILSE anak serta satu atau lebih referensi objek yang mengidentifikasi anotasi tautan yang terkait.

### NonStruct {#NonStruct}
```
public static final StructureTypeStandard NonStruct
```

(Elemen nonstruktural) Elemen pengelompokan yang tidak memiliki signifikansi struktural bawaan; hanya berfungsi untuk tujuan pengelompokan. Tipe elemen ini berbeda dari divisi (tipe struktur Div) karena tidak akan diinterpretasikan atau diekspor ke format dokumen lain; namun, turunannya akan diproses secara normal.

### Note {#Note}
```
public static final StructureTypeStandard Note
```

(Catatan) Item teks penjelas, seperti catatan kaki atau catatan akhir, yang dirujuk dari dalam badan dokumen. Bisa memiliki label (tipe struktur Lbl) sebagai anak. Catatan dapat dimasukkan sebagai anak elemen struktur dalam teks badan yang merujuknya, atau dapat dimasukkan di tempat lain (misalnya dalam bagian catatan akhir) dan diakses melalui referensi (tipe struktur Reference). Tagged PDF tidak menentukan penempatan catatan kaki dalam urutan konten halaman. Mereka dapat berada secara inline atau di akhir halaman, sesuai kebijakan penulis yang mematuhi standar.

### P {#P}
```
public static final StructureTypeStandard P
```

(Paragraf) Pembagian teks tingkat rendah.

### Part {#Part}
```
public static final StructureTypeStandard Part
```

(Bagian) Pembagian skala besar dari sebuah dokumen. Tipe elemen ini cocok untuk mengelompokkan artikel atau bagian.

### Private {#Private}
```
public static final StructureTypeStandard Private
```

(Elemen pribadi) Elemen pengelompokan yang berisi konten pribadi milik aplikasi yang menghasilkan. Signifikansi struktural tipe elemen ini tidak ditentukan dan sepenuhnya ditentukan oleh penulis yang mematuhi standar. Baik elemen Pribadi maupun turunannya tidak akan diinterpretasikan atau diekspor ke format dokumen lain.

### Quote {#Quote}
```
public static final StructureTypeStandard Quote
```

(Kutipan) Bagian teks inline yang dikaitkan kepada orang selain penulis teks di sekitarnya. Teks yang dikutip harus berada inline dalam satu paragraf tunggal. Ini berbeda dari elemen blok BlockQuote, yang terdiri dari satu atau lebih paragraf lengkap (atau elemen lain yang disajikan seolah‑seperti paragraf lengkap).

### RB {#RB}
```
public static final StructureTypeStandard RB
```

(Teks dasar Ruby) Teks berukuran penuh yang menjadi dasar anotasi ruby. RB dapat berisi teks, elemen inline lain, atau campuran keduanya. Bisa memiliki atribut RubyAlign.

### Reference {#Reference}
```
public static final StructureTypeStandard Reference
```

(Referensi) Kutipan ke konten di tempat lain dalam dokumen.

### RP {#RP}
```
public static final StructureTypeStandard RP
```

(Tanda baca Ruby) Tanda baca yang mengelilingi teks anotasi ruby. Hanya digunakan ketika anotasi ruby tidak dapat diformat dengan gaya ruby dan malah diformat sebagai komentar normal, atau ketika diformat sebagai warichu. Berisi teks (biasanya satu TANDA KURUNG KIRI atau KANAN atau karakter penutup serupa).

### RT {#RT}
```
public static final StructureTypeStandard RT
```

(Teks anotasi Ruby) Teks berukuran lebih kecil yang harus ditempatkan berdekatan dengan teks dasar ruby. Bisa berisi teks, elemen inline lain, atau campuran keduanya. Bisa memiliki atribut RubyAlign dan RubyPosition.

### Ruby {#Ruby}
```
public static final StructureTypeStandard Ruby
```

(Ruby; PDF 1.5) Catatan samping (anotasi) yang ditulis dengan ukuran teks lebih kecil dan ditempatkan berdekatan dengan teks dasar yang menjadi referensinya. Sebuah elemen Ruby juga dapat berisi elemen RB, RT, dan RP. (Ruby) Pembungkus di sekitar seluruh rangkaian ruby. Harus berisi satu elemen RB diikuti oleh elemen RT atau grup tiga elemen yang terdiri dari RP, RT, dan RP. Elemen Ruby dan elemen kontennya tidak boleh terputus melintasi beberapa baris.

### Sect {#Sect}
```
public static final StructureTypeStandard Sect
```

(Section) Sebuah wadah untuk mengelompokkan elemen konten yang terkait.

### Span {#Span}
```
public static final StructureTypeStandard Span
```

(Span) Sebuah bagian teks inline generik yang tidak memiliki karakteristik khusus. Itu dapat digunakan, misalnya, untuk membatasi rentang teks dengan sekumpulan atribut gaya tertentu.

### Table {#Table}
```
public static final StructureTypeStandard Table
```

(Table) Tata letak dua dimensi dari sel data berbentuk persegi panjang, yang mungkin memiliki substruktur yang kompleks. Ia berisi satu atau lebih baris tabel (tipe struktur TR) sebagai anak; atau kepala tabel opsional (tipe struktur THead) diikuti oleh satu atau lebih elemen tubuh tabel (tipe struktur TBody) dan kaki tabel opsional (tipe struktur TFoot). Selain itu, sebuah tabel dapat memiliki caption (tipe struktur Caption) sebagai anak pertama atau terakhirnya.

### TBody {#TBody}
```
public static final StructureTypeStandard TBody
```

(Table body row group; PDF 1.5) Sekelompok baris yang membentuk bagian utama tubuh sebuah tabel. Jika tabel terpisah ke beberapa halaman, area tubuh dapat dipisahkan pada batas baris. Sebuah tabel dapat memiliki beberapa elemen TBody untuk memungkinkan penggambaran batas atau latar belakang bagi sekumpulan baris.

### TD {#TD}
```
public static final StructureTypeStandard TD
```

(Table data cell) Sebuah sel tabel yang berisi data yang merupakan bagian dari konten tabel.

### TFoot {#TFoot}
```
public static final StructureTypeStandard TFoot
```

(Table footer row group; PDF 1.5) Sekelompok baris yang membentuk kaki tabel. Jika tabel terpisah ke beberapa halaman, baris-baris ini dapat digambar ulang di bagian bawah setiap fragmen tabel (meskipun hanya ada satu elemen TFoot.)

### TH {#TH}
```
public static final StructureTypeStandard TH
```

(Table header cell) Sebuah sel tabel yang berisi teks header yang menjelaskan satu atau lebih baris atau kolom tabel.

### THead {#THead}
```
public static final StructureTypeStandard THead
```

(Table header row group; PDF 1.5) Sekelompok baris yang membentuk header sebuah tabel. Jika tabel terpisah ke beberapa halaman, baris-baris ini dapat digambar ulang di bagian atas setiap fragmen tabel (meskipun hanya ada satu elemen THead).

### TOC {#TOC}
```
public static final StructureTypeStandard TOC
```

(Table of contents) Sebuah daftar yang terdiri dari entri item daftar isi (tipe struktur TOCI) dan/atau entri daftar isi bersarang lainnya (TOC). Entri TOC yang hanya mencakup entri TOCI mewakili hierarki datar. Entri TOC yang mencakup entri TOC bersarang lainnya (dan mungkin entri TOCI) mewakili hierarki yang lebih kompleks. Idealnya, hierarki entri TOC tingkat atas mencerminkan struktur tubuh utama dokumen.

### TOCI {#TOCI}
```
public static final StructureTypeStandard TOCI
```

(Table of contents item) Sebuah anggota individu dari daftar isi. Anak-anak entri ini dapat berupa salah satu tipe struktur berikut: Lbl - Sebuah label Reference - Sebuah referensi ke judul dan nomor halaman NonStruct - Elemen non-struktur untuk membungkus artefak pemimpin P - Teks deskriptif TOC - Elemen daftar isi untuk tabel isi hierarkis, seperti yang dijelaskan untuk entri TOC

### TR {#TR}
```
public static final StructureTypeStandard TR
```

(Table row) Sebuah baris judul atau data dalam sebuah tabel. Ia dapat berisi sel header tabel dan sel data tabel (tipe struktur TH dan TD).

### Warichu {#Warichu}
```
public static final StructureTypeStandard Warichu
```

(Warichu; PDF 1.5) Sebuah komentar atau anotasi dengan ukuran teks lebih kecil dan diformat menjadi dua baris kecil dalam tinggi baris teks yang memuatnya serta ditempatkan setelah (inline) teks dasar yang menjadi referensinya. Sebuah elemen Warichu juga dapat berisi elemen WT dan WP. (Warichu) Pembungkus di sekitar seluruh rangkaian warichu. Ia dapat berisi grup tiga elemen yang terdiri dari WP, WT, dan WP. Elemen Warichu (dan elemen kontennya) dapat melilit melintasi beberapa baris, sesuai aturan pemutusan warichu yang dijelaskan dalam Standar Industri Jepang (JIS) X 4051-1995.

### WP {#WP}
```
public static final StructureTypeStandard WP
```

(Warichu punctuation) Tanda baca yang mengelilingi teks WT. Ia berisi teks (biasanya satu TANDA KURUNG KIRI atau KANAN atau karakter kurung serupa). Menurut JIS X 4051-1995, tanda kurung yang mengelilingi warichu dapat diubah menjadi SPASI (secara nominal 1/4 EM dalam lebar) atas kebijakan formatir.

### WT {#WT}
```
public static final StructureTypeStandard WT
```

(Warichu text) Teks berukuran lebih kecil dari komentar warichu yang diformat menjadi dua baris dan ditempatkan di antara elemen WP di sekitarnya.

### canBeAppended {#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-}


### createElement {#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### getCategory {#getCategory--}
```
public final StructureTypeCategory getCategory()
```

Mendapatkan kategori dari Standard Structure Type.

**Returns:**
Nilai: Kategori dari Standard Structure Type.

### getTag {#getTag--}
```
public final String getTag()
```

Mendapatkan nama tag dari {@code StructureElement}.

**Returns:**
Nama tag dari {@code StructureElement}.

### to_StructureTypeStandard {#to_StructureTypeStandard-java.lang.String-}
Melakukan konversi eksplisit dari {@link String} ke {@link StructureTypeStandard}.

### toString {#toString--}
```
public String toString()
```

Mengembalikan string yang mewakili objek saat ini.

**Returns:**
String yang mewakili objek saat ini.
