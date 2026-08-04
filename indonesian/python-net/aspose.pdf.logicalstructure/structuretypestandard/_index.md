---
title: "StructureTypeStandard"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili Tipe Struktur Standar."
type: docs
weight: 560
url: /id/python-net/aspose.pdf.logicalstructure/structuretypestandard/
---

## StructureTypeStandard class

Mewakili Tipe Struktur Standar.

Tipe StructureTypeStandard menampilkan anggota berikut:
## Properti
| Nama | Deskripsi |
| :- | :- |
| tag | Mendapatkan nama tag dari [StructureElement](/pdf/python-net/aspose.pdf.logicalstructure/structureelement/). |
| category | Mendapatkan kategori dari Standard Structure Type. |
| DOCUMENT | (Document) Dokumen lengkap. Ini adalah elemen akar dari setiap pohon struktur yang berisi beberapa bagian atau beberapa artikel. |
| PART | (Part) Pembagian skala besar dari sebuah dokumen. Jenis elemen ini cocok untuk mengelompokkan artikel atau bagian. |
| ART | (Article) Sebuah tubuh teks yang relatif mandiri yang membentuk satu narasi atau eksposisi. Artikel harus terpisah; yaitu, mereka tidak boleh berisi artikel lain sebagai elemen konstituen. |
| SECT | (Section) Sebuah wadah untuk mengelompokkan elemen konten yang terkait. |
| DIV | (Division) Sebuah elemen tingkat blok generik atau grup elemen. |
| BLOCK_QUOTE | (Block quotation) Sebuah bagian teks yang terdiri dari satu atau lebih paragraf yang dikaitkan dengan seseorang selain penulis teks di sekitarnya. |
| CAPTION | (Caption) Sebuah bagian teks singkat yang menggambarkan sebuah tabel atau gambar. |
| TOC | (Table of contents) Sebuah daftar yang terdiri dari entri item daftar isi (tipe struktur TOCI) dan/atau entri daftar isi bersarang lainnya (TOC). |
| TOCI | (Table of contents item) Sebuah anggota individual dari daftar isi. Anak dari entri ini dapat berupa salah satu tipe struktur berikut: |
| INDEX | (Index) Sebuah urutan entri yang berisi teks identifikasi disertai elemen referensi yang menunjukkan kemunculan teks yang ditentukan dalam badan utama dokumen. |
| NON_STRUCT | (Nonstructural element) Sebuah elemen pengelompokan yang tidak memiliki signifikansi struktural bawaan; elemen ini hanya berfungsi untuk tujuan pengelompokan. Tipe elemen ini berbeda dari sebuah division (tipe struktur Div) karena tidak akan diinterpretasikan atau diekspor ke format dokumen lain; namun, keturunannya akan diproses secara normal. |
| PRIVATE | (Private element) Sebuah elemen pengelompokan yang berisi konten pribadi milik aplikasi yang menghasilkan elemen tersebut. Signifikansi struktural dari tipe elemen ini tidak ditentukan dan harus ditetapkan sepenuhnya oleh penulis yang sesuai. Baik elemen Private maupun keturunannya tidak boleh diinterpretasikan atau diekspor ke format dokumen lain. |
| P | (Paragraph) Sebuah pembagian tingkat rendah dari teks. |
| H | (Heading) Sebuah label untuk subdivisi konten dokumen. Itu harus menjadi anak pertama dari divisi yang dipimpinnya. |
| H1 | Judul Tingkat 1, untuk digunakan oleh penulis yang mematuhi standar tetapi tidak dapat menumpuk bagian mereka secara hierarkis sehingga tidak dapat menentukan tingkat judul dari tingkat penumpukannya. |
| H2 | Judul Tingkat 2, untuk digunakan oleh penulis yang mematuhi standar tetapi tidak dapat menumpuk bagian mereka secara hierarkis sehingga tidak dapat menentukan tingkat judul dari tingkat penumpukannya. |
| H3 | Judul Tingkat 3, untuk digunakan oleh penulis yang mematuhi standar tetapi tidak dapat menumpuk bagian mereka secara hierarkis sehingga tidak dapat menentukan tingkat judul dari tingkat penumpukannya. |
| H4 | Judul Tingkat 4, untuk digunakan oleh penulis yang mematuhi standar tetapi tidak dapat menumpuk bagian mereka secara hierarkis sehingga tidak dapat menentukan tingkat judul dari tingkat penumpukannya. |
| H5 | Judul Tingkat 5, untuk digunakan oleh penulis yang mematuhi standar tetapi tidak dapat menumpuk bagian mereka secara hierarkis sehingga tidak dapat menentukan tingkat judul dari tingkat penumpukannya. |
| H6 | Judul Tingkat 6, untuk digunakan oleh penulis yang mematuhi standar tetapi tidak dapat menumpuk bagian mereka secara hierarkis sehingga tidak dapat menentukan tingkat judul dari tingkat penumpukannya. |
| L | (List) Sekuens item dengan makna dan pentingnya yang serupa. Anak langsungnya harus berupa caption opsional (tipe struktur Caption) diikuti oleh satu atau lebih item daftar (tipe struktur LI). |
| LI | (List item) Sebuah anggota individual dari sebuah daftar. Anak-anaknya dapat berupa satu atau lebih label, badan daftar, atau keduanya (tipe struktur Lbl atau LBody). |
| LBL | (Label) Sebuah nama atau nomor yang membedakan suatu item dari yang lain dalam daftar yang sama atau kelompok item serupa lainnya. |
| L_BODY | (List body) Konten deskriptif dari sebuah item daftar. Misalnya, dalam daftar kamus, ini berisi definisi istilah. Ia dapat berisi konten secara langsung atau memiliki BLSE lain, mungkin termasuk daftar bersarang, sebagai anak. |
| TABLE | (Table) Tata letak dua dimensi dari sel data persegi panjang, yang mungkin memiliki substruktur kompleks. Ia berisi satu atau lebih baris tabel (tipe struktur TR) sebagai anak; atau sebuah kepala tabel opsional (tipe struktur THead) diikuti oleh satu atau lebih elemen badan tabel (tipe struktur TBody) dan footer tabel opsional (tipe struktur TFoot). Selain itu, tabel dapat memiliki caption (tipe struktur Caption) sebagai anak pertama atau terakhir. |
| T_HEAD | (Table header row group; PDF 1.5) Sekelompok baris yang membentuk header sebuah tabel. Jika tabel terbagi menjadi beberapa halaman, baris-baris ini dapat digambar ulang di bagian atas setiap fragmen tabel (meskipun hanya ada satu elemen THead). |
| T_BODY | (Grup baris tubuh tabel; PDF 1.5) Sekelompok baris yang membentuk bagian utama tubuh sebuah tabel. Jika tabel terbagi menjadi beberapa halaman, area tubuh dapat terpecah pada batas baris. Sebuah tabel dapat memiliki beberapa elemen TBody untuk memungkinkan penggambaran batas atau latar belakang bagi sekumpulan baris. |
| T_FOOT | (Grup baris kaki tabel; PDF 1.5) Sekelompok baris yang membentuk kaki sebuah tabel. Jika tabel terbagi menjadi beberapa halaman, baris-baris ini dapat digambar ulang di bagian bawah setiap fragmen tabel (meskipun hanya ada satu elemen TFoot.) |
| TR | (Baris tabel) Sebuah baris judul atau data dalam sebuah tabel. Baris ini dapat berisi sel header tabel dan sel data tabel (tipe struktur TH dan TD). |
| TH | (Sel header tabel) Sel tabel yang berisi teks header yang menjelaskan satu atau lebih baris atau kolom tabel. |
| TD | (Sel data tabel) Sel tabel yang berisi data yang merupakan bagian dari konten tabel. |
| SPAN | (Span) Sebuah bagian teks inline umum yang tidak memiliki karakteristik khusus. Misalnya dapat digunakan untuk membatasi rentang teks dengan sekumpulan atribut gaya tertentu. |
| QUOTE | (Kutipan) Sebuah bagian teks inline yang dikaitkan dengan seseorang selain penulis teks di sekitarnya. |
| CATATAN | (Catatan) Sebuah item teks penjelas, seperti catatan kaki atau catatan akhir, yang dirujuk dari dalam isi dokumen. Item ini dapat memiliki label (tipe struktur Lbl) sebagai anak. Catatan dapat dimasukkan sebagai anak elemen struktur dalam teks isi yang merujuknya, atau dapat dimasukkan di tempat lain (misalnya dalam bagian catatan akhir) dan diakses melalui referensi (tipe struktur Reference). |
| REFERENCE | (Referensi) Sebuah kutipan ke konten di tempat lain dalam dokumen. |
| BIB_ENTRY | (Entri bibliografi) Sebuah referensi yang mengidentifikasi sumber eksternal dari konten yang dikutip. Entri ini dapat berisi label (tipe struktur Lbl) sebagai anak. |
| CODE | (Kode) Sebuah fragmen teks program komputer. |
| LINK | (Tautan) Sebuah asosiasi antara bagian konten ILSE dengan anotasi tautan yang bersesuaian atau beberapa anotasi tautan. Anak-anaknya harus berupa satu atau lebih item konten atau ILSE anak serta satu atau lebih referensi objek yang mengidentifikasi anotasi tautan yang terkait. |
| ANNOT | (Anotasi; PDF 1.5) Sebuah asosiasi antara bagian konten ILSE dengan anotasi PDF yang bersesuaian. Annot harus digunakan untuk semua anotasi PDF kecuali anotasi tautan dan anotasi widget. |
| RUBY | (Ruby; PDF 1.5) Sebuah catatan samping (anotasi) yang ditulis dengan ukuran teks lebih kecil dan ditempatkan bersebelahan dengan teks dasar yang dirujuknya. Elemen Ruby juga dapat berisi elemen RB, RT, dan RP. |
| RB | (Ruby base text) Teks berukuran penuh yang menjadi dasar anotasi ruby. RB dapat berisi teks, elemen inline lainnya, atau campuran keduanya. Mungkin memiliki atribut RubyAlignattribute. |
| RT | (Ruby annotation text) Teks berukuran lebih kecil yang harus ditempatkan berdekatan dengan teks dasar ruby. Itu dapat berisi teks, elemen inline lainnya, atau campuran keduanya. Mungkin memiliki atribut RubyAlign dan RubyPosition. |
| RP | (Ruby punctuation) Tanda baca yang mengelilingi teks anotasi ruby. Hanya digunakan ketika anotasi ruby tidak dapat diformat dengan benar dalam gaya ruby dan malah diformat sebagai komentar normal, atau ketika diformat sebagai warichu. Berisi teks (biasanya satu LEFT atau RIGHT PARENTHESIS atau karakter penutup serupa). |
| WARICHU | (Warichu; PDF 1.5) Sebuah komentar atau anotasi dengan ukuran teks lebih kecil dan diformat menjadi dua baris kecil dalam tinggi baris teks yang memuatnya serta ditempatkan setelah (inline) teks dasar yang menjadi referensinya. Elemen Warichu juga dapat berisi elemen WT dan WP. |
| WT | (Warichu text) Teks berukuran lebih kecil dari komentar warichu yang diformat menjadi dua baris dan ditempatkan di antara elemen WP yang mengelilinginya. |
| WP | (Warichu punctuation) Tanda baca yang mengelilingi teks WT. Berisi teks (biasanya satu LEFT atau RIGHT PARENTHESIS atau karakter penutup serupa). Menurut JIS X 4051-1995, tanda kurung yang mengelilingi warichu dapat diubah menjadi SPACE (sekitar 1/4 EM dalam lebar) sesuai kebijakan formatter. |
| FIGURE | (Figure) Sebuah item konten grafis. Penempatannya dapat ditentukan dengan atribut layout Placement. |
| FORMULA | (Formula) Sebuah rumus matematika. |
| FORM | (Form) Sebuah anotasi widget yang mewakili bidang formulir interaktif. |

### Lihat Juga

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

