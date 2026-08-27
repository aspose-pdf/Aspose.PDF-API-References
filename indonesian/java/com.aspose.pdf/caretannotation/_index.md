---
title: "CaretAnnotation"
linktitle: "CaretAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili anotasi Caret."
type: docs
weight: 470
url: /id/java/com.aspose.pdf/caretannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.CaretAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class CaretAnnotation extends MarkupAnnotation
```

Kelas yang mewakili anotasi Caret.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.IDocument-) | Konstruktor untuk penggunaan di Generator. |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Membuat anotasi Caret baru pada halaman yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima objek visitor untuk memproses anotasi. |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. |
| [getFrame](#getFrame--) | Mendapatkan persegi panjang caret. |
| [getSymbol](#getSymbol--) | Mendapatkan simbol yang terkait dengan caret. {@code CaretSymbol} |
| [setFrame](#setFrame-com.aspose.pdf.Rectangle-) | Mengatur persegi panjang caret. |
| [setSymbol](#setSymbol-com.aspose.pdf.CaretSymbol-) | Mengatur ukuran halaman output untuk impor. |

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.IDocument-}
Konstruktor untuk penggunaan di Generator.

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Membuat anotasi Caret baru pada halaman yang ditentukan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima objek visitor untuk memproses anotasi.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi.

**Returns:**
Elemen AnnotationType

### getFrame {#getFrame--}
```
public Rectangle getFrame()
```

Mendapatkan persegi panjang caret.

**Returns:**
persegi panjang caret.

### getSymbol {#getSymbol--}
```
public CaretSymbol getSymbol()
```

Mendapatkan simbol yang terkait dengan caret. {@code CaretSymbol}

**Returns:**
Elemen CaretSymbol @see CaretSymbol

### setFrame {#setFrame-com.aspose.pdf.Rectangle-}
Mengatur persegi panjang caret.

### setSymbol {#setSymbol-com.aspose.pdf.CaretSymbol-}
Mengatur ukuran halaman output untuk impor.
