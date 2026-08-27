---
title: "SetGlyphsPositionShowText"
linktitle: "SetGlyphsPositionShowText"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator TJ (menampilkan teks dengan penempatan glif)."
type: docs
weight: 630
url: /id/java/com.aspose.pdf.operators/setglyphspositionshowtext/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextShowOperator com.aspose.pdf.operators.SetGlyphsPositionShowText, com.aspose.pdf.operators.TextShowOperator, com.aspose.pdf.operators.SetGlyphsPositionShowText

```
public class SetGlyphsPositionShowText extends TextShowOperator
```

Kelas yang mewakili operator TJ (menampilkan teks dengan penempatan glif).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText--) | Menginisialisasi operator. |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-) | Menginisialisasi operator. |
| [SetGlyphsPositionShowText](#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textshowing.ShowTextWithPositions-) | Menginisialisasi operator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getGlyphPositions](#getGlyphPositions--) | Mengembalikan posisi glyph. |
| [getText](#getText--) | Mendapatkan teks dari argumen operator (posisi glyph diabaikan). |
| [toString](#toString--) | Mengembalikan representasi teks operator. |

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText--}
```
public SetGlyphsPositionShowText()
```

Menginisialisasi operator.

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-}
Menginisialisasi operator.

### SetGlyphsPositionShowText {#SetGlyphsPositionShowText-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textshowing.ShowTextWithPositions-}
Menginisialisasi operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getGlyphPositions {#getGlyphPositions--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerable< GlyphPosition > getGlyphPositions()
```

Mengembalikan posisi glyph.

**Returns:**
koleksi instance GlyphPosition

### getText {#getText--}
```
public String getText()
```

Mendapatkan teks dari argumen operator (posisi glyph diabaikan).

**Returns:**
nilai String

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi teks operator.

**Returns:**
Representasi teks dari operator.
