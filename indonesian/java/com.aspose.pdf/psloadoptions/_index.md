---
title: "PsLoadOptions"
linktitle: "PsLoadOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili opsi untuk memuat/mengimpor file .mht ke dalam dokumen pdf."
type: docs
weight: 4060
url: /id/java/com.aspose.pdf/psloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PsLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PsLoadOptions

```
public final class PsLoadOptions extends LoadOptions
```

Mewakili opsi untuk memuat/mengimpor file .mht ke dalam dokumen pdf.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PsLoadOptions](#PsLoadOptions--) | Membuat opsi pemuatan untuk mengonversi PostScript menjadi dokumen pdf dengan jalur dasar kosong. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFontsFolders](#getFontsFolders--) | Mendapatkan jalur folder font. Folder dengan font tambahan untuk konversi. |
| [isConvertFontsToTTF](#isConvertFontsToTTF--) | Menentukan apakah akan menyimpan font non-TrueType ke TTF. Ini secara signifikan mengurangi volume dokumen yang dihasilkan dalam konversi PS ke PDF dan meningkatkan kecepatan konversi file PS dengan sejumlah besar teks dalam font non-TrueType ke format output apa pun. Namun, terdapat sedikit pergeseran vertikal teks saat mengonversi file PostSctipt menjadi gambar. |
| [setConvertFontsToTTF](#setConvertFontsToTTF-boolean-) | Menentukan apakah akan menyimpan font non-TrueType ke TTF. Ini secara signifikan mengurangi volume dokumen yang dihasilkan dalam konversi PS ke PDF dan meningkatkan kecepatan konversi file PS dengan sejumlah besar teks dalam font non-TrueType ke format output apa pun. Namun, terdapat sedikit pergeseran vertikal teks saat mengonversi file PostSctipt menjadi gambar. |
| [setFontsFolders](#setFontsFolders-java.lang.String:A-) | Mengatur jalur folder font. Folder dengan font tambahan untuk konversi. |

### PsLoadOptions {#PsLoadOptions--}
```
public PsLoadOptions()
```

Membuat opsi pemuatan untuk mengonversi PostScript menjadi dokumen pdf dengan jalur dasar kosong.

### getFontsFolders {#getFontsFolders--}
```
public String [] getFontsFolders()
```

Mendapatkan jalur folder font. Folder dengan font tambahan untuk konversi.

**Returns:**
array nilai String

### isConvertFontsToTTF {#isConvertFontsToTTF--}
```
public final boolean isConvertFontsToTTF()
```

Menentukan apakah akan menyimpan font non-TrueType ke TTF. Ini secara signifikan mengurangi volume dokumen yang dihasilkan dalam konversi PS ke PDF dan meningkatkan kecepatan konversi file PS dengan sejumlah besar teks dalam font non-TrueType ke format output apa pun. Namun, terdapat sedikit pergeseran vertikal teks saat mengonversi file PostSctipt menjadi gambar.

**Returns:**
nilai boolean

### setConvertFontsToTTF {#setConvertFontsToTTF-boolean-}
```
public final void setConvertFontsToTTF(boolean value)
```

Menentukan apakah akan menyimpan font non-TrueType ke TTF. Ini secara signifikan mengurangi volume dokumen yang dihasilkan dalam konversi PS ke PDF dan meningkatkan kecepatan konversi file PS dengan sejumlah besar teks dalam font non-TrueType ke format output apa pun. Namun, terdapat sedikit pergeseran vertikal teks saat mengonversi file PostSctipt menjadi gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setFontsFolders {#setFontsFolders-java.lang.String:A-}
Mengatur jalur folder font. Folder dengan font tambahan untuk konversi.
