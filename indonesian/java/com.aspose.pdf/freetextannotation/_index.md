---
title: "FreeTextAnnotation"
linktitle: "FreeTextAnnotation"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili anotasi teks bebas yang menampilkan teks secara langsung pada halaman. Tidak seperti anotasi teks biasa, anotasi teks bebas tidak memiliki keadaan terbuka atau tertutup; sebaliknya."
type: docs
weight: 1790
url: /id/java/com.aspose.pdf/freetextannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FreeTextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FreeTextAnnotation extends MarkupAnnotation
```

Mewakili anotasi teks bebas yang menampilkan teks langsung pada halaman. Tidak seperti anotasi teks biasa, anotasi teks bebas tidak memiliki keadaan terbuka atau tertutup; alih-alih ditampilkan dalam jendela pop-up, teks selalu terlihat.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-) | Konstruktor untuk digunakan dengan Generator. |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | Membuat anotasi FreeText baru pada halaman yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Menerima objek visitor untuk memproses anotasi. |
| [getAnnotationType](#getAnnotationType--) | Mendapatkan tipe anotasi. |
| [getCallout](#getCallout--) | Array titik yang menentukan garis panggilan. |
| [getDefaultAppearance](#getDefaultAppearance--) | Mendapatkan string tampilan default yang akan digunakan dalam memformat teks. |
| [getDefaultAppearanceObject](#getDefaultAppearanceObject--) | Objek yang mewakili tampilan default anotasi FreeText. |
| [getDefaultStyle](#getDefaultStyle--) | Mendapatkan string gaya default. |
| [getEndingStyle](#getEndingStyle--) | Mendapatkan gaya akhir garis untuk titik akhir garis. |
| [getIntent](#getIntent--) | Mendapatkan maksud anotasi teks bebas. |
| [getJustification](#getJustification--) | Mendapatkan kode yang menentukan bentuk perataan (justifikasi) yang akan digunakan dalam menampilkan teks anotasi. |
| [getRotate](#getRotate--) | Sudut rotasi anotasi. |
| [getStartingStyle](#getStartingStyle--) | Mendapatkan atau mengatur gaya akhir garis untuk titik akhir garis. Properti ini sudah usang, silakan gunakan EndingStyle. |
| [getTextRectangle](#getTextRectangle--) | Persegi panjang yang menggambarkan perbedaan numerik antara dua persegi panjang: entri Rect dari anotasi dan sebuah persegi panjang yang berada di dalam persegi panjang tersebut. Persegi panjang dalam adalah tempat teks anotasi harus ditampilkan. |
| [getTextStyle](#getTextStyle--) | Mendapatkan atau mengatur gaya teks dalam tampilan. Ketika gaya teks diubah, tampilan teks diperbarui. |
| [isValidXml](#isValidXml-java.lang.String-) |  |
| [setCallout](#setCallout-com.aspose.pdf.Point:A-) | Array titik yang menentukan garis panggilan. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Mengatur string tampilan default yang akan digunakan dalam memformat teks. |
| [setDefaultStyle](#setDefaultStyle-java.lang.String-) | Mengatur string gaya default. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Mengatur gaya akhir garis untuk titik akhir garis. |
| [setIntent](#setIntent-com.aspose.pdf.FreeTextIntent-) | Mengatur maksud anotasi teks bebas. |
| [setJustification](#setJustification-com.aspose.pdf.Justification-) | Mengatur kode yang menentukan bentuk perataan (justifikasi) yang akan digunakan dalam menampilkan teks anotasi. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Sudut rotasi anotasi. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Mendapatkan atau mengatur gaya akhir garis untuk titik akhir garis. Properti ini sudah usang, silakan gunakan EndingStyle. |
| [setTextRectangle](#setTextRectangle-com.aspose.pdf.Rectangle-) | Persegi panjang yang menggambarkan perbedaan numerik antara dua persegi panjang: entri Rect dari anotasi dan sebuah persegi panjang yang berada di dalam persegi panjang tersebut. Persegi panjang dalam adalah tempat teks anotasi harus ditampilkan. |
| [setTextStyle](#setTextStyle-int-int-int-) | Mengatur pemformatan yang ditentukan oleh parameter textStyle untuk fragmen teks dari indeks fromInd hingga indeks toInd. |
| [setTextStyle](#setTextStyle-int-java.lang.String-double-java.awt.Color-) | Mengatur pemformatan yang ditentukan oleh parameter textStyle untuk semua teks anotasi. |
| [setTextStyle](#setTextStyle-com.aspose.pdf.TextStyle-) | Mengatur gaya teks dalam tampilan. ketika gaya teks diubah, tampilan teks diperbarui. |
| [updateAppearance](#updateAppearance--) | Memperbarui Appearance, setelah teks diubah/dipindahkan. |

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-}
Konstruktor untuk digunakan dengan Generator.

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-}
Membuat anotasi FreeText baru pada halaman yang ditentukan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Menerima objek visitor untuk memproses anotasi.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Mendapatkan tipe anotasi.

**Returns:**
nilai int

### getCallout {#getCallout--}
```
public final Point [] getCallout()
```

Array titik yang menentukan garis panggilan.

**Returns:**
array dari Point

### getDefaultAppearance {#getDefaultAppearance--}
```
public String getDefaultAppearance()
```

Mendapatkan string tampilan default yang akan digunakan dalam memformat teks.

**Returns:**
nilai String

### getDefaultAppearanceObject {#getDefaultAppearanceObject--}
```
public final DefaultAppearance getDefaultAppearanceObject()
```

Objek yang mewakili tampilan default anotasi FreeText.

**Returns:**
objek DefaultAppearance

### getDefaultStyle {#getDefaultStyle--}
```
public String getDefaultStyle()
```

Mendapatkan string gaya default.

**Returns:**
nilai String

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Mendapatkan gaya akhir garis untuk titik akhir garis.

**Returns:**
nilai LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public FreeTextIntent getIntent()
```

Mendapatkan maksud anotasi teks bebas.

**Returns:**
nilai int @see FreeTextIntent

### getJustification {#getJustification--}
```
public Justification getJustification()
```

Mendapatkan kode yang menentukan bentuk perataan (justifikasi) yang akan digunakan dalam menampilkan teks anotasi.

**Returns:**
nilai int @see Justification

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Sudut rotasi anotasi.

**Returns:**
elemen Rotation @see Rotation

### getStartingStyle {#getStartingStyle--}
```
public final LineEnding getStartingStyle()
```

Mendapatkan atau mengatur gaya akhir garis untuk titik akhir garis. Properti ini sudah usang, silakan gunakan EndingStyle.

**Returns:**
elemen LineEnding

### getTextRectangle {#getTextRectangle--}
```
public final Rectangle getTextRectangle()
```

Persegi panjang yang menggambarkan perbedaan numerik antara dua persegi panjang: entri Rect dari anotasi dan sebuah persegi panjang yang berada di dalam persegi panjang tersebut. Persegi panjang dalam adalah tempat teks anotasi harus ditampilkan.

**Returns:**
Instansi Rectangle

### getTextStyle {#getTextStyle--}
```
public TextStyle getTextStyle()
```

Mendapatkan atau mengatur gaya teks dalam tampilan. Ketika gaya teks diubah, tampilan teks diperbarui.

**Returns:**
nilai TextStyle

### isValidXml {#isValidXml-java.lang.String-}


### setCallout {#setCallout-com.aspose.pdf.Point:A-}
Array titik yang menentukan garis panggilan.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Mengatur string tampilan default yang akan digunakan dalam memformat teks.

### setDefaultStyle {#setDefaultStyle-java.lang.String-}
Mengatur string gaya default.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Mengatur gaya akhir garis untuk titik akhir garis.

### setIntent {#setIntent-com.aspose.pdf.FreeTextIntent-}
Mengatur maksud anotasi teks bebas.

### setJustification {#setJustification-com.aspose.pdf.Justification-}
Mengatur kode yang menentukan bentuk perataan (justifikasi) yang akan digunakan dalam menampilkan teks anotasi.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Sudut rotasi anotasi.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Mendapatkan atau mengatur gaya akhir garis untuk titik akhir garis. Properti ini sudah usang, silakan gunakan EndingStyle.

### setTextRectangle {#setTextRectangle-com.aspose.pdf.Rectangle-}
Persegi panjang yang menggambarkan perbedaan numerik antara dua persegi panjang: entri Rect dari anotasi dan sebuah persegi panjang yang berada di dalam persegi panjang tersebut. Persegi panjang dalam adalah tempat teks anotasi harus ditampilkan.

### setTextStyle {#setTextStyle-int-int-int-}
```
public final void setTextStyle(int fromInd, int toInd, int textStyles)
```

Mengatur pemformatan yang ditentukan oleh parameter textStyle untuk fragmen teks dari indeks fromInd hingga indeks toInd.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fromInd |  | Indeks mulai dari fragmen teks (dari 0). |
| toInd |  | Indeks akhir dari fragmen teks (menghitung dari 0, tidak termasuk ini). |
| textStyles |  | Gaya yang diterapkan untuk fragmen teks. |

### setTextStyle {#setTextStyle-int-java.lang.String-double-java.awt.Color-}
Mengatur pemformatan yang ditentukan oleh parameter textStyle untuk semua teks anotasi.

### setTextStyle {#setTextStyle-com.aspose.pdf.TextStyle-}
Mengatur gaya teks dalam tampilan. ketika gaya teks diubah, tampilan teks diperbarui.

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Memperbarui Appearance, setelah teks diubah/dipindahkan.
