---
title: "TextDefaults.DefaultFontStrategy"
linktitle: "TextDefaults.DefaultFontStrategy"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Menentukan jenis nilai default subsistem teks"
type: docs
weight: 4960
url: /id/java/com.aspose.pdf/textdefaults.defaultfontstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.TextDefaults.DefaultFontStrategy

```
public static class TextDefaults.DefaultFontStrategy extends com.aspose.ms.System.Enum
```

Menentukan jenis nilai default subsistem teks

## Fields

| Field | Deskripsi |
| --- | --- |
| [ListOfFonts](#ListOfFonts) | Gunakan font default dari daftar font yang telah ditentukan sebelumnya. Dapat diatur menggunakan setDefaultFonts(List of Font instances). Font pertama yang ditemukan yang berisi semua karakter yang diperlukan untuk teks akan digunakan. Jika font tersebut tidak ditemukan - akan digunakan font Sistem. |
| [PredefinedFont](#PredefinedFont) | Gunakan font default tersebut. Dapat diatur menggunakan set/get PredefinedFont(Font) jika PredefinedFont bernilai null - akan digunakan SystemFont. |
| [SystemFont](#SystemFont) | Gunakan font sistem default Helvetica, atau analognya yang menggantikan. |
| [TheFirstSuitableFoundFont](#TheFirstSuitableFoundFont) | Font pertama yang ditemukan akan digunakan, yang berisi semua karakter yang diperlukan untuk teks. Semua font yang ditemukan akan terlibat. Jika font tersebut tidak ditemukan - akan digunakan font Sistem. |

### ListOfFonts {#ListOfFonts}
```
public static final int ListOfFonts
```

Gunakan font default dari daftar font yang telah ditentukan sebelumnya. Dapat diatur menggunakan setDefaultFonts(List of Font instances). Font pertama yang ditemukan yang berisi semua karakter yang diperlukan untuk teks akan digunakan. Jika font tersebut tidak ditemukan - akan digunakan font Sistem.

### PredefinedFont {#PredefinedFont}
```
public static final int PredefinedFont
```

Gunakan font default tersebut. Dapat diatur menggunakan set/get PredefinedFont(Font) jika PredefinedFont bernilai null - akan digunakan SystemFont.

### SystemFont {#SystemFont}
```
public static final int SystemFont
```

Gunakan font sistem default Helvetica, atau analognya yang menggantikan.

### TheFirstSuitableFoundFont {#TheFirstSuitableFoundFont}
```
public static final int TheFirstSuitableFoundFont
```

Font pertama yang ditemukan akan digunakan, yang berisi semua karakter yang diperlukan untuk teks. Semua font yang ditemukan akan terlibat. Jika font tersebut tidak ditemukan - akan digunakan font Sistem.
