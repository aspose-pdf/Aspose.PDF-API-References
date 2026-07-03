---
title: PrintPageSettings
second_title: Aspose.PDF for Java API Reference
description: Specifies settings that apply to a single, printed page.
type: docs
weight: 90
url: /java/com.aspose.pdf.printing/printpagesettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPageSettings

```
public class PrintPageSettings extends Object
```

Specifies settings that apply to a single, printed page.

## Constructors

| Constructor | Description |
| --- | --- |
| [PrintPageSettings](#PrintPageSettings--) | Initializes a new instance of the PageSettings class using the default printer. |
| [PrintPageSettings](#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Initializes a new instance of the PageSettings class using the default printer. |

## Methods

| Method | Description |
| --- | --- |
| [getBounds](#getBounds--) | Gets the size of the page, taking into account the page orientation specified by the Landscape property. |
| [getHardMarginX](#getHardMarginX--) | Gets the x-coordinate, in hundredths of an inch, of the hard margin at the left of the page. |
| [getHardMarginY](#getHardMarginY--) | Gets the y-coordinate, in hundredths of an inch, of the hard margin at the top of the page. |
| [getMargins](#getMargins--) | Gets the margins for this page. |
| [getPageSettings](#getPageSettings--) | Gets Page Settings |
| [getPaperSize](#getPaperSize--) | Gets the paper size for the page. |
| [getPaperSource](#getPaperSource--) | Gets the page's paper source; for example, the printer's upper tray. |
| [getPrintableArea](#getPrintableArea--) | Gets the bounds of the printable area of the page for the printer. |
| [getPrinterResolution](#getPrinterResolution--) | Gets the printer resolution for the page. |
| [getPrinterSettings](#getPrinterSettings--) | Gets the printer settings associated with the page. |
| [isColor](#isColor--) | Gets or sets a value indicating whether the page should be printed in color. |
| [isLandscape](#isLandscape--) | Gets or sets a value indicating whether the page is printed in landscape or portrait orientation. |
| [setColor](#setColor-boolean-) | Gets or sets a value indicating whether the page should be printed in color. |
| [setLandscape](#setLandscape-boolean-) | Gets or sets a value indicating whether the page is printed in landscape or portrait orientation. |
| [setMargins](#setMargins-com.aspose.pdf.printing.PrinterMargins-) | Sets the margins for this page. |
| [setPaperSize](#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Sets the paper size for the page. |
| [setPaperSource](#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-) | Sets the page's paper source; for example, the printer's upper tray. |
| [setPrinterResolution](#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-) | Sets the printer resolution for the page. |
| [setPrinterSettings](#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Sets the printer settings associated with the page. |

### PrintPageSettings {#PrintPageSettings--}
```
public PrintPageSettings()
```

Initializes a new instance of the PageSettings class using the default printer.

### PrintPageSettings {#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Initializes a new instance of the PageSettings class using the default printer.

### getBounds {#getBounds--}
```
public Rectangle getBounds()
```

Gets the size of the page, taking into account the page orientation specified by the Landscape property.

**Returns:**
Rectangle object

### getHardMarginX {#getHardMarginX--}
```
public float getHardMarginX()
```

Gets the x-coordinate, in hundredths of an inch, of the hard margin at the left of the page.

**Returns:**
float value

### getHardMarginY {#getHardMarginY--}
```
public float getHardMarginY()
```

Gets the y-coordinate, in hundredths of an inch, of the hard margin at the top of the page.

**Returns:**
float value

### getMargins {#getMargins--}
```
public PrinterMargins getMargins()
```

Gets the margins for this page.

**Returns:**
PrinterMargins object

### getPageSettings {#getPageSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PageSettings getPageSettings()
```

Gets Page Settings

**Returns:**
PageSettings object

### getPaperSize {#getPaperSize--}
```
public PrintPaperSize getPaperSize()
```

Gets the paper size for the page.

**Returns:**
PrintPaperSize object

### getPaperSource {#getPaperSource--}
```
public PrintPaperSource getPaperSource()
```

Gets the page's paper source; for example, the printer's upper tray.

**Returns:**
PrintPaperSource object

### getPrintableArea {#getPrintableArea--}
```
public Rectangle getPrintableArea()
```

Gets the bounds of the printable area of the page for the printer.

**Returns:**
Rectangle object

### getPrinterResolution {#getPrinterResolution--}
```
public PdfPrinterResolution getPrinterResolution()
```

Gets the printer resolution for the page.

**Returns:**
PdfPrinterResolution object

### getPrinterSettings {#getPrinterSettings--}
```
public PdfPrinterSettings getPrinterSettings()
```

Gets the printer settings associated with the page.

**Returns:**
PdfPrinterSettings object

### isColor {#isColor--}
```
public boolean isColor()
```

Gets or sets a value indicating whether the page should be printed in color.

**Returns:**
boolean value

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

Gets or sets a value indicating whether the page is printed in landscape or portrait orientation.

**Returns:**
boolean value

### setColor {#setColor-boolean-}
```
public void setColor(boolean value)
```

Gets or sets a value indicating whether the page should be printed in color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

Gets or sets a value indicating whether the page is printed in landscape or portrait orientation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMargins {#setMargins-com.aspose.pdf.printing.PrinterMargins-}
Sets the margins for this page.

### setPaperSize {#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Sets the paper size for the page.

### setPaperSource {#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-}
Sets the page's paper source; for example, the printer's upper tray.

### setPrinterResolution {#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-}
Sets the printer resolution for the page.

### setPrinterSettings {#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Sets the printer settings associated with the page.
