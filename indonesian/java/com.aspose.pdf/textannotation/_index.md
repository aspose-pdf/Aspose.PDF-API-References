---
title: "TextAnnotation"
linktitle: "TextAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili anotasi teks yang merupakan \\\"sticky note\\\" yang terpasang pada suatu titik dalam dokumen PDF."
type: docs
weight: 4920
url: /id/java/com.aspose.pdf/textannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class TextAnnotation extends MarkupAnnotation
```

Mewakili anotasi teks yang berupa "sticky note" yang terpasang pada suatu titik dalam dokumen PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextAnnotation](#TextAnnotation--) | Buat instance TextAnnotation |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.IDocument-) | Buat instance TextAnnotation |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Buat instance TextAnnotation |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima objek visitor untuk memproses anotasi. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Menimpa definisi di kelas dasar dengan tubuh kosong. |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. |
| [getIcon](#getIcon--) | Mendapatkan ikon yang akan digunakan untuk menampilkan anotasi. |
| [getOpen](#getOpen--) | Mendapatkan flag yang menentukan apakah anotasi harus ditampilkan terbuka pada awalnya. |
| [setIcon](#setIcon-int-) | Mengatur ikon yang akan digunakan untuk menampilkan anotasi. |
| [setOpen](#setOpen-boolean-) | Mengatur flag yang menentukan apakah anotasi harus ditampilkan terbuka pada awalnya. |

### TextAnnotation {#TextAnnotation--}
```
public TextAnnotation()
```

Buat instance TextAnnotation

### TextAnnotation {#TextAnnotation-com.aspose.pdf.IDocument-}
Buat instance TextAnnotation

### TextAnnotation {#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Buat instance TextAnnotation

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima objek visitor untuk memproses anotasi.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Menimpa definisi di kelas dasar dengan tubuh kosong.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi.

**Returns:**
Nilai AnnotationType @see AnnotationState

### getIcon {#getIcon--}
```
public int getIcon()
```

Mendapatkan ikon yang akan digunakan untuk menampilkan anotasi.

**Returns:**
Nilai TextIcon @see TextIcon

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Mendapatkan flag yang menentukan apakah anotasi harus ditampilkan terbuka pada awalnya.

**Returns:**
nilai boolean

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Mengatur ikon yang akan digunakan untuk menampilkan anotasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Nilai TextIcon @see TextIcon |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Mengatur flag yang menentukan apakah anotasi harus ditampilkan terbuka pada awalnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
