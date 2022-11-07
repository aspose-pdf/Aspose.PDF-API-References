---
title: BarcodeField
second_title: Aspose.PDF for Java API Reference
description: Class represents barcode field.
type: docs
weight: 30
url: /java/com.aspose.pdf/barcodefield/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation), [com.aspose.pdf.Field](../../com.aspose.pdf/field), [com.aspose.pdf.TextBoxField](../../com.aspose.pdf/textboxfield)
```
public final class BarcodeField extends TextBoxField
```

Class represents barcode field.
## Constructors

| Constructor | Description |
| --- | --- |
| [BarcodeField(Page page, Rectangle rect)](#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Initializes new instance of the  BarcodeField  class. |
## Methods

| Method | Description |
| --- | --- |
| [getResolution()](#getResolution--) | Gets the resolution, in dots-per-inch (dpi), at which the barcode object is rendered. |
| [getCaption()](#getCaption--) | Gets the caption of the barcode object. |
| [getSymbology()](#getSymbology--) | Specifies which barcode or glyph technology is to be used on this annotation, see  Symbology  for details. |
| [getXSymWidth()](#getXSymWidth--) | Gets The horizontal distance, in pixels, between two barcode modules. |
| [getXSymHeight()](#getXSymHeight--) | Gets the the vertical distance between two barcode modules, measured in pixels. |
| [getECC()](#getECC--) | Gets an integer value representing the error correction coefficient. |
### BarcodeField(Page page, Rectangle rect) {#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
```
public BarcodeField(Page page, Rectangle rect)
```


Initializes new instance of the  BarcodeField  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page where to place new barcode. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Barcode sizes given in rectangle. |

### getResolution() {#getResolution--}
```
public int getResolution()
```


Gets the resolution, in dots-per-inch (dpi), at which the barcode object is rendered.

**Returns:**
int - int value
### getCaption() {#getCaption--}
```
public String getCaption()
```


Gets the caption of the barcode object.

**Returns:**
java.lang.String - String value
### getSymbology() {#getSymbology--}
```
public int getSymbology()
```


Specifies which barcode or glyph technology is to be used on this annotation, see  Symbology  for details.

**Returns:**
int - Symbology element
### getXSymWidth() {#getXSymWidth--}
```
public int getXSymWidth()
```


Gets The horizontal distance, in pixels, between two barcode modules.

**Returns:**
int - int value
### getXSymHeight() {#getXSymHeight--}
```
public int getXSymHeight()
```


Gets the the vertical distance between two barcode modules, measured in pixels. The ratio XSymHeight/XSymWidth shall be an integer value. For PDF417, the acceptable ratio range is from 1 to 4. For QRCode and DataMatrix, this ratio shall always be 1

**Returns:**
int - int value
### getECC() {#getECC--}
```
public int getECC()
```


Gets an integer value representing the error correction coefficient. For PDF417, shall be from 0 to 8. For QRCode, shall be from 0 to 3 (0 for \\ufffdL\\ufffd, 1 for \\ufffdM\\ufffd, 2 for \\ufffdQ\\ufffd, and 3 for \\ufffdH\\ufffd).

**Returns:**
int - int value
