---
title: "WidgetAnnotation"
linktitle: "WidgetAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili anotasi widget."
type: docs
weight: 5540
url: /id/java/com.aspose.pdf/widgetannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class WidgetAnnotation extends Annotation
```

Kelas yang mewakili anotasi widget.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [WidgetAnnotation](#WidgetAnnotation-com.aspose.pdf.IDocument-) | Buat anotasi (digunakan untuk Generator) |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima visitor. |
| [getAnnotationActions](#getAnnotationActions--) | Mendapatkan aksi anotasi. |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. |
| [getCheckedStateName](#getCheckedStateName--) | Mengembalikan nama status "checked" sesuai dengan nama status yang ada. |
| [getDefaultAppearance](#getDefaultAppearance--) | Mendapatkan tampilan default bidang. |
| [getExportable](#getExportable--) | Mendapatkan flag dapat diekspor dari bidang. |
| [getHighlighting](#getHighlighting--) | Mode penyorotan anotasi. |
| [getOnActivated](#getOnActivated--) | Dapatkan aksi yang harus dilakukan ketika anotasi diaktifkan. |
| [getParent](#getParent--) | Mendapatkan induk anotasi. |
| [getReadOnly](#getReadOnly--) | Mendapatkan status hanya baca bidang. |
| [getRequired](#getRequired--) | Mendapatkan status wajib bidang. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Mengatur tampilan default bidang. |
| [setExportable](#setExportable-boolean-) | Mengatur status hanya baca bidang. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Mode penyorotan anotasi. |
| [setOnActivated](#setOnActivated-com.aspose.pdf.PdfAction-) | Atur aksi yang harus dilakukan ketika anotasi diaktifkan. |
| [setReadOnly](#setReadOnly-boolean-) | Mengatur status hanya baca bidang. |
| [setRequired](#setRequired-boolean-) | Mengatur status hanya baca bidang. |

### WidgetAnnotation {#WidgetAnnotation-com.aspose.pdf.IDocument-}
Buat anotasi (digunakan untuk Generator)

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima visitor.

### getAnnotationActions {#getAnnotationActions--}
```
public AnnotationActionCollection getAnnotationActions()
```

Mendapatkan aksi anotasi.

**Returns:**
Objek AnnotationActionCollection

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi.

**Returns:**
Elemen AnnotationType @see AnnotationType

### getCheckedStateName {#getCheckedStateName--}
```
public final String getCheckedStateName()
```

Mengembalikan nama status "checked" sesuai dengan nama status yang ada.

**Returns:**
Nama status "checked" untuk anotasi ini.

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Mendapatkan tampilan default bidang.

**Returns:**
objek DefaultAppearance

### getExportable {#getExportable--}
```
public boolean getExportable()
```

Mendapatkan flag dapat diekspor dari bidang.

**Returns:**
nilai boolean

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Mode penyorotan anotasi.

**Returns:**
Nilai HighlightingMode @see HighlightingMode

### getOnActivated {#getOnActivated--}
```
public PdfAction getOnActivated()
```

Dapatkan aksi yang harus dilakukan ketika anotasi diaktifkan.

**Returns:**
PdfAction objek

### getParent {#getParent--}
```
public Field getParent()
```

Mendapatkan induk anotasi.

**Returns:**
Objek Field

### getReadOnly {#getReadOnly--}
```
public boolean getReadOnly()
```

Mendapatkan status hanya baca bidang.

**Returns:**
nilai boolean

### getRequired {#getRequired--}
```
public boolean getRequired()
```

Mendapatkan status wajib bidang.

**Returns:**
nilai boolean

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Mengatur tampilan default bidang.

### setExportable {#setExportable-boolean-}
```
public void setExportable(boolean value)
```

Mengatur status hanya baca bidang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Mode penyorotan anotasi.

### setOnActivated {#setOnActivated-com.aspose.pdf.PdfAction-}
Atur aksi yang harus dilakukan ketika anotasi diaktifkan.

### setReadOnly {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```

Mengatur status hanya baca bidang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRequired {#setRequired-boolean-}
```
public void setRequired(boolean value)
```

Mengatur status hanya baca bidang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
