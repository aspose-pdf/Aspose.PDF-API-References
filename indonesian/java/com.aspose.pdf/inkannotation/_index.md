---
title: "InkAnnotation"
linktitle: "InkAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili \\\"scribble\\\" bebas tangan yang terdiri dari satu atau lebih jalur terpisah."
type: docs
weight: 2430
url: /id/java/com.aspose.pdf/inkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.InkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class InkAnnotation extends MarkupAnnotation
```

Mewakili "coretan" bebas yang terdiri dari satu atau lebih jalur terpisah.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-) | Konstruktor untuk anotasi Ink bagi Generator. |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-) | Membuat anotasi Ink baru pada halaman yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima objek visitor untuk memproses anotasi. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Memperbarui titik-titik dalam InkList, sesuai dengan transformasi matriks. |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. |
| [getCapStyle](#getCapStyle--) | dapatkan gaya ujung garis anotasi ink. |
| [getInkList](#getInkList--) | <p> Mendapatkan daftar gestur yang merupakan garis independen yang direpresentasikan oleh array Point[]. </p> |
| [setCapStyle](#setCapStyle-com.aspose.pdf.CapStyle-) | Atur gaya akhir garis anotasi tinta. |
| [setInkList](#setInkList-java.util.List-) | Mengatur daftar gestur yang merupakan garis independen yang direpresentasikan oleh array Point[]. |
| [updateAppearance](#updateAppearance--) | Memperbarui Appearance, setelah teks diubah/dipindahkan. |

### InkAnnotation {#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-}
Konstruktor untuk anotasi Ink bagi Generator.

### InkAnnotation {#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-}
Membuat anotasi Ink baru pada halaman yang ditentukan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima objek visitor untuk memproses anotasi.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Memperbarui titik-titik dalam InkList, sesuai dengan transformasi matriks.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi.

**Returns:**
Elemen AnnotationType @see AnnotationType

### getCapStyle {#getCapStyle--}
```
public CapStyle getCapStyle()
```

dapatkan gaya ujung garis anotasi ink.

**Returns:**
Elemen CapStyle @see CapStyle

### getInkList {#getInkList--}
```
public List < Point []> getInkList()
```

<p> Mendapatkan daftar gestur yang merupakan garis independen yang direpresentasikan oleh array Point[]. </p>

**Returns:**
{@code List<Point[]>} objek

### setCapStyle {#setCapStyle-com.aspose.pdf.CapStyle-}
Atur gaya akhir garis anotasi tinta.

### setInkList {#setInkList-java.util.List-}
Mengatur daftar gestur yang merupakan garis independen yang direpresentasikan oleh array Point[].

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Memperbarui Appearance, setelah teks diubah/dipindahkan.
