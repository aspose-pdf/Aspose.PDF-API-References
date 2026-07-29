---
title: "PdfPrinterSettings"
linktitle: "PdfPrinterSettings"
second_title: "Aspose.PDF för Java API-referens"
description: "Anger information om hur ett dokument skrivs ut, inklusive skrivaren som skriver ut det."
type: docs
weight: 50
url: /sv/java/com.aspose.pdf.printing/pdfprintersettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrinterSettings

```
public class PdfPrinterSettings extends Object
```

Anger information om hur ett dokument skrivs ut, inklusive skrivaren som skriver ut det.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfPrinterSettings](#PdfPrinterSettings--) | Initierar en ny instans av klassen PrinterSettings. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [canDuplex](#canDuplex--) | Hämtar ett värde som indikerar om skrivaren stöder dubbelsidig utskrift. |
| [createMeasurementGraphics](#createMeasurementGraphics--) | Hämta Graphics2D-objektet |
| [createMeasurementGraphics](#createMeasurementGraphics-boolean-) | Hämta Graphics2D-objektet |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-) | Hämta Graphics2D-objektet |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-) | Hämta Graphics2D-objektet |
| [deepClone](#deepClone--) | Hämta klonat objekt |
| [getCopies](#getCopies--) | Hämtar antalet kopior av dokumentet som ska skrivas ut. |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Hämtar standard sidinställningar för denna skrivare. |
| [getDuplex](#getDuplex--) | Hämtar eller anger skrivarnas inställning för dubbelsidig utskrift. |
| [getFromPage](#getFromPage--) | Hämtar eller anger sidnumret för den första sidan som ska skrivas ut. |
| [getInstalledPrinters](#getInstalledPrinters--) | Hämtar namnen på alla skrivare som är installerade på datorn. |
| [getLandscapeAngle](#getLandscapeAngle--) | Hämtar vinkeln, i grader, som porträttorienteringen roteras för att skapa landskapsorientering. |
| [getMaximumCopies](#getMaximumCopies--) | Hämtar det maximala antalet kopior som skrivaren tillåter användaren att skriva ut samtidigt. |
| [getMaximumPage](#getMaximumPage--) | Hämtar eller anger det maximala FromPage- eller ToPage‑värdet som kan väljas i en PrintDialog. |
| [getMinimumPage](#getMinimumPage--) | Hämtar eller anger det minsta FromPage- eller ToPage‑värdet som kan väljas i en PrintDialog. |
| [getPaperSizes](#getPaperSizes--) | Hämtar pappersstorlekarna som stöds av denna skrivare. |
| [getPaperSources](#getPaperSources--) | Hämtar papperskällfacken som finns tillgängliga på skrivaren. |
| [getPrinterName](#getPrinterName--) | Hämtar eller anger namnet på den skrivare som ska användas. |
| [getPrinterResolutions](#getPrinterResolutions--) | Hämtar alla upplösningar som stöds av denna skrivare. |
| [getPrinterSettings](#getPrinterSettings--) | Returnera PrinterSettings-objekt |
| [getPrintFileName](#getPrintFileName--) | Hämtar eller anger filnamnet när du skriver ut till en fil. |
| [getPrintRange](#getPrintRange--) | Hämtar eller anger sidnumren som användaren har specificerat för utskrift. |
| [getSelectedPages](#getSelectedPages--) | Hämtar antalet valda sidor för utskrift. |
| [getToPage](#getToPage--) | Hämtar eller anger numret på den sista sidan som ska skrivas ut. |
| [isCollate](#isCollate--) | Hämtar eller anger ett värde som indikerar om det utskrivna dokumentet är sorterat. |
| [isDefaultPrinter](#isDefaultPrinter--) | Hämtar ett värde som indikerar om egenskapen PrinterName anger standardskrivaren, förutom när användaren uttryckligen anger PrinterName. |
| [isDirectPrintingSupported](#isDirectPrintingSupported-com.aspose.pdf.ImageType-) | Hämtar ett värde som indikerar om skrivaren är Supported DirectPrinting |
| [isDirectPrintingSupported](#isDirectPrintingSupported-java.lang.String-) | Hämtar ett värde som indikerar om skrivaren är Supported DirectPrinting |
| [isPlotter](#isPlotter--) | Hämtar ett värde som indikerar om skrivaren är en plotter. |
| [isPrintToFile](#isPrintToFile--) | Hämtar ett värde som indikerar om utskriftsresultatet skickas till en fil istället för en port. |
| [isSupportsColor](#isSupportsColor--) | Hämtar ett värde som indikerar om den här skrivaren stöder färgutskrift. |
| [isValid](#isValid--) | Hämtar ett värde som indikerar om egenskapen PrinterName anger en giltig skrivare. |
| [setCollate](#setCollate-boolean-) | Hämtar eller anger ett värde som indikerar om det utskrivna dokumentet är sorterat. |
| [setCopies](#setCopies-short-) | Anger antalet kopior av dokumentet som ska skrivas ut. |
| [setDuplex](#setDuplex-int-) | Hämtar eller anger skrivarnas inställning för dubbelsidig utskrift. |
| [setFromPage](#setFromPage-int-) | Hämtar eller anger sidnumret för den första sidan som ska skrivas ut. |
| [setMaximumPage](#setMaximumPage-int-) | Hämtar eller anger det maximala FromPage- eller ToPage‑värdet som kan väljas i en PrintDialog. |
| [setMinimumPage](#setMinimumPage-int-) | Hämtar eller anger det minsta FromPage- eller ToPage‑värdet som kan väljas i en PrintDialog. |
| [setPrinterName](#setPrinterName-java.lang.String-) | Anger namnet på skrivaren som ska användas. |
| [setPrintFileName](#setPrintFileName-java.lang.String-) | Anger filnamnet för utskrift. |
| [setPrintRange](#setPrintRange-int-) | Anger sidnumren som användaren har specificerat för utskrift. |
| [setPrintToFile](#setPrintToFile-boolean-) | Anger ett värde som indikerar om utskriftsresultatet skickas till en fil istället för en port. |
| [setSelectedPages](#setSelectedPages-int:A-) | Anger antalet valda sidor för utskrift. |
| [setToPage](#setToPage-int-) | Anger numret på den sista sidan som ska skrivas ut. |

### PdfPrinterSettings {#PdfPrinterSettings--}
```
public PdfPrinterSettings()
```

Initierar en ny instans av klassen PrinterSettings.

### canDuplex {#canDuplex--}
```
public boolean canDuplex()
```

Hämtar ett värde som indikerar om skrivaren stöder dubbelsidig utskrift.

**Returns:**
booleskt värde

### createMeasurementGraphics {#createMeasurementGraphics--}
```
public Graphics2D createMeasurementGraphics()
```

Hämta Graphics2D-objektet

**Returns:**
Graphics2D-objekt

### createMeasurementGraphics {#createMeasurementGraphics-boolean-}
```
public Graphics2D createMeasurementGraphics(boolean value)
```

Hämta Graphics2D-objektet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

**Returns:**
Graphics2D-objekt

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-}
Hämta Graphics2D-objektet

**Returns:**
Graphics2D-objekt

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-}
Hämta Graphics2D-objektet

**Returns:**
Graphics2D-objekt

### deepClone {#deepClone--}
```
public PdfPrinterSettings deepClone()
```

Hämta klonat objekt

**Returns:**
PdfPrinterSettings-objekt

### getCopies {#getCopies--}
```
public short getCopies()
```

Hämtar antalet kopior av dokumentet som ska skrivas ut.

**Returns:**
antal kopior

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Hämtar standard sidinställningar för denna skrivare.

**Returns:**
standard sidinställningar

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Hämtar eller anger skrivarnas inställning för dubbelsidig utskrift.

**Returns:**
int‑värde @see DuplexKind

### getFromPage {#getFromPage--}
```
public int getFromPage()
```

Hämtar eller anger sidnumret för den första sidan som ska skrivas ut.

**Returns:**
int‑värde

### getInstalledPrinters {#getInstalledPrinters--}
```
public static ArrayList < String > getInstalledPrinters()
```

Hämtar namnen på alla skrivare som är installerade på datorn.

**Returns:**
{@code ArrayList<String>} objekt

### getLandscapeAngle {#getLandscapeAngle--}
```
public int getLandscapeAngle()
```

Hämtar vinkeln, i grader, som porträttorienteringen roteras för att skapa landskapsorientering.

**Returns:**
int‑värde

### getMaximumCopies {#getMaximumCopies--}
```
public int getMaximumCopies()
```

Hämtar det maximala antalet kopior som skrivaren tillåter användaren att skriva ut samtidigt.

**Returns:**
int‑värde

### getMaximumPage {#getMaximumPage--}
```
public int getMaximumPage()
```

Hämtar eller anger det maximala FromPage- eller ToPage‑värdet som kan väljas i en PrintDialog.

**Returns:**
int‑värde

### getMinimumPage {#getMinimumPage--}
```
public int getMinimumPage()
```

Hämtar eller anger det minsta FromPage- eller ToPage‑värdet som kan väljas i en PrintDialog.

**Returns:**
int‑värde

### getPaperSizes {#getPaperSizes--}
```
public ArrayList < PrintPaperSize > getPaperSizes()
```

Hämtar pappersstorlekarna som stöds av denna skrivare.

**Returns:**
{@code ArrayList<PrintPaperSize> } objekt

### getPaperSources {#getPaperSources--}
```
public ArrayList < PrintPaperSource > getPaperSources()
```

Hämtar papperskällfacken som finns tillgängliga på skrivaren.

**Returns:**
{@code ArrayList<PrintPaperSource> } objekt

### getPrinterName {#getPrinterName--}
```
public String getPrinterName()
```

Hämtar eller anger namnet på den skrivare som ska användas.

**Returns:**
string‑objekt

### getPrinterResolutions {#getPrinterResolutions--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection getPrinterResolutions()
```

Hämtar alla upplösningar som stöds av denna skrivare.

**Returns:**
PrinterResolutionCollection objekt

### getPrinterSettings {#getPrinterSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings getPrinterSettings()
```

Returnera PrinterSettings-objekt

**Returns:**
PrinterSettings objekt

### getPrintFileName {#getPrintFileName--}
```
public String getPrintFileName()
```

Hämtar eller anger filnamnet när du skriver ut till en fil.

**Returns:**
string‑objekt

### getPrintRange {#getPrintRange--}
```
public int getPrintRange()
```

Hämtar eller anger sidnumren som användaren har specificerat för utskrift.

**Returns:**
int värde @see PdfPrintRange

### getSelectedPages {#getSelectedPages--}
```
public int[] getSelectedPages()
```

Hämtar antalet valda sidor för utskrift.

**Returns:**
pagesList int-array @see PdfPrintRange

### getToPage {#getToPage--}
```
public int getToPage()
```

Hämtar eller anger numret på den sista sidan som ska skrivas ut.

**Returns:**
int‑värde

### isCollate {#isCollate--}
```
public boolean isCollate()
```

Hämtar eller anger ett värde som indikerar om det utskrivna dokumentet är sorterat.

**Returns:**
booleskt värde

### isDefaultPrinter {#isDefaultPrinter--}
```
public boolean isDefaultPrinter()
```

Hämtar ett värde som indikerar om egenskapen PrinterName anger standardskrivaren, förutom när användaren uttryckligen anger PrinterName.

**Returns:**
booleskt värde

### isDirectPrintingSupported {#isDirectPrintingSupported-com.aspose.pdf.ImageType-}
Hämtar ett värde som indikerar om skrivaren är Supported DirectPrinting

### isDirectPrintingSupported {#isDirectPrintingSupported-java.lang.String-}
Hämtar ett värde som indikerar om skrivaren är Supported DirectPrinting

### isPlotter {#isPlotter--}
```
public boolean isPlotter()
```

Hämtar ett värde som indikerar om skrivaren är en plotter.

**Returns:**
booleskt värde

### isPrintToFile {#isPrintToFile--}
```
public boolean isPrintToFile()
```

Hämtar ett värde som indikerar om utskriftsresultatet skickas till en fil istället för en port.

**Returns:**
booleskt värde

### isSupportsColor {#isSupportsColor--}
```
public boolean isSupportsColor()
```

Hämtar ett värde som indikerar om den här skrivaren stöder färgutskrift.

**Returns:**
booleskt värde

### isValid {#isValid--}
```
public boolean isValid()
```

Hämtar ett värde som indikerar om egenskapen PrinterName anger en giltig skrivare.

**Returns:**
booleskt värde

### setCollate {#setCollate-boolean-}
```
public void setCollate(boolean value)
```

Hämtar eller anger ett värde som indikerar om det utskrivna dokumentet är sorterat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setCopies {#setCopies-short-}
```
public void setCopies(short value)
```

Anger antalet kopior av dokumentet som ska skrivas ut.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | antal kopior |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Hämtar eller anger skrivarnas inställning för dubbelsidig utskrift.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde @see DuplexKind |

### setFromPage {#setFromPage-int-}
```
public void setFromPage(int value)
```

Hämtar eller anger sidnumret för den första sidan som ska skrivas ut.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setMaximumPage {#setMaximumPage-int-}
```
public void setMaximumPage(int value)
```

Hämtar eller anger det maximala FromPage- eller ToPage‑värdet som kan väljas i en PrintDialog.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setMinimumPage {#setMinimumPage-int-}
```
public void setMinimumPage(int value)
```

Hämtar eller anger det minsta FromPage- eller ToPage‑värdet som kan väljas i en PrintDialog.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setPrinterName {#setPrinterName-java.lang.String-}
Anger namnet på skrivaren som ska användas.

### setPrintFileName {#setPrintFileName-java.lang.String-}
Anger filnamnet för utskrift.

### setPrintRange {#setPrintRange-int-}
```
public void setPrintRange(int value)
```

Anger sidnumren som användaren har specificerat för utskrift.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | PdfPrintRange-element @see PdfPrintRange |

### setPrintToFile {#setPrintToFile-boolean-}
```
public void setPrintToFile(boolean value)
```

Anger ett värde som indikerar om utskriftsresultatet skickas till en fil istället för en port.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSelectedPages {#setSelectedPages-int:A-}
```
public void setSelectedPages(int[] pagesList)
```

Anger antalet valda sidor för utskrift.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pagesList |  | int-array @see PdfPrintRange |

### setToPage {#setToPage-int-}
```
public void setToPage(int value)
```

Anger numret på den sista sidan som ska skrivas ut.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | PdfPrintRange-element @see PdfPrintRange |
