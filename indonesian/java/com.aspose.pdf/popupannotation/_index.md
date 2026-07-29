---
title: "PopupAnnotation"
linktitle: "PopupAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili anotasi pop-up yang menampilkan teks dalam jendela pop-up untuk entri dan penyuntingan."
type: docs
weight: 3930
url: /id/java/com.aspose.pdf/popupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PopupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PopupAnnotation extends Annotation
```

Mewakili anotasi pop-up yang menampilkan teks dalam jendela pop-up untuk entri dan penyuntingan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.IDocument-) | Konstruktor. untuk digunakan dalam Generator. |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Membuat anotasi Popup baru pada halaman yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima objek visitor untuk memproses anotasi. |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. |
| [getOpen](#getOpen--) | Mendapatkan flag yang menentukan apakah anotasi pop-up harus ditampilkan terbuka secara awal. |
| [getParent](#getParent--) | Mendapatkan anotasi induk yang akan dikaitkan dengan anotasi pop-up ini. Jika entri ini ada, entri Contents, M, C, dan T dari anotasi induk akan menggantikan entri tersebut pada anotasi pop-up itu sendiri. |
| [setOpen](#setOpen-boolean-) | Mengatur flag yang menentukan apakah anotasi pop-up harus ditampilkan terbuka secara awal. |
| [setParent](#setParent-com.aspose.pdf.MarkupAnnotation-) | Mengatur anotasi induk yang akan dikaitkan dengan anotasi pop-up ini. Jika entri ini ada, entri Contents, M, C, dan T dari anotasi induk akan menggantikan entri tersebut pada anotasi pop-up itu sendiri. |

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.IDocument-}
Konstruktor. untuk digunakan dalam Generator.

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Membuat anotasi Popup baru pada halaman yang ditentukan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima objek visitor untuk memproses anotasi.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi.

**Returns:**
Elemen AnnotationType @see AnnotationType

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Mendapatkan flag yang menentukan apakah anotasi pop-up harus ditampilkan terbuka secara awal.

**Returns:**
nilai boolean

### getParent {#getParent--}
```
public Annotation getParent()
```

Mendapatkan anotasi induk yang akan dikaitkan dengan anotasi pop-up ini. Jika entri ini ada, entri Contents, M, C, dan T dari anotasi induk akan menggantikan entri tersebut pada anotasi pop-up itu sendiri.

**Returns:**
objek MarkupAnnotation

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Mengatur flag yang menentukan apakah anotasi pop-up harus ditampilkan terbuka secara awal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setParent {#setParent-com.aspose.pdf.MarkupAnnotation-}
Mengatur anotasi induk yang akan dikaitkan dengan anotasi pop-up ini. Jika entri ini ada, entri Contents, M, C, dan T dari anotasi induk akan menggantikan entri tersebut pada anotasi pop-up itu sendiri.
