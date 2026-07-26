---
title: "TextReplaceOptions.ReplaceAdjustment"
linktitle: "TextReplaceOptions.ReplaceAdjustment"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Menentukan aksi yang akan dilakukan setelah mengganti fragmen teks menjadi lebih pendek. None - tidak ada aksi, teks yang diganti dapat tumpang tindih dengan sisa baris; AdjustSpaceWidth - mencoba."
type: docs
weight: 5270
url: /id/java/com.aspose.pdf/textreplaceoptions.replaceadjustment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.Enum, com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment

```
public static final class TextReplaceOptions.ReplaceAdjustment extends com.aspose.ms.System.Enum
```

Menentukan aksi yang akan dilakukan setelah mengganti fragmen teks menjadi lebih pendek. None - tidak ada aksi, teks yang diganti dapat tumpang tindih dengan sisa baris; AdjustSpaceWidth - mencoba menyesuaikan spasi antar kata untuk mempertahankan panjang baris; WholeWordsHyphenation - mencoba mendistribusikan kata antar baris paragraf untuk mempertahankan bidang kanan paragraf; ShiftRestOfLine - menggeser sisa baris sesuai dengan perubahan panjang teks, panjang baris dapat diubah; Nilai default adalah ShiftRestOfLine.

## Fields

| Field | Deskripsi |
| --- | --- |
| [AdjustSpaceWidth](#AdjustSpaceWidth) | Mencoba menyesuaikan spasi antar kata untuk mempertahankan panjang baris |
| [IsFormFillingMode](#IsFormFillingMode) | Mencoba menyebarkan kata-kata dalam ruang putih yang tersedia menggunakan lebar paragraf. Jika teks meluap, akan disembunyikan. |
| [None](#None) | Tidak ada aksi, teks yang diganti dapat tumpang tindih dengan sisa baris |
| [ShiftRestOfLine](#ShiftRestOfLine) | (Default) Menggeser sisa baris sesuai dengan perubahan panjang teks, panjang baris dapat diubah |
| [WholeWordsHyphenation](#WholeWordsHyphenation) | Mencoba mendistribusikan kata-kata antara baris paragraf untuk mempertahankan bidang kanan paragraf |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) |  |

### AdjustSpaceWidth {#AdjustSpaceWidth}
```
public static final int AdjustSpaceWidth
```

Mencoba menyesuaikan spasi antar kata untuk mempertahankan panjang baris

### IsFormFillingMode {#IsFormFillingMode}
```
public static final int IsFormFillingMode
```

Mencoba menyebarkan kata-kata dalam ruang putih yang tersedia menggunakan lebar paragraf. Jika teks meluap, akan disembunyikan.

### None {#None}
```
public static final int None
```

Tidak ada aksi, teks yang diganti dapat tumpang tindih dengan sisa baris

### ShiftRestOfLine {#ShiftRestOfLine}
```
public static final int ShiftRestOfLine
```

(Default) Menggeser sisa baris sesuai dengan perubahan panjang teks, panjang baris dapat diubah

### WholeWordsHyphenation {#WholeWordsHyphenation}
```
public static final int WholeWordsHyphenation
```

Mencoba mendistribusikan kata-kata antara baris paragraf untuk mempertahankan bidang kanan paragraf

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| flag |  |  |
| flagToCheck |  |  |
