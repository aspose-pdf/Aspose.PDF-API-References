---
title: "HeadingRecognitionStrategy"
linktitle: "HeadingRecognitionStrategy"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili tipe strategi pengenalan header."
type: docs
weight: 30
url: /id/java/com.aspose.pdf.markdownoptions/headingrecognitionstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy

```
public final class HeadingRecognitionStrategy extends com.aspose.ms.System.Enum
```

Mewakili tipe strategi pengenalan header.

## Fields

| Field | Deskripsi |
| --- | --- |
| [Auto](#Auto) | Menyediakan pemilihan strategi pengenalan header otomatis. Ini adalah opsi default. Jika dokumen berisi bookmark, strategi {@link HeadingRecognitionStrategy#Outlines} akan dipilih, jika tidak {@link HeadingRecognitionStrategy#Heuristic}. |
| [Heuristic](#Heuristic) | Mewakili strategi pengenalan header dengan aturan heuristik dan statistik ukuran font. |
| [None](#None) | Jangan mengenali header. Opsi ini dapat berguna pada dokumen dengan format yang kompleks. |
| [Outlines](#Outlines) | Mewakili strategi pengenalan header dengan outline. |

### Auto {#Auto}
```
public static final int Auto
```

Menyediakan pemilihan strategi pengenalan header otomatis. Ini adalah opsi default. Jika dokumen berisi bookmark, strategi {@link HeadingRecognitionStrategy#Outlines} akan dipilih, jika tidak {@link HeadingRecognitionStrategy#Heuristic}.

### Heuristic {#Heuristic}
```
public static final int Heuristic
```

Mewakili strategi pengenalan header dengan aturan heuristik dan statistik ukuran font.

### None {#None}
```
public static final int None
```

Jangan mengenali header. Opsi ini dapat berguna pada dokumen dengan format yang kompleks.

### Outlines {#Outlines}
```
public static final int Outlines
```

Mewakili strategi pengenalan header dengan outline.
