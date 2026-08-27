---
title: "LineAnnotation"
linktitle: "LineAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang merepresentasikan anotasi garis."
type: docs
weight: 2710
url: /id/java/com.aspose.pdf/lineannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.LineAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class LineAnnotation extends MarkupAnnotation
```

Kelas yang merepresentasikan anotasi garis.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Konstruktor untuk digunakan dengan Generator. |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Membuat anotasi Line baru pada halaman yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima pengunjung untuk pemrosesan anotasi. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Memperbarui titik Mulai dan Akhir, sesuai dengan transformasi matriks. |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. |
| [getCaptionOffset](#getCaptionOffset--) | Mendapatkan offset teks keterangan dari posisi normalnya. |
| [getCaptionPosition](#getCaptionPosition--) | Mendapatkan posisi keterangan anotasi. |
| [getEnding](#getEnding--) | Mendapatkan titik akhir garis. |
| [getEndingStyle](#getEndingStyle--) | Mendapatkan gaya akhir untuk titik akhir garis. |
| [getIntent](#getIntent--) | Mendapatkan maksud anotasi garis. |
| [getInteriorColor](#getInteriorColor--) | Mendapatkan warna interior anotasi. |
| [getLeaderLine](#getLeaderLine--) | Mendapatkan panjang garis pemimpin. |
| [getLeaderLineExtension](#getLeaderLineExtension--) | Mendapatkan panjang ekstensi garis pemimpin. |
| [getLeaderLineOffset](#getLeaderLineOffset--) | Mendapatkan offset garis pemimpin. |
| [getMeasure](#getMeasure--) | Satuan ukuran yang ditentukan untuk anotasi ini. |
| [getShowCaption](#getShowCaption--) | Mendapatkan flag boolean yang menentukan apakah konten harus ditampilkan sebagai keterangan. |
| [getStarting](#getStarting--) | Mendapatkan titik mulai garis. |
| [getStartingStyle](#getStartingStyle--) | Mendapatkan gaya akhir garis untuk titik mulai garis. |
| [setCaptionOffset](#setCaptionOffset-com.aspose.pdf.Point-) | Mengatur offset teks keterangan dari posisi normalnya. |
| [setCaptionPosition](#setCaptionPosition-com.aspose.pdf.CaptionPosition-) | Mengatur posisi keterangan anotasi. |
| [setEnding](#setEnding-com.aspose.pdf.Point-) | Mengatur titik akhir garis. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Mengatur gaya akhir untuk titik akhir garis. |
| [setIntent](#setIntent-com.aspose.pdf.LineIntent-) | Mengatur maksud anotasi garis. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Mengatur warna interior anotasi. |
| [setLeaderLine](#setLeaderLine-double-) | Mengatur panjang garis pemimpin. |
| [setLeaderLineExtension](#setLeaderLineExtension-double-) | Mengatur panjang ekstensi garis pemimpin. |
| [setLeaderLineOffset](#setLeaderLineOffset-double-) | Mengatur offset garis pemimpin. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Satuan ukuran yang ditentukan untuk anotasi ini. |
| [setShowCaption](#setShowCaption-boolean-) | Mengatur flag boolean yang menentukan apakah konten harus ditampilkan sebagai caption. |
| [setStarting](#setStarting-com.aspose.pdf.Point-) | Mengatur titik awal garis. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Mengatur gaya akhir garis untuk titik awal garis. |

### LineAnnotation {#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Konstruktor untuk digunakan dengan Generator.

### LineAnnotation {#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Membuat anotasi Line baru pada halaman yang ditentukan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima pengunjung untuk pemrosesan anotasi.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Memperbarui titik Mulai dan Akhir, sesuai dengan transformasi matriks.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi.

**Returns:**
Elemen AnnotationType @see AnnotationType

### getCaptionOffset {#getCaptionOffset--}
```
public Point getCaptionOffset()
```

Mendapatkan offset teks keterangan dari posisi normalnya.

**Returns:**
Objek Point

### getCaptionPosition {#getCaptionPosition--}
```
public CaptionPosition getCaptionPosition()
```

Mendapatkan posisi keterangan anotasi.

**Returns:**
Elemen CaptionPosition @see CaptionPosition

### getEnding {#getEnding--}
```
public Point getEnding()
```

Mendapatkan titik akhir garis.

**Returns:**
Nilai titik

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Mendapatkan gaya akhir untuk titik akhir garis.

**Returns:**
Elemen LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public LineIntent getIntent()
```

Mendapatkan maksud anotasi garis.

**Returns:**
Elemen LineIntent @see LineIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Mendapatkan warna interior anotasi.

**Returns:**
objek Color

### getLeaderLine {#getLeaderLine--}
```
public double getLeaderLine()
```

Mendapatkan panjang garis pemimpin.

**Returns:**
nilai double

### getLeaderLineExtension {#getLeaderLineExtension--}
```
public double getLeaderLineExtension()
```

Mendapatkan panjang ekstensi garis pemimpin.

**Returns:**
nilai double

### getLeaderLineOffset {#getLeaderLineOffset--}
```
public double getLeaderLineOffset()
```

Mendapatkan offset garis pemimpin.

**Returns:**
nilai double

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Satuan ukuran yang ditentukan untuk anotasi ini.

**Returns:**
Objek Measure

### getShowCaption {#getShowCaption--}
```
public boolean getShowCaption()
```

Mendapatkan flag boolean yang menentukan apakah konten harus ditampilkan sebagai keterangan.

**Returns:**
nilai boolean

### getStarting {#getStarting--}
```
public Point getStarting()
```

Mendapatkan titik mulai garis.

**Returns:**
Nilai titik

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Mendapatkan gaya akhir garis untuk titik mulai garis.

**Returns:**
Elemen LineEnding @see LineEnding

### setCaptionOffset {#setCaptionOffset-com.aspose.pdf.Point-}
Mengatur offset teks keterangan dari posisi normalnya.

### setCaptionPosition {#setCaptionPosition-com.aspose.pdf.CaptionPosition-}
Mengatur posisi keterangan anotasi.

### setEnding {#setEnding-com.aspose.pdf.Point-}
Mengatur titik akhir garis.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Mengatur gaya akhir untuk titik akhir garis.

### setIntent {#setIntent-com.aspose.pdf.LineIntent-}
Mengatur maksud anotasi garis.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Mengatur warna interior anotasi.

### setLeaderLine {#setLeaderLine-double-}
```
public void setLeaderLine(double value)
```

Mengatur panjang garis pemimpin.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setLeaderLineExtension {#setLeaderLineExtension-double-}
```
public void setLeaderLineExtension(double value)
```

Mengatur panjang ekstensi garis pemimpin.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setLeaderLineOffset {#setLeaderLineOffset-double-}
```
public void setLeaderLineOffset(double value)
```

Mengatur offset garis pemimpin.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Satuan ukuran yang ditentukan untuk anotasi ini.

### setShowCaption {#setShowCaption-boolean-}
```
public void setShowCaption(boolean value)
```

Mengatur flag boolean yang menentukan apakah konten harus ditampilkan sebagai caption.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setStarting {#setStarting-com.aspose.pdf.Point-}
Mengatur titik awal garis.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Mengatur gaya akhir garis untuk titik awal garis.
