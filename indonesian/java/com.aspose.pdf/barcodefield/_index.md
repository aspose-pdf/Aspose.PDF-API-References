---
title: "BarcodeField"
linktitle: "BarcodeField"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili bidang barcode."
type: docs
weight: 250
url: /id/java/com.aspose.pdf/barcodefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.TextBoxField, com.aspose.pdf.BarcodeField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class BarcodeField extends TextBoxField
```

Kelas yang mewakili bidang barcode.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BarcodeField](#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Menginisialisasi instance baru dari kelas {@code BarcodeField}. |
| [BarcodeField](#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Menginisialisasi instance baru dari kelas {@code BarcodeField}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCaption](#getCaption--) | Mendapatkan keterangan dari objek barcode. |
| [getECC](#getECC--) | Mendapatkan nilai integer yang mewakili koefisien koreksi kesalahan. Untuk PDF417, harus antara 0 hingga 8. Untuk QRCode, harus antara 0 hingga 3 (0 untuk 'L', 1 untuk 'M', 2 untuk 'Q', dan 3 untuk 'H'). |
| [getResolution](#getResolution--) | Mendapatkan resolusi, dalam dot-per-inch (dpi), pada mana objek barcode dirender. |
| [getSymbology](#getSymbology--) | Menentukan teknologi barcode atau glyph mana yang akan digunakan pada anotasi ini, lihat {@code Symbology} untuk detail. |
| [getXSymHeight](#getXSymHeight--) | Mendapatkan jarak vertikal antara dua modul barcode, diukur dalam piksel. Rasio XSymHeight/XSymWidth harus berupa nilai integer. Untuk PDF417, rentang rasio yang dapat diterima adalah antara 1 hingga 4. Untuk QRCode dan DataMatrix, rasio ini selalu 1. |
| [getXSymWidth](#getXSymWidth--) | Mendapatkan jarak horizontal, dalam piksel, antara dua modul barcode. |

### BarcodeField {#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Menginisialisasi instance baru dari kelas {@code BarcodeField}.

### BarcodeField {#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Menginisialisasi instance baru dari kelas {@code BarcodeField}.

### getCaption {#getCaption--}
```
public String getCaption()
```

Mendapatkan keterangan dari objek barcode.

**Returns:**
nilai String

### getECC {#getECC--}
```
public int getECC()
```

Mendapatkan nilai integer yang mewakili koefisien koreksi kesalahan. Untuk PDF417, harus antara 0 hingga 8. Untuk QRCode, harus antara 0 hingga 3 (0 untuk 'L', 1 untuk 'M', 2 untuk 'Q', dan 3 untuk 'H').

**Returns:**
nilai int

### getResolution {#getResolution--}
```
public int getResolution()
```

Mendapatkan resolusi, dalam dot-per-inch (dpi), pada mana objek barcode dirender.

**Returns:**
nilai int

### getSymbology {#getSymbology--}
```
public int getSymbology()
```

Menentukan teknologi barcode atau glyph mana yang akan digunakan pada anotasi ini, lihat {@code Symbology} untuk detail.

**Returns:**
Elemen Symbology @see Symbology

### getXSymHeight {#getXSymHeight--}
```
public int getXSymHeight()
```

Mendapatkan jarak vertikal antara dua modul barcode, diukur dalam piksel. Rasio XSymHeight/XSymWidth harus berupa nilai integer. Untuk PDF417, rentang rasio yang dapat diterima adalah antara 1 hingga 4. Untuk QRCode dan DataMatrix, rasio ini selalu 1.

**Returns:**
nilai int

### getXSymWidth {#getXSymWidth--}
```
public int getXSymWidth()
```

Mendapatkan jarak horizontal, dalam piksel, antara dua modul barcode.

**Returns:**
nilai int
