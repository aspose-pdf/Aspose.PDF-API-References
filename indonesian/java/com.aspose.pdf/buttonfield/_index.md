---
title: "ButtonField"
linktitle: "ButtonField"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas mewakili bidang tombol dorong."
type: docs
weight: 440
url: /id/java/com.aspose.pdf/buttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Field, com.aspose.pdf.ButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class ButtonField extends Field
```

Kelas mewakili bidang tombol dorong.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ButtonField](#ButtonField--) | Konstruktor Button field untuk Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Konstruktor Button field untuk Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Konstruktor Button field untuk Generator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Menambahkan gambar ke dalam sumber daya bidang dan menggambarnya. |
| [addImage](#addImage-java.awt.image.BufferedImage-boolean-) | Menambahkan gambar ke sumber daya bidang dan menggambarnya. |
| [getAlternateCaption](#getAlternateCaption--) | Mendapatkan caption alternatif tombol yang akan ditampilkan ketika tombol mouse ditekan di dalam area aktifnya. |
| [getAlternateIcon](#getAlternateIcon--) | Mendapatkan ikon alternatif yang akan ditampilkan ketika tombol mouse ditekan di dalam area aktifnya. |
| [getIconFit](#getIconFit--) | Mendapatkan objek penyesuaian ikon yang menentukan bagaimana ikon anotasi widget akan ditampilkan dalam persegi panjang anotasinya. |
| [getICPosition](#getICPosition--) | Mendapatkan posisi caption ikon. |
| [getNormalCaption](#getNormalCaption--) | Mendapatkan caption normal. |
| [getNormalIcon](#getNormalIcon--) | Mendapatkan ikon normal tombol yang akan ditampilkan ketika tidak berinteraksi dengan pengguna. |
| [getRolloverCaption](#getRolloverCaption--) | Mendapatkan caption rollover tombol yang akan ditampilkan ketika pengguna menggerakkan kursor ke area aktifnya tanpa menekan tombol mouse. |
| [getRolloverIcon](#getRolloverIcon--) | Mendapatkan ikon rollover tombol yang akan ditampilkan ketika pengguna menggerakkan kursor ke area aktifnya tanpa menekan tombol mouse. |
| [setAlternateCaption](#setAlternateCaption-java.lang.String-) | Mengatur caption alternatif tombol yang akan ditampilkan ketika tombol mouse ditekan di dalam area aktifnya. |
| [setAlternateIcon](#setAlternateIcon-com.aspose.pdf.XForm-) | Mengatur ikon alternatif yang akan ditampilkan ketika tombol mouse ditekan di dalam area aktifnya. |
| [setICPosition](#setICPosition-com.aspose.pdf.IconCaptionPosition-) | Mengatur posisi caption ikon. |
| [setNormalCaption](#setNormalCaption-java.lang.String-) | Mengatur caption normal. |
| [setNormalIcon](#setNormalIcon-com.aspose.pdf.XForm-) | Mengatur ikon normal tombol yang akan ditampilkan ketika tidak berinteraksi dengan pengguna. |
| [setRolloverCaption](#setRolloverCaption-java.lang.String-) | Mengatur caption rollover tombol yang akan ditampilkan ketika pengguna menggerakkan kursor ke area aktifnya tanpa menekan tombol mouse. |
| [setRolloverIcon](#setRolloverIcon-com.aspose.pdf.XForm-) | Mengatur ikon rollover tombol yang akan ditampilkan ketika pengguna menggerakkan kursor ke area aktifnya tanpa menekan tombol mouse. |

### ButtonField {#ButtonField--}
```
public ButtonField()
```

Konstruktor Button field untuk Generator.

### ButtonField {#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Konstruktor Button field untuk Generator.

### ButtonField {#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Konstruktor Button field untuk Generator.

### addImage {#addImage-java.awt.image.BufferedImage-}
Menambahkan gambar ke dalam sumber daya bidang dan menggambarnya.

### addImage {#addImage-java.awt.image.BufferedImage-boolean-}
Menambahkan gambar ke sumber daya bidang dan menggambarnya.

### getAlternateCaption {#getAlternateCaption--}
```
public String getAlternateCaption()
```

Mendapatkan caption alternatif tombol yang akan ditampilkan ketika tombol mouse ditekan di dalam area aktifnya.

**Returns:**
nilai String

### getAlternateIcon {#getAlternateIcon--}
```
public XForm getAlternateIcon()
```

Mendapatkan ikon alternatif yang akan ditampilkan ketika tombol mouse ditekan di dalam area aktifnya.

**Returns:**
objek XForm

### getIconFit {#getIconFit--}
```
public IconFit getIconFit()
```

Mendapatkan objek penyesuaian ikon yang menentukan bagaimana ikon anotasi widget akan ditampilkan dalam persegi panjang anotasinya.

**Returns:**
objek IconFit

### getICPosition {#getICPosition--}
```
public IconCaptionPosition getICPosition()
```

Mendapatkan posisi caption ikon.

**Returns:**
posisi keterangan ikon. @see IconCaptionPosition

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Mendapatkan caption normal.

**Returns:**
nilai String

### getNormalIcon {#getNormalIcon--}
```
public XForm getNormalIcon()
```

Mendapatkan ikon normal tombol yang akan ditampilkan ketika tidak berinteraksi dengan pengguna.

**Returns:**
objek XForm

### getRolloverCaption {#getRolloverCaption--}
```
public String getRolloverCaption()
```

Mendapatkan caption rollover tombol yang akan ditampilkan ketika pengguna menggerakkan kursor ke area aktifnya tanpa menekan tombol mouse.

**Returns:**
nilai String

### getRolloverIcon {#getRolloverIcon--}
```
public XForm getRolloverIcon()
```

Mendapatkan ikon rollover tombol yang akan ditampilkan ketika pengguna menggerakkan kursor ke area aktifnya tanpa menekan tombol mouse.

**Returns:**
objek XForm

### setAlternateCaption {#setAlternateCaption-java.lang.String-}
Mengatur caption alternatif tombol yang akan ditampilkan ketika tombol mouse ditekan di dalam area aktifnya.

### setAlternateIcon {#setAlternateIcon-com.aspose.pdf.XForm-}
Mengatur ikon alternatif yang akan ditampilkan ketika tombol mouse ditekan di dalam area aktifnya.

### setICPosition {#setICPosition-com.aspose.pdf.IconCaptionPosition-}
Mengatur posisi caption ikon.

### setNormalCaption {#setNormalCaption-java.lang.String-}
Mengatur caption normal.

### setNormalIcon {#setNormalIcon-com.aspose.pdf.XForm-}
Mengatur ikon normal tombol yang akan ditampilkan ketika tidak berinteraksi dengan pengguna.

### setRolloverCaption {#setRolloverCaption-java.lang.String-}
Mengatur caption rollover tombol yang akan ditampilkan ketika pengguna menggerakkan kursor ke area aktifnya tanpa menekan tombol mouse.

### setRolloverIcon {#setRolloverIcon-com.aspose.pdf.XForm-}
Mengatur ikon rollover tombol yang akan ditampilkan ketika pengguna menggerakkan kursor ke area aktifnya tanpa menekan tombol mouse.
