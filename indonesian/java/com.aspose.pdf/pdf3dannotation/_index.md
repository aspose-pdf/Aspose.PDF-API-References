---
title: "PDF3DAnnotation"
linktitle: "PDF3DAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas PDF3DAnnotation. Kelas ini tidak dapat diwarisi. @see Annotation"
type: docs
weight: 3560
url: /id/java/com.aspose.pdf/pdf3dannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PDF3DAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PDF3DAnnotation extends Annotation
```

Kelas PDF3DAnnotation. Kelas ini tidak dapat diwarisi. @see Annotation

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-) | Menginisialisasi instance baru dari kelas {@code PDF3DAnnotation}. |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-) | Menginisialisasi instance baru dari kelas {@code PDF3DAnnotation}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima visitor untuk pemrosesan anotasi. |
| [clearImagePreview](#clearImagePreview--) | Menghapus pratinjau gambar. |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. Nilai: Tipe anotasi. |
| [getContent](#getContent--) | Mendapatkan atau mengatur konten. Nilai: Konten. |
| [getImagePreview](#getImagePreview--) | Mendapatkan pratinjau gambar. |
| [getLightingScheme](#getLightingScheme--) | Mendapatkan skema pencahayaan. Nilai: Skema pencahayaan. |
| [getPdf3DArtwork](#getPdf3DArtwork--) | Mendapatkan Karya Seni 3D. Nilai: PDF3 d artwork. |
| [getRenderMode](#getRenderMode--) | Mendapatkan mode render. Nilai: Mode render. |
| [getViewArray](#getViewArray--) | Mendapatkan array tampilan. Nilai: Array tampilan. |
| [setContent](#setContent-com.aspose.pdf.PDF3DContent-) | Mendapatkan atau mengatur konten. Nilai: Konten. |
| [setDefaultViewIndex](#setDefaultViewIndex-int-) | Mengatur indeks tampilan default. |
| [setImagePreview](#setImagePreview-java.io.InputStream-) | Mengatur pratinjau gambar. |
| [setImagePreview](#setImagePreview-java.lang.String-) | Mengatur pratinjau gambar. |

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-}
Menginisialisasi instance baru dari kelas {@code PDF3DAnnotation}.

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-}
Menginisialisasi instance baru dari kelas {@code PDF3DAnnotation}.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima visitor untuk pemrosesan anotasi.

### clearImagePreview {#clearImagePreview--}
```
public void clearImagePreview()
```

Menghapus pratinjau gambar.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi. Nilai: Tipe anotasi.

**Returns:**
nilai int

### getContent {#getContent--}
```
public PDF3DContent getContent()
```

Mendapatkan atau mengatur konten. Nilai: Konten.

**Returns:**
PDF3DContent objek

### getImagePreview {#getImagePreview--}
```
public InputStream getImagePreview()
```

Mendapatkan pratinjau gambar.

**Returns:**
Pratinjau gambar sebagai aliran.

### getLightingScheme {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```

Mendapatkan skema pencahayaan. Nilai: Skema pencahayaan.

**Returns:**
PDF3DLightingScheme objek

### getPdf3DArtwork {#getPdf3DArtwork--}
```
public PDF3DArtwork getPdf3DArtwork()
```

Mendapatkan Karya Seni 3D. Nilai: PDF3 d artwork.

**Returns:**
objek PDF3DArtwork

### getRenderMode {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```

Mendapatkan mode render. Nilai: Mode render.

**Returns:**
objek PDF3DRenderMode

### getViewArray {#getViewArray--}
```
public PDF3DViewArray getViewArray()
```

Mendapatkan array tampilan. Nilai: Array tampilan.

**Returns:**
objek PDF3DViewArray

### setContent {#setContent-com.aspose.pdf.PDF3DContent-}
Mendapatkan atau mengatur konten. Nilai: Konten.

### setDefaultViewIndex {#setDefaultViewIndex-int-}
```
public void setDefaultViewIndex(int index)
```

Mengatur indeks tampilan default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks tampilan default. |

### setImagePreview {#setImagePreview-java.io.InputStream-}
Mengatur pratinjau gambar.

### setImagePreview {#setImagePreview-java.lang.String-}
Mengatur pratinjau gambar.
