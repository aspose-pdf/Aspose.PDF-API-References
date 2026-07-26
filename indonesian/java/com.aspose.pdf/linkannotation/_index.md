---
title: "LinkAnnotation"
linktitle: "LinkAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili baik tautan hiperteks ke tujuan lain dalam dokumen maupun aksi yang akan dilakukan."
type: docs
weight: 2760
url: /id/java/com.aspose.pdf/linkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.LinkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class LinkAnnotation extends Annotation
```

Mewakili baik tautan hiperteks ke tujuan lain dalam dokumen maupun aksi yang akan dilakukan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LinkAnnotation](#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Membuat anotasi Link baru pada halaman yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima objek visitor untuk memproses anotasi. |
| [getAction](#getAction--) | Dapatkan aksi yang akan dilakukan ketika anotasi link diaktifkan. |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. |
| [getDestination](#getDestination--) | Dapatkan tujuan yang akan ditampilkan ketika anotasi diaktifkan. |
| [getHighlighting](#getHighlighting--) | Dapatkan efek visual yang akan digunakan ketika tombol mouse ditekan atau ditahan di dalam area aktifnya. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Atur aksi yang akan dilakukan ketika anotasi link diaktifkan. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Atur tujuan yang akan ditampilkan ketika anotasi diaktifkan. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Atur efek visual yang akan digunakan ketika tombol mouse ditekan atau ditahan di dalam area aktifnya. |

### LinkAnnotation {#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Membuat anotasi Link baru pada halaman yang ditentukan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima objek visitor untuk memproses anotasi.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Dapatkan aksi yang akan dilakukan ketika anotasi link diaktifkan.

**Returns:**
Nilai PdfAction

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi.

**Returns:**
Elemen AnnotationType @see AnnotationType

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Dapatkan tujuan yang akan ditampilkan ketika anotasi diaktifkan.

**Returns:**
nilai IAppointment

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Dapatkan efek visual yang akan digunakan ketika tombol mouse ditekan atau ditahan di dalam area aktifnya.

**Returns:**
Elemen HighlightingMode @see HighlightingMode

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Atur aksi yang akan dilakukan ketika anotasi link diaktifkan.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Atur tujuan yang akan ditampilkan ketika anotasi diaktifkan.

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Atur efek visual yang akan digunakan ketika tombol mouse ditekan atau ditahan di dalam area aktifnya.
