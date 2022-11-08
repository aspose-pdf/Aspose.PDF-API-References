---
title: PrintPageSettings
second_title: Aspose.PDF for Java API Reference
description: Specifies settings that apply to a single printed page.
type: docs
weight: 15
url: /java/com.aspose.pdf.printing/printpagesettings/
---
**Inheritance:**
java.lang.Object
```
public class PrintPageSettings
```

Specifies settings that apply to a single, printed page.
## Constructors

| Constructor | Description |
| --- | --- |
| [PrintPageSettings()](#PrintPageSettings--) | Initializes a new instance of the PageSettings class using the default printer. |
| [PrintPageSettings(PdfPrinterSettings value)](#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Initializes a new instance of the PageSettings class using a specified printer. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Gets the size of the page, taking into account the page orientation specified by the Landscape property. |
| [getClass()](#getClass--) |  |
| [getHardMarginX()](#getHardMarginX--) | Gets the x-coordinate, in hundredths of an inch, of the hard margin at the left of the page. |
| [getHardMarginY()](#getHardMarginY--) | Gets the y-coordinate, in hundredths of an inch, of the hard margin at the top of the page. |
| [getMargins()](#getMargins--) | Gets the margins for this page. |
| [getPageSettings()](#getPageSettings--) | Gets Page Settings |
| [getPaperSize()](#getPaperSize--) | Gets the paper size for the page. |
| [getPaperSource()](#getPaperSource--) | Gets the page's paper source; for example, the printer's upper tray. |
| [getPrintableArea()](#getPrintableArea--) | Gets the bounds of the printable area of the page for the printer. |
| [getPrinterResolution()](#getPrinterResolution--) | Gets the printer resolution for the page. |
| [getPrinterSettings()](#getPrinterSettings--) | Gets the printer settings associated with the page. |
| [hashCode()](#hashCode--) |  |
| [isColor()](#isColor--) | Gets or sets a value indicating whether the page should be printed in color. |
| [isLandscape()](#isLandscape--) | Gets or sets a value indicating whether the page is printed in landscape or portrait orientation. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColor(boolean value)](#setColor-boolean-) | Gets or sets a value indicating whether the page should be printed in color. |
| [setLandscape(boolean value)](#setLandscape-boolean-) | Gets or sets a value indicating whether the page is printed in landscape or portrait orientation. |
| [setMargins(PrinterMargins value)](#setMargins-com.aspose.pdf.printing.PrinterMargins-) | Sets the margins for this page. |
| [setPaperSize(PrintPaperSize value)](#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Sets the paper size for the page. |
| [setPaperSource(PrintPaperSource value)](#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-) | Sets the page's paper source; for example, the printer's upper tray. |
| [setPrinterResolution(PdfPrinterResolution value)](#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-) | Sets the printer resolution for the page. |
| [setPrinterSettings(PdfPrinterSettings value)](#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Sets the printer settings associated with the page. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PrintPageSettings() {#PrintPageSettings--}
```
public PrintPageSettings()
```


Initializes a new instance of the PageSettings class using the default printer.

### PrintPageSettings(PdfPrinterSettings value) {#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public PrintPageSettings(PdfPrinterSettings value)
```


Initializes a new instance of the PageSettings class using a specified printer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | PdfPrinterSettings object |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Gets the size of the page, taking into account the page orientation specified by the Landscape property.

**Returns:**
[Rectangle](../../java.awt/rectangle) - Rectangle object
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHardMarginX() {#getHardMarginX--}
```
public float getHardMarginX()
```


Gets the x-coordinate, in hundredths of an inch, of the hard margin at the left of the page.

**Returns:**
float - float value
### getHardMarginY() {#getHardMarginY--}
```
public float getHardMarginY()
```


Gets the y-coordinate, in hundredths of an inch, of the hard margin at the top of the page.

**Returns:**
float - float value
### getMargins() {#getMargins--}
```
public PrinterMargins getMargins()
```


Gets the margins for this page.

**Returns:**
[PrinterMargins](../../com.aspose.pdf.printing/printermargins) - PrinterMargins object
### getPageSettings() {#getPageSettings--}
```
public System.Drawing.Printing.PageSettings getPageSettings()
```


Gets Page Settings

**Returns:**
com.aspose.ms.System.Drawing.Printing.PageSettings - PageSettings object
### getPaperSize() {#getPaperSize--}
```
public PrintPaperSize getPaperSize()
```


Gets the paper size for the page.

**Returns:**
[PrintPaperSize](../../com.aspose.pdf.printing/printpapersize) - PrintPaperSize object
### getPaperSource() {#getPaperSource--}
```
public PrintPaperSource getPaperSource()
```


Gets the page's paper source; for example, the printer's upper tray.

**Returns:**
[PrintPaperSource](../../com.aspose.pdf.printing/printpapersource) - PrintPaperSource object
### getPrintableArea() {#getPrintableArea--}
```
public Rectangle getPrintableArea()
```


Gets the bounds of the printable area of the page for the printer.

**Returns:**
[Rectangle](../../java.awt/rectangle) - Rectangle object
### getPrinterResolution() {#getPrinterResolution--}
```
public PdfPrinterResolution getPrinterResolution()
```


Gets the printer resolution for the page.

**Returns:**
[PdfPrinterResolution](../../com.aspose.pdf.printing/pdfprinterresolution) - PdfPrinterResolution object
### getPrinterSettings() {#getPrinterSettings--}
```
public PdfPrinterSettings getPrinterSettings()
```


Gets the printer settings associated with the page.

**Returns:**
[PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) - PdfPrinterSettings object
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColor() {#isColor--}
```
public boolean isColor()
```


Gets or sets a value indicating whether the page should be printed in color.

**Returns:**
boolean - boolean value
### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


Gets or sets a value indicating whether the page is printed in landscape or portrait orientation.

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Gets or sets a value indicating whether the page should be printed in color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setLandscape(boolean value) {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```


Gets or sets a value indicating whether the page is printed in landscape or portrait orientation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setMargins(PrinterMargins value) {#setMargins-com.aspose.pdf.printing.PrinterMargins-}
```
public void setMargins(PrinterMargins value)
```


Sets the margins for this page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PrinterMargins](../../com.aspose.pdf.printing/printermargins) | PrinterMargins object |

### setPaperSize(PrintPaperSize value) {#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-}
```
public void setPaperSize(PrintPaperSize value)
```


Sets the paper size for the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PrintPaperSize](../../com.aspose.pdf.printing/printpapersize) | PrintPaperSize object |

### setPaperSource(PrintPaperSource value) {#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-}
```
public void setPaperSource(PrintPaperSource value)
```


Sets the page's paper source; for example, the printer's upper tray.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PrintPaperSource](../../com.aspose.pdf.printing/printpapersource) | PrintPaperSource object |

### setPrinterResolution(PdfPrinterResolution value) {#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-}
```
public void setPrinterResolution(PdfPrinterResolution value)
```


Sets the printer resolution for the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfPrinterResolution](../../com.aspose.pdf.printing/pdfprinterresolution) | PdfPrinterResolution object |

### setPrinterSettings(PdfPrinterSettings value) {#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
```
public void setPrinterSettings(PdfPrinterSettings value)
```


Sets the printer settings associated with the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) | PdfPrinterSettings object |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

