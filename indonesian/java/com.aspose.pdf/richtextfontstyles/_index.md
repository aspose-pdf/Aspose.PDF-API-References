---
title: "RichTextFontStyles"
linktitle: "RichTextFontStyles"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Opsi untuk menata fragmen teks dalam RichText."
type: docs
weight: 4300
url: /id/java/com.aspose.pdf/richtextfontstyles/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.Enum, com.aspose.pdf.RichTextFontStyles

```
public final class RichTextFontStyles extends com.aspose.ms.System.Enum
```

Opsi untuk menata fragmen teks dalam RichText.

## Fields

| Field | Deskripsi |
| --- | --- |
| [Bold](#Bold) | Opsi yang menentukan tebal. |
| [ClearExisting](#ClearExisting) | Jika diatur, menghapus semua gaya yang ada sebelum menerapkan gaya tambahan. Ketika digabungkan dengan flag gaya lainnya (mis., {@code RichTextFontStyles#Bold}), pertama kali mereset gaya, kemudian menerapkan yang ditentukan. Tanpa flag ini, gaya baru ditambahkan ke gaya yang sudah ada. |
| [Italic](#Italic) | Opsi yang menentukan miring. |
| [Underline](#Underline) | Opsi yang menentukan garis bawah. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) | Memeriksa apakah flag yang ditentukan sudah diatur. |

### Bold {#Bold}
```
public static final int Bold
```

Opsi yang menentukan tebal.

### ClearExisting {#ClearExisting}
```
public static final int ClearExisting
```

Jika diatur, menghapus semua gaya yang ada sebelum menerapkan gaya tambahan. Ketika digabungkan dengan flag gaya lainnya (mis., {@code RichTextFontStyles#Bold}), pertama kali mereset gaya, kemudian menerapkan yang ditentukan. Tanpa flag ini, gaya baru ditambahkan ke gaya yang sudah ada.

### Italic {#Italic}
```
public static final int Italic
```

Opsi yang menentukan miring.

### Underline {#Underline}
```
public static final int Underline
```

Opsi yang menentukan garis bawah.

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```

Memeriksa apakah flag yang ditentukan sudah diatur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| flag |  | nilai enum yang mewakili flag yang akan diperiksa |
| flagToCheck |  | nilai enum yang mewakili flag yang akan diperiksa |

**Returns:**
{@code true} jika flag diatur; {@code false} jika tidak
