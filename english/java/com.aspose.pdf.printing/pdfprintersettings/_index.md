---
title: PdfPrinterSettings
second_title: Aspose.PDF for Java API Reference
description: Specifies information about how a document is printed including the printer that prints it.
type: docs
weight: 14
url: /java/com.aspose.pdf.printing/pdfprintersettings/
---
**Inheritance:**
java.lang.Object
```
public class PdfPrinterSettings
```

Specifies information about how a document is printed, including the printer that prints it.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfPrinterSettings()](#PdfPrinterSettings--) | Initializes a new instance of the PrinterSettings class. |
## Methods

| Method | Description |
| --- | --- |
| [canDuplex()](#canDuplex--) | Gets a value indicating whether the printer supports double-sided printing. |
| [createMeasurementGraphics()](#createMeasurementGraphics--) | Get Graphics2D object |
| [createMeasurementGraphics(boolean value)](#createMeasurementGraphics-boolean-) | Get Graphics2D object |
| [createMeasurementGraphics(PrintPageSettings value)](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-) | Get Graphics2D object |
| [createMeasurementGraphics(PrintPageSettings pageSettings, boolean honorOriginAtMargins)](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-) | Get Graphics2D object |
| [deepClone()](#deepClone--) | Get clonned object |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCopies()](#getCopies--) | Gets the number of copies of the document to print. |
| [getDefaultPageSettings()](#getDefaultPageSettings--) | Gets the default page settings for this printer. |
| [getDuplex()](#getDuplex--) | Gets or sets the printer setting for double-sided printing. |
| [getFromPage()](#getFromPage--) | Gets or sets the page number of the first page to print. |
| [getInstalledPrinters()](#getInstalledPrinters--) | Gets the names of all printers installed on the computer. |
| [getLandscapeAngle()](#getLandscapeAngle--) | Gets the angle, in degrees, that the portrait orientation is rotated to produce the landscape orientation. |
| [getMaximumCopies()](#getMaximumCopies--) | Gets the maximum number of copies that the printer enables the user to print at a time. |
| [getMaximumPage()](#getMaximumPage--) | Gets or sets the maximum FromPage or ToPage that can be selected in a PrintDialog. |
| [getMinimumPage()](#getMinimumPage--) | Gets or sets the minimum FromPage or ToPage that can be selected in a PrintDialog. |
| [getPaperSizes()](#getPaperSizes--) | Gets the paper sizes that are supported by this printer. |
| [getPaperSources()](#getPaperSources--) | Gets the paper source trays that are available on the printer. |
| [getPrintFileName()](#getPrintFileName--) | Gets or sets the file name, when printing to a file. |
| [getPrintRange()](#getPrintRange--) | Gets or sets the page numbers that the user has specified to be printed. |
| [getPrinterName()](#getPrinterName--) | Gets or sets the name of the printer to use. |
| [getPrinterResolutions()](#getPrinterResolutions--) | Gets all the resolutions that are supported by this printer. |
| [getPrinterSettings()](#getPrinterSettings--) | Return PrinterSettings object |
| [getSelectedPages()](#getSelectedPages--) | Gets the number of selected pages to print. |
| [getToPage()](#getToPage--) | Gets or sets the number of the last page to print. |
| [hashCode()](#hashCode--) |  |
| [isCollate()](#isCollate--) | Gets or sets a value indicating whether the printed document is collated. |
| [isDefaultPrinter()](#isDefaultPrinter--) | Gets a value indicating whether the PrinterName property designates the default printer, except when the user explicitly sets PrinterName. |
| [isDirectPrintingSupported(ImageType format)](#isDirectPrintingSupported-com.aspose.pdf.ImageType-) | Gets a value indicating whether the printer is Supported DirectPrinting |
| [isDirectPrintingSupported(String filename)](#isDirectPrintingSupported-java.lang.String-) | Gets a value indicating whether the printer is Supported DirectPrinting |
| [isPlotter()](#isPlotter--) | Gets a value indicating whether the printer is a plotter. |
| [isPrintToFile()](#isPrintToFile--) | Gets a value indicating whether the printing output is sent to a file instead of a port. |
| [isSupportsColor()](#isSupportsColor--) | Gets a value indicating whether this printer supports color printing. |
| [isValid()](#isValid--) | Gets a value indicating whether the PrinterName property designates a valid printer. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCollate(boolean value)](#setCollate-boolean-) | Gets or sets a value indicating whether the printed document is collated. |
| [setCopies(short value)](#setCopies-short-) | Sets the number of copies of the document to print. |
| [setDuplex(int value)](#setDuplex-int-) | Gets or sets the printer setting for double-sided printing. |
| [setFromPage(int value)](#setFromPage-int-) | Gets or sets the page number of the first page to print. |
| [setMaximumPage(int value)](#setMaximumPage-int-) | Gets or sets the maximum FromPage or ToPage that can be selected in a PrintDialog. |
| [setMinimumPage(int value)](#setMinimumPage-int-) | Gets or sets the minimum FromPage or ToPage that can be selected in a PrintDialog. |
| [setPrintFileName(String value)](#setPrintFileName-java.lang.String-) | Sets the filename to print. |
| [setPrintRange(int value)](#setPrintRange-int-) | Sets the page numbers that the user has specified to be printed. |
| [setPrintToFile(boolean value)](#setPrintToFile-boolean-) | Sets a value indicating whether the printing output is sent to a file instead of a port. |
| [setPrinterName(String value)](#setPrinterName-java.lang.String-) | Sets the name of the printer to use. |
| [setSelectedPages(int[] pagesList)](#setSelectedPages-int---) | Sets the number of selected pages to print. |
| [setToPage(int value)](#setToPage-int-) | Sets the number of the last page to print. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfPrinterSettings() {#PdfPrinterSettings--}
```
public PdfPrinterSettings()
```


Initializes a new instance of the PrinterSettings class.

### canDuplex() {#canDuplex--}
```
public boolean canDuplex()
```


Gets a value indicating whether the printer supports double-sided printing.

**Returns:**
boolean - boolean value
### createMeasurementGraphics() {#createMeasurementGraphics--}
```
public Graphics2D createMeasurementGraphics()
```


Get Graphics2D object

**Returns:**
java.awt.Graphics2D - Graphics2D object
### createMeasurementGraphics(boolean value) {#createMeasurementGraphics-boolean-}
```
public Graphics2D createMeasurementGraphics(boolean value)
```


Get Graphics2D object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

**Returns:**
java.awt.Graphics2D - Graphics2D object
### createMeasurementGraphics(PrintPageSettings value) {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-}
```
public Graphics2D createMeasurementGraphics(PrintPageSettings value)
```


Get Graphics2D object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | PrintPageSettings value |

**Returns:**
java.awt.Graphics2D - Graphics2D object
### createMeasurementGraphics(PrintPageSettings pageSettings, boolean honorOriginAtMargins) {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-}
```
public Graphics2D createMeasurementGraphics(PrintPageSettings pageSettings, boolean honorOriginAtMargins)
```


Get Graphics2D object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSettings | [PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) | PrintPageSettings value |
| honorOriginAtMargins | boolean | boolean value |

**Returns:**
java.awt.Graphics2D - Graphics2D object
### deepClone() {#deepClone--}
```
public PdfPrinterSettings deepClone()
```


Get clonned object

**Returns:**
[PdfPrinterSettings](../../com.aspose.pdf.printing/pdfprintersettings) - PdfPrinterSettings object
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCopies() {#getCopies--}
```
public short getCopies()
```


Gets the number of copies of the document to print.

**Returns:**
short - number of copies
### getDefaultPageSettings() {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```


Gets the default page settings for this printer.

**Returns:**
[PrintPageSettings](../../com.aspose.pdf.printing/printpagesettings) - default page settings
### getDuplex() {#getDuplex--}
```
public int getDuplex()
```


Gets or sets the printer setting for double-sided printing.

**Returns:**
int - int value
### getFromPage() {#getFromPage--}
```
public int getFromPage()
```


Gets or sets the page number of the first page to print.

**Returns:**
int - int value
### getInstalledPrinters() {#getInstalledPrinters--}
```
public static ArrayList<String> getInstalledPrinters()
```


Gets the names of all printers installed on the computer.

**Returns:**
java.util.ArrayList<java.lang.String> -  ArrayList  object
### getLandscapeAngle() {#getLandscapeAngle--}
```
public int getLandscapeAngle()
```


Gets the angle, in degrees, that the portrait orientation is rotated to produce the landscape orientation.

**Returns:**
int - int value
### getMaximumCopies() {#getMaximumCopies--}
```
public int getMaximumCopies()
```


Gets the maximum number of copies that the printer enables the user to print at a time.

**Returns:**
int - int value
### getMaximumPage() {#getMaximumPage--}
```
public int getMaximumPage()
```


Gets or sets the maximum FromPage or ToPage that can be selected in a PrintDialog.

**Returns:**
int - int value
### getMinimumPage() {#getMinimumPage--}
```
public int getMinimumPage()
```


Gets or sets the minimum FromPage or ToPage that can be selected in a PrintDialog.

**Returns:**
int - int value
### getPaperSizes() {#getPaperSizes--}
```
public ArrayList<PrintPaperSize> getPaperSizes()
```


Gets the paper sizes that are supported by this printer.

**Returns:**
java.util.ArrayList<com.aspose.pdf.printing.PrintPaperSize> -  ArrayList  object
### getPaperSources() {#getPaperSources--}
```
public ArrayList<PrintPaperSource> getPaperSources()
```


Gets the paper source trays that are available on the printer.

**Returns:**
java.util.ArrayList<com.aspose.pdf.printing.PrintPaperSource> -  ArrayList  object
### getPrintFileName() {#getPrintFileName--}
```
public String getPrintFileName()
```


Gets or sets the file name, when printing to a file.

**Returns:**
java.lang.String - string object
### getPrintRange() {#getPrintRange--}
```
public int getPrintRange()
```


Gets or sets the page numbers that the user has specified to be printed.

**Returns:**
int - int value
### getPrinterName() {#getPrinterName--}
```
public String getPrinterName()
```


Gets or sets the name of the printer to use.

**Returns:**
java.lang.String - string object
### getPrinterResolutions() {#getPrinterResolutions--}
```
public System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection getPrinterResolutions()
```


Gets all the resolutions that are supported by this printer.

**Returns:**
com.aspose.ms.System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection - PrinterResolutionCollection object
### getPrinterSettings() {#getPrinterSettings--}
```
public System.Drawing.Printing.PrinterSettings getPrinterSettings()
```


Return PrinterSettings object

**Returns:**
com.aspose.ms.System.Drawing.Printing.PrinterSettings - PrinterSettings object
### getSelectedPages() {#getSelectedPages--}
```
public int[] getSelectedPages()
```


Gets the number of selected pages to print.

**Returns:**
int[] - pagesList int array
### getToPage() {#getToPage--}
```
public int getToPage()
```


Gets or sets the number of the last page to print.

**Returns:**
int - int value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCollate() {#isCollate--}
```
public boolean isCollate()
```


Gets or sets a value indicating whether the printed document is collated.

**Returns:**
boolean - boolean value
### isDefaultPrinter() {#isDefaultPrinter--}
```
public boolean isDefaultPrinter()
```


Gets a value indicating whether the PrinterName property designates the default printer, except when the user explicitly sets PrinterName.

**Returns:**
boolean - boolean value
### isDirectPrintingSupported(ImageType format) {#isDirectPrintingSupported-com.aspose.pdf.ImageType-}
```
public boolean isDirectPrintingSupported(ImageType format)
```


Gets a value indicating whether the printer is Supported DirectPrinting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | [ImageType](../../com.aspose.pdf/imagetype) | ImageType object |

**Returns:**
boolean - boolean value
### isDirectPrintingSupported(String filename) {#isDirectPrintingSupported-java.lang.String-}
```
public boolean isDirectPrintingSupported(String filename)
```


Gets a value indicating whether the printer is Supported DirectPrinting

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filename | java.lang.String | String object |

**Returns:**
boolean - boolean value
### isPlotter() {#isPlotter--}
```
public boolean isPlotter()
```


Gets a value indicating whether the printer is a plotter.

**Returns:**
boolean - boolean value
### isPrintToFile() {#isPrintToFile--}
```
public boolean isPrintToFile()
```


Gets a value indicating whether the printing output is sent to a file instead of a port.

**Returns:**
boolean - boolean value
### isSupportsColor() {#isSupportsColor--}
```
public boolean isSupportsColor()
```


Gets a value indicating whether this printer supports color printing.

**Returns:**
boolean - boolean value
### isValid() {#isValid--}
```
public boolean isValid()
```


Gets a value indicating whether the PrinterName property designates a valid printer.

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




### setCollate(boolean value) {#setCollate-boolean-}
```
public void setCollate(boolean value)
```


Gets or sets a value indicating whether the printed document is collated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setCopies(short value) {#setCopies-short-}
```
public void setCopies(short value)
```


Sets the number of copies of the document to print.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short | number of copies |

### setDuplex(int value) {#setDuplex-int-}
```
public void setDuplex(int value)
```


Gets or sets the printer setting for double-sided printing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setFromPage(int value) {#setFromPage-int-}
```
public void setFromPage(int value)
```


Gets or sets the page number of the first page to print.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setMaximumPage(int value) {#setMaximumPage-int-}
```
public void setMaximumPage(int value)
```


Gets or sets the maximum FromPage or ToPage that can be selected in a PrintDialog.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setMinimumPage(int value) {#setMinimumPage-int-}
```
public void setMinimumPage(int value)
```


Gets or sets the minimum FromPage or ToPage that can be selected in a PrintDialog.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setPrintFileName(String value) {#setPrintFileName-java.lang.String-}
```
public void setPrintFileName(String value)
```


Sets the filename to print.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | string value |

### setPrintRange(int value) {#setPrintRange-int-}
```
public void setPrintRange(int value)
```


Sets the page numbers that the user has specified to be printed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PdfPrintRange element |

### setPrintToFile(boolean value) {#setPrintToFile-boolean-}
```
public void setPrintToFile(boolean value)
```


Sets a value indicating whether the printing output is sent to a file instead of a port.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setPrinterName(String value) {#setPrinterName-java.lang.String-}
```
public void setPrinterName(String value)
```


Sets the name of the printer to use.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | string value |

### setSelectedPages(int[] pagesList) {#setSelectedPages-int---}
```
public void setSelectedPages(int[] pagesList)
```


Sets the number of selected pages to print.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pagesList | int[] | int array |

### setToPage(int value) {#setToPage-int-}
```
public void setToPage(int value)
```


Sets the number of the last page to print.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PdfPrintRange element |

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

