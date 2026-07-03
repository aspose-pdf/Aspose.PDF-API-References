---
title: PdfPrinterSettings
linktitle: PdfPrinterSettings
second_title: Aspose.PDF for Java API Reference
description: Specifies information about how a document is printed, including the printer that prints it.
type: docs
weight: 50
url: /java/com.aspose.pdf.printing/pdfprintersettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrinterSettings

```
public class PdfPrinterSettings extends Object
```

Specifies information about how a document is printed, including the printer that prints it.

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfPrinterSettings](#PdfPrinterSettings--) | Initializes a new instance of the PrinterSettings class. |

## Methods

| Method | Description |
| --- | --- |
| [canDuplex](#canDuplex--) | Gets a value indicating whether the printer supports double-sided printing. |
| [createMeasurementGraphics](#createMeasurementGraphics--) | Get Graphics2D object |
| [createMeasurementGraphics](#createMeasurementGraphics-boolean-) | Get Graphics2D object |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-) | Get Graphics2D object |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-) | Get Graphics2D object |
| [deepClone](#deepClone--) | Get clonned object |
| [getCopies](#getCopies--) | Gets the number of copies of the document to print. |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Gets the default page settings for this printer. |
| [getDuplex](#getDuplex--) | Gets or sets the printer setting for double-sided printing. |
| [getFromPage](#getFromPage--) | Gets or sets the page number of the first page to print. |
| [getInstalledPrinters](#getInstalledPrinters--) | Gets the names of all printers installed on the computer. |
| [getLandscapeAngle](#getLandscapeAngle--) | Gets the angle, in degrees, that the portrait orientation is rotated to produce the landscape orientation. |
| [getMaximumCopies](#getMaximumCopies--) | Gets the maximum number of copies that the printer enables the user to print at a time. |
| [getMaximumPage](#getMaximumPage--) | Gets or sets the maximum FromPage or ToPage that can be selected in a PrintDialog. |
| [getMinimumPage](#getMinimumPage--) | Gets or sets the minimum FromPage or ToPage that can be selected in a PrintDialog. |
| [getPaperSizes](#getPaperSizes--) | Gets the paper sizes that are supported by this printer. |
| [getPaperSources](#getPaperSources--) | Gets the paper source trays that are available on the printer. |
| [getPrinterName](#getPrinterName--) | Gets or sets the name of the printer to use. |
| [getPrinterResolutions](#getPrinterResolutions--) | Gets all the resolutions that are supported by this printer. |
| [getPrinterSettings](#getPrinterSettings--) | Return PrinterSettings object |
| [getPrintFileName](#getPrintFileName--) | Gets or sets the file name, when printing to a file. |
| [getPrintRange](#getPrintRange--) | Gets or sets the page numbers that the user has specified to be printed. |
| [getSelectedPages](#getSelectedPages--) | Gets the number of selected pages to print. |
| [getToPage](#getToPage--) | Gets or sets the number of the last page to print. |
| [isCollate](#isCollate--) | Gets or sets a value indicating whether the printed document is collated. |
| [isDefaultPrinter](#isDefaultPrinter--) | Gets a value indicating whether the PrinterName property designates the default printer, except when the user explicitly sets PrinterName. |
| [isDirectPrintingSupported](#isDirectPrintingSupported-com.aspose.pdf.ImageType-) | Gets a value indicating whether the printer is Supported DirectPrinting |
| [isDirectPrintingSupported](#isDirectPrintingSupported-java.lang.String-) | Gets a value indicating whether the printer is Supported DirectPrinting |
| [isPlotter](#isPlotter--) | Gets a value indicating whether the printer is a plotter. |
| [isPrintToFile](#isPrintToFile--) | Gets a value indicating whether the printing output is sent to a file instead of a port. |
| [isSupportsColor](#isSupportsColor--) | Gets a value indicating whether this printer supports color printing. |
| [isValid](#isValid--) | Gets a value indicating whether the PrinterName property designates a valid printer. |
| [setCollate](#setCollate-boolean-) | Gets or sets a value indicating whether the printed document is collated. |
| [setCopies](#setCopies-short-) | Sets the number of copies of the document to print. |
| [setDuplex](#setDuplex-int-) | Gets or sets the printer setting for double-sided printing. |
| [setFromPage](#setFromPage-int-) | Gets or sets the page number of the first page to print. |
| [setMaximumPage](#setMaximumPage-int-) | Gets or sets the maximum FromPage or ToPage that can be selected in a PrintDialog. |
| [setMinimumPage](#setMinimumPage-int-) | Gets or sets the minimum FromPage or ToPage that can be selected in a PrintDialog. |
| [setPrinterName](#setPrinterName-java.lang.String-) | Sets the name of the printer to use. |
| [setPrintFileName](#setPrintFileName-java.lang.String-) | Sets the filename to print. |
| [setPrintRange](#setPrintRange-int-) | Sets the page numbers that the user has specified to be printed. |
| [setPrintToFile](#setPrintToFile-boolean-) | Sets a value indicating whether the printing output is sent to a file instead of a port. |
| [setSelectedPages](#setSelectedPages-int:A-) | Sets the number of selected pages to print. |
| [setToPage](#setToPage-int-) | Sets the number of the last page to print. |

### PdfPrinterSettings {#PdfPrinterSettings--}
```
public PdfPrinterSettings()
```

Initializes a new instance of the PrinterSettings class.

### canDuplex {#canDuplex--}
```
public boolean canDuplex()
```

Gets a value indicating whether the printer supports double-sided printing.

**Returns:**
boolean value

### createMeasurementGraphics {#createMeasurementGraphics--}
```
public Graphics2D createMeasurementGraphics()
```

Get Graphics2D object

**Returns:**
Graphics2D object

### createMeasurementGraphics {#createMeasurementGraphics-boolean-}
```
public Graphics2D createMeasurementGraphics(boolean value)
```

Get Graphics2D object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

**Returns:**
Graphics2D object

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-}
Get Graphics2D object

**Returns:**
Graphics2D object

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-}
Get Graphics2D object

**Returns:**
Graphics2D object

### deepClone {#deepClone--}
```
public PdfPrinterSettings deepClone()
```

Get clonned object

**Returns:**
PdfPrinterSettings object

### getCopies {#getCopies--}
```
public short getCopies()
```

Gets the number of copies of the document to print.

**Returns:**
number of copies

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Gets the default page settings for this printer.

**Returns:**
default page settings

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Gets or sets the printer setting for double-sided printing.

**Returns:**
int value @see DuplexKind

### getFromPage {#getFromPage--}
```
public int getFromPage()
```

Gets or sets the page number of the first page to print.

**Returns:**
int value

### getInstalledPrinters {#getInstalledPrinters--}
```
public static ArrayList < String > getInstalledPrinters()
```

Gets the names of all printers installed on the computer.

**Returns:**
{@code ArrayList<String>} object

### getLandscapeAngle {#getLandscapeAngle--}
```
public int getLandscapeAngle()
```

Gets the angle, in degrees, that the portrait orientation is rotated to produce the landscape orientation.

**Returns:**
int value

### getMaximumCopies {#getMaximumCopies--}
```
public int getMaximumCopies()
```

Gets the maximum number of copies that the printer enables the user to print at a time.

**Returns:**
int value

### getMaximumPage {#getMaximumPage--}
```
public int getMaximumPage()
```

Gets or sets the maximum FromPage or ToPage that can be selected in a PrintDialog.

**Returns:**
int value

### getMinimumPage {#getMinimumPage--}
```
public int getMinimumPage()
```

Gets or sets the minimum FromPage or ToPage that can be selected in a PrintDialog.

**Returns:**
int value

### getPaperSizes {#getPaperSizes--}
```
public ArrayList < PrintPaperSize > getPaperSizes()
```

Gets the paper sizes that are supported by this printer.

**Returns:**
{@code ArrayList<PrintPaperSize> } object

### getPaperSources {#getPaperSources--}
```
public ArrayList < PrintPaperSource > getPaperSources()
```

Gets the paper source trays that are available on the printer.

**Returns:**
{@code ArrayList<PrintPaperSource> } object

### getPrinterName {#getPrinterName--}
```
public String getPrinterName()
```

Gets or sets the name of the printer to use.

**Returns:**
string object

### getPrinterResolutions {#getPrinterResolutions--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection getPrinterResolutions()
```

Gets all the resolutions that are supported by this printer.

**Returns:**
PrinterResolutionCollection object

### getPrinterSettings {#getPrinterSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings getPrinterSettings()
```

Return PrinterSettings object

**Returns:**
PrinterSettings object

### getPrintFileName {#getPrintFileName--}
```
public String getPrintFileName()
```

Gets or sets the file name, when printing to a file.

**Returns:**
string object

### getPrintRange {#getPrintRange--}
```
public int getPrintRange()
```

Gets or sets the page numbers that the user has specified to be printed.

**Returns:**
int value @see PdfPrintRange

### getSelectedPages {#getSelectedPages--}
```
public int[] getSelectedPages()
```

Gets the number of selected pages to print.

**Returns:**
pagesList int array @see PdfPrintRange

### getToPage {#getToPage--}
```
public int getToPage()
```

Gets or sets the number of the last page to print.

**Returns:**
int value

### isCollate {#isCollate--}
```
public boolean isCollate()
```

Gets or sets a value indicating whether the printed document is collated.

**Returns:**
boolean value

### isDefaultPrinter {#isDefaultPrinter--}
```
public boolean isDefaultPrinter()
```

Gets a value indicating whether the PrinterName property designates the default printer, except when the user explicitly sets PrinterName.

**Returns:**
boolean value

### isDirectPrintingSupported {#isDirectPrintingSupported-com.aspose.pdf.ImageType-}
Gets a value indicating whether the printer is Supported DirectPrinting

### isDirectPrintingSupported {#isDirectPrintingSupported-java.lang.String-}
Gets a value indicating whether the printer is Supported DirectPrinting

### isPlotter {#isPlotter--}
```
public boolean isPlotter()
```

Gets a value indicating whether the printer is a plotter.

**Returns:**
boolean value

### isPrintToFile {#isPrintToFile--}
```
public boolean isPrintToFile()
```

Gets a value indicating whether the printing output is sent to a file instead of a port.

**Returns:**
boolean value

### isSupportsColor {#isSupportsColor--}
```
public boolean isSupportsColor()
```

Gets a value indicating whether this printer supports color printing.

**Returns:**
boolean value

### isValid {#isValid--}
```
public boolean isValid()
```

Gets a value indicating whether the PrinterName property designates a valid printer.

**Returns:**
boolean value

### setCollate {#setCollate-boolean-}
```
public void setCollate(boolean value)
```

Gets or sets a value indicating whether the printed document is collated.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setCopies {#setCopies-short-}
```
public void setCopies(short value)
```

Sets the number of copies of the document to print.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | number of copies |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Gets or sets the printer setting for double-sided printing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value @see DuplexKind |

### setFromPage {#setFromPage-int-}
```
public void setFromPage(int value)
```

Gets or sets the page number of the first page to print.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setMaximumPage {#setMaximumPage-int-}
```
public void setMaximumPage(int value)
```

Gets or sets the maximum FromPage or ToPage that can be selected in a PrintDialog.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setMinimumPage {#setMinimumPage-int-}
```
public void setMinimumPage(int value)
```

Gets or sets the minimum FromPage or ToPage that can be selected in a PrintDialog.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setPrinterName {#setPrinterName-java.lang.String-}
Sets the name of the printer to use.

### setPrintFileName {#setPrintFileName-java.lang.String-}
Sets the filename to print.

### setPrintRange {#setPrintRange-int-}
```
public void setPrintRange(int value)
```

Sets the page numbers that the user has specified to be printed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | PdfPrintRange element @see PdfPrintRange |

### setPrintToFile {#setPrintToFile-boolean-}
```
public void setPrintToFile(boolean value)
```

Sets a value indicating whether the printing output is sent to a file instead of a port.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSelectedPages {#setSelectedPages-int:A-}
```
public void setSelectedPages(int[] pagesList)
```

Sets the number of selected pages to print.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pagesList |  | int array @see PdfPrintRange |

### setToPage {#setToPage-int-}
```
public void setToPage(int value)
```

Sets the number of the last page to print.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | PdfPrintRange element @see PdfPrintRange |
