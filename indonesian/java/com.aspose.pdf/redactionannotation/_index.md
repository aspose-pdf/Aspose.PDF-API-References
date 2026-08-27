---
title: "RedactionAnnotation"
linktitle: "RedactionAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Merepresentasikan anotasi Redact."
type: docs
weight: 4120
url: /id/java/com.aspose.pdf/redactionannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.RedactionAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class RedactionAnnotation extends MarkupAnnotation
```

Merepresentasikan anotasi Redact.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.IDocument-) | Konstruktor untuk RedactionAnnotation. Untuk digunakan dalam Generator. |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Konstruktor untuk RedactAnnotation. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima objek visitor untuk memproses anotasi. |
| [flatten](#flatten--) | Meratakan anotasi yaitu menghapus anotasi dan menambahkan isinya |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. |
| [getBorderColor](#getBorderColor--) | Mendapatkan warna border yang digambar ketika redaction tidak aktif. |
| [getDefaultAppearance](#getDefaultAppearance--) | Mendapatkan atau mengatur string tampilan default yang akan digunakan dalam memformat teks. |
| [getFillColor](#getFillColor--) | Mendapatkan warna untuk mengisi anotasi. |
| [getFontSize](#getFontSize--) | Mendapatkan ukuran font untuk OverlayText. |
| [getOverlayText](#getOverlayText--) | Mendapatkan teks untuk dicetak pada anotasi redaksi. |
| [getQuadPoint](#getQuadPoint--) | Array berukuran 8xN angka yang menentukan koordinat wilayah konten yang dimaksud untuk dihapus. |
| [getQuadPoints](#getQuadPoints--) | Mendapatkan array titik yang menentukan koordinat dari n segiempat. Setiap segiempat mencakup satu kata atau kelompok kata yang berurutan dalam teks yang menjadi dasar anotasi. |
| [getTextAlignment](#getTextAlignment--) | Mendapatkan perataan Teks Overlay. |
| [isRepeat](#isRepeat--) | Jika true, teks overlay akan diulang pada anotasi. |
| [redact](#redact--) | Meratakan anotasi dan menyensor konten halaman (misalnya menghapus teks dan konten gambar di bawah anotasi yang disensor) |
| [redactExact](#redactExact--) | Meratakan anotasi dan menyensor konten halaman (misalnya menghapus teks dan konten gambar tepat di bawah anotasi yang disensor) |
| [setBorderColor](#setBorderColor-com.aspose.pdf.Color-) | Mengatur warna batas yang digambar ketika penyensoran tidak aktif. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Mendapatkan atau mengatur string tampilan default yang akan digunakan dalam memformat teks. |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | Mengatur warna untuk mengisi anotasi. |
| [setFontSize](#setFontSize-float-) | Mengatur ukuran font untuk OverlayText. Nilai default adalah 10. |
| [setOverlayText](#setOverlayText-java.lang.String-) | Mengatur teks untuk dicetak pada anotasi redaksi. |
| [setQuadPoint](#setQuadPoint-com.aspose.pdf.Point:A-) | Array berukuran 8xN angka yang menentukan koordinat wilayah konten yang dimaksud untuk dihapus. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Mengatur array titik yang menentukan koordinat dari n segiempat. Setiap segiempat mencakup satu kata atau kelompok kata yang berurutan dalam teks yang menjadi dasar anotasi. |
| [setRepeat](#setRepeat-boolean-) | Jika true, teks overlay akan diulang pada anotasi. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Mengatur perataan Teks Overlay. |

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.IDocument-}
Konstruktor untuk RedactionAnnotation. Untuk digunakan dalam Generator.

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Konstruktor untuk RedactAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima objek visitor untuk memproses anotasi.

### flatten {#flatten--}
```
public void flatten()
```

Meratakan anotasi yaitu menghapus anotasi dan menambahkan isinya

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi.

**Returns:**
Elemen AnnotationType @see AnnotationType

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

Mendapatkan warna border yang digambar ketika redaction tidak aktif.

**Returns:**
Nilai warna

### getDefaultAppearance {#getDefaultAppearance--}
```
public final String getDefaultAppearance()
```

Mendapatkan atau mengatur string tampilan default yang akan digunakan dalam memformat teks.

**Returns:**
nilai String

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

Mendapatkan warna untuk mengisi anotasi.

**Returns:**
nilai warna

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Mendapatkan ukuran font untuk OverlayText.

**Returns:**
nilai int

### getOverlayText {#getOverlayText--}
```
public String getOverlayText()
```

Mendapatkan teks untuk dicetak pada anotasi redaksi.

**Returns:**
nilai string

### getQuadPoint {#getQuadPoint--}
```
public Point [] getQuadPoint()
```

Array berukuran 8xN angka yang menentukan koordinat wilayah konten yang dimaksud untuk dihapus.

**Returns:**
array titik

### getQuadPoints {#getQuadPoints--}
```
@Deprecated public Point [] getQuadPoints()
```

Mendapatkan array titik yang menentukan koordinat dari n segiempat. Setiap segiempat mencakup satu kata atau kelompok kata yang berurutan dalam teks yang menjadi dasar anotasi.

**Returns:**
array nilai Point

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Mendapatkan perataan Teks Overlay.

**Returns:**
Nilai HorizontalAlignment @see HorizontalAlignment

### isRepeat {#isRepeat--}
```
public boolean isRepeat()
```

Jika true, teks overlay akan diulang pada anotasi.

**Returns:**
nilai boolean

### redact {#redact--}
```
public void redact()
```

Meratakan anotasi dan menyensor konten halaman (misalnya menghapus teks dan konten gambar di bawah anotasi yang disensor)

### redactExact {#redactExact--}
```
public void redactExact()
```

Meratakan anotasi dan menyensor konten halaman (misalnya menghapus teks dan konten gambar tepat di bawah anotasi yang disensor)

### setBorderColor {#setBorderColor-com.aspose.pdf.Color-}
Mengatur warna batas yang digambar ketika penyensoran tidak aktif.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Mendapatkan atau mengatur string tampilan default yang akan digunakan dalam memformat teks.

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
Mengatur warna untuk mengisi anotasi.

### setFontSize {#setFontSize-float-}
```
public final void setFontSize(float fontSize)
```

Mengatur ukuran font untuk OverlayText. Nilai default adalah 10.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontSize |  | nilai int |

### setOverlayText {#setOverlayText-java.lang.String-}
Mengatur teks untuk dicetak pada anotasi redaksi.

### setQuadPoint {#setQuadPoint-com.aspose.pdf.Point:A-}
Array berukuran 8xN angka yang menentukan koordinat wilayah konten yang dimaksud untuk dihapus.

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Mengatur array titik yang menentukan koordinat dari n segiempat. Setiap segiempat mencakup satu kata atau kelompok kata yang berurutan dalam teks yang menjadi dasar anotasi.

### setRepeat {#setRepeat-boolean-}
```
public void setRepeat(boolean value)
```

Jika true, teks overlay akan diulang pada anotasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Mengatur perataan Teks Overlay.
