---
title: "HtmlSaveOptions.FontEncodingRules"
linktitle: "HtmlSaveOptions.FontEncodingRules"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Enumerasi ini mendefinisikan aturan yang menyesuaikan logika enkoding"
type: docs
weight: 2050
url: /id/java/com.aspose.pdf/htmlsaveoptions.fontencodingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.FontEncodingRules

```
public static final class HtmlSaveOptions.FontEncodingRules extends com.aspose.ms.System.Enum
```

Enumerasi ini mendefinisikan aturan yang menyesuaikan logika enkoding

## Fields

| Field | Deskripsi |
| --- | --- |
| [DecreaseToUnicodePriorityLevel](#DecreaseToUnicodePriorityLevel) | ToUnicode adalah mekanisme khusus yang membantu mendekode kode input menjadi simbol unicode. Menurut spesifikasi, mekanisme ini harus digunakan sebagai mekanisme pertama untuk mendapatkan simbol unicode untuk kode input tertentu. Namun beberapa dokumen memiliki font non-standar dan untuk mengonversi dokumen-dokumen ini dengan benar mungkin perlu menurunkan prioritas ToUnicode dan menggunakan mekanisme lain untuk mendekode kode input. |
| [Default](#Default) | Biarkan logika pengkodean "as is" - sesuai dengan spesifikasi PDF |

### DecreaseToUnicodePriorityLevel {#DecreaseToUnicodePriorityLevel}
```
public static final byte DecreaseToUnicodePriorityLevel
```

ToUnicode adalah mekanisme khusus yang membantu mendekode kode input menjadi simbol unicode. Menurut spesifikasi, mekanisme ini harus digunakan sebagai mekanisme pertama untuk mendapatkan simbol unicode untuk kode input tertentu. Namun beberapa dokumen memiliki font non-standar dan untuk mengonversi dokumen-dokumen ini dengan benar mungkin perlu menurunkan prioritas ToUnicode dan menggunakan mekanisme lain untuk mendekode kode input.

### Default {#Default}
```
public static final byte Default
```

Biarkan logika pengkodean "as is" - sesuai dengan spesifikasi PDF
