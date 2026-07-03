---
title: BarcodeField
second_title: Aspose.PDF for Java API Reference
description: Class represents barcode field.
type: docs
weight: 250
url: /java/com.aspose.pdf/barcodefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.TextBoxField, com.aspose.pdf.BarcodeField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class BarcodeField extends TextBoxField
```

Class represents barcode field.

## Constructors

| Constructor | Description |
| --- | --- |
| [BarcodeField](#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Initializes new instance of the {@code BarcodeField} class. |
| [BarcodeField](#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initializes new instance of the {@code BarcodeField} class. |

## Methods

| Method | Description |
| --- | --- |
| [getCaption](#getCaption--) | Gets the caption of the barcode object. |
| [getECC](#getECC--) | Gets an integer value representing the error correction coefficient. For PDF417, shall be from 0 to 8. For QRCode, shall be from 0 to 3 (0 for 'L', 1 for 'M', 2 for 'Q', and 3 for 'H'). |
| [getResolution](#getResolution--) | Gets the resolution, in dots-per-inch (dpi), at which the barcode object is rendered. |
| [getSymbology](#getSymbology--) | Specifies which barcode or glyph technology is to be used on this annotation, see {@code Symbology} for details. |
| [getXSymHeight](#getXSymHeight--) | Gets the the vertical distance between two barcode modules, measured in pixels. The ratio XSymHeight/XSymWidth shall be an integer value. For PDF417, the acceptable ratio range is from 1 to 4. For QRCode and DataMatrix, this ratio shall always be 1 |
| [getXSymWidth](#getXSymWidth--) | Gets The horizontal distance, in pixels, between two barcode modules. |

### BarcodeField {#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Initializes new instance of the {@code BarcodeField} class.

### BarcodeField {#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Initializes new instance of the {@code BarcodeField} class.

### getCaption {#getCaption--}
```
public String getCaption()
```

Gets the caption of the barcode object.

**Returns:**
String value

### getECC {#getECC--}
```
public int getECC()
```

Gets an integer value representing the error correction coefficient. For PDF417, shall be from 0 to 8. For QRCode, shall be from 0 to 3 (0 for 'L', 1 for 'M', 2 for 'Q', and 3 for 'H').

**Returns:**
int value

### getResolution {#getResolution--}
```
public int getResolution()
```

Gets the resolution, in dots-per-inch (dpi), at which the barcode object is rendered.

**Returns:**
int value

### getSymbology {#getSymbology--}
```
public int getSymbology()
```

Specifies which barcode or glyph technology is to be used on this annotation, see {@code Symbology} for details.

**Returns:**
Symbology element @see Symbology

### getXSymHeight {#getXSymHeight--}
```
public int getXSymHeight()
```

Gets the the vertical distance between two barcode modules, measured in pixels. The ratio XSymHeight/XSymWidth shall be an integer value. For PDF417, the acceptable ratio range is from 1 to 4. For QRCode and DataMatrix, this ratio shall always be 1

**Returns:**
int value

### getXSymWidth {#getXSymWidth--}
```
public int getXSymWidth()
```

Gets The horizontal distance, in pixels, between two barcode modules.

**Returns:**
int value
