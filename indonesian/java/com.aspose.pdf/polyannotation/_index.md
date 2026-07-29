---
title: "PolyAnnotation"
linktitle: "PolyAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas dasar abstrak untuk poly-annotations."
type: docs
weight: 3890
url: /id/java/com.aspose.pdf/polyannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.PolyAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class PolyAnnotation extends MarkupAnnotation
```

Kelas dasar abstrak untuk poly-annotations.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Memperbarui titik-titik dalam Vertices, sesuai dengan transformasi matriks. |
| [getEndingStyle](#getEndingStyle--) | Mendapatkan gaya akhir baris kedua. |
| [getIntent](#getIntent--) | Mendapatkan maksud anotasi poligon atau polyline. |
| [getInteriorColor](#getInteriorColor--) | Mendapatkan warna interior yang digunakan untuk mengisi akhir garis anotasi. |
| [getMeasure](#getMeasure--) | Satuan ukuran yang ditentukan untuk anotasi ini. |
| [getStartingStyle](#getStartingStyle--) | Mendapatkan gaya akhir baris pertama. |
| [getVertices](#getVertices--) | Mendapatkan array titik yang mewakili koordinat horizontal dan vertikal setiap vertex. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Menetapkan gaya akhir baris kedua. |
| [setIntent](#setIntent-com.aspose.pdf.PolyIntent-) | Menetapkan maksud anotasi poligon atau polyline. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Menetapkan warna interior yang digunakan untuk mengisi akhir garis anotasi. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Satuan ukuran yang ditentukan untuk anotasi ini. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Menetapkan gaya akhir baris pertama. |
| [setVertices](#setVertices-com.aspose.pdf.Point:A-) | Menetapkan array titik yang mewakili koordinat horizontal dan vertikal setiap vertex. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Memperbarui titik-titik dalam Vertices, sesuai dengan transformasi matriks.

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Mendapatkan gaya akhir baris kedua.

**Returns:**
Elemen LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public PolyIntent getIntent()
```

Mendapatkan maksud anotasi poligon atau polyline.

**Returns:**
PolyIntent elemen @see PolyIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Mendapatkan warna interior yang digunakan untuk mengisi akhir garis anotasi.

**Returns:**
objek Color

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Satuan ukuran yang ditentukan untuk anotasi ini.

**Returns:**
Measure instansi

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Mendapatkan gaya akhir baris pertama.

**Returns:**
Elemen LineEnding @see LineEnding

### getVertices {#getVertices--}
```
public Point [] getVertices()
```

Mendapatkan array titik yang mewakili koordinat horizontal dan vertikal setiap vertex.

**Returns:**
array nilai Point

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Menetapkan gaya akhir baris kedua.

### setIntent {#setIntent-com.aspose.pdf.PolyIntent-}
Menetapkan maksud anotasi poligon atau polyline.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Menetapkan warna interior yang digunakan untuk mengisi akhir garis anotasi.

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Satuan ukuran yang ditentukan untuk anotasi ini.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Menetapkan gaya akhir baris pertama.

### setVertices {#setVertices-com.aspose.pdf.Point:A-}
Menetapkan array titik yang mewakili koordinat horizontal dan vertikal setiap vertex.
