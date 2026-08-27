---
title: "TextMarkupAnnotation"
linktitle: "TextMarkupAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas dasar abstrak untuk anotasi markup teks."
type: docs
weight: 5180
url: /id/java/com.aspose.pdf/textmarkupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextMarkupAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextMarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class TextMarkupAnnotation extends MarkupAnnotation
```

Kelas dasar abstrak untuk anotasi markup teks.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Memperbarui QuadPoints, sesuai dengan transformasi matriks. |
| [getMarkedText](#getMarkedText--) | Mendapatkan teks di bawah anotasi markup sebagai string. |
| [getMarkedTextFragments](#getMarkedTextFragments--) | Mendapatkan teks di bawah anotasi markup sebagai {@code TextFragmentCollection}. |
| [getQuadPoints](#getQuadPoints--) | Mendapatkan array titik yang menentukan koordinat dari n segiempat. Setiap segiempat mencakup satu kata atau kelompok kata yang berurutan dalam teks yang menjadi dasar anotasi. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Mengatur array titik yang menentukan koordinat dari n segiempat. Setiap segiempat mencakup satu kata atau kelompok kata yang berurutan dalam teks yang menjadi dasar anotasi. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Memperbarui QuadPoints, sesuai dengan transformasi matriks.

### getMarkedText {#getMarkedText--}
```
public String getMarkedText()
```

Mendapatkan teks di bawah anotasi markup sebagai string.

**Returns:**
String yang berisi teks yang berada di bawah anotasi markup.

### getMarkedTextFragments {#getMarkedTextFragments--}
```
public TextFragmentCollection getMarkedTextFragments()
```

Mendapatkan teks di bawah anotasi markup sebagai {@code TextFragmentCollection}.

**Returns:**
{@code TextFragmentCollection} yang berisi {@code TextFragment}s yang berada di bawah anotasi markup.

### getQuadPoints {#getQuadPoints--}
```
public Point [] getQuadPoints()
```

Mendapatkan array titik yang menentukan koordinat dari n segiempat. Setiap segiempat mencakup satu kata atau kelompok kata yang berurutan dalam teks yang menjadi dasar anotasi.

**Returns:**
array nilai Point

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Mengatur array titik yang menentukan koordinat dari n segiempat. Setiap segiempat mencakup satu kata atau kelompok kata yang berurutan dalam teks yang menjadi dasar anotasi.
