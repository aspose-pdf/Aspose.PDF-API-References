---
title: "PdfPrinterSettings"
linktitle: "PdfPrinterSettings"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Gibt Informationen darüber an, wie ein Dokument gedruckt wird, einschließlich des Druckers, der es druckt."
type: docs
weight: 50
url: /de/java/com.aspose.pdf.printing/pdfprintersettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrinterSettings

```
public class PdfPrinterSettings extends Object
```

Gibt Informationen darüber an, wie ein Dokument gedruckt wird, einschließlich des Druckers, der es druckt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfPrinterSettings](#PdfPrinterSettings--) | Initialisiert eine neue Instanz der Klasse PrinterSettings. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [canDuplex](#canDuplex--) | Gibt einen Wert zurück, der angibt, ob der Drucker beidseitiges Drucken unterstützt. |
| [createMeasurementGraphics](#createMeasurementGraphics--) | Graphics2D-Objekt abrufen |
| [createMeasurementGraphics](#createMeasurementGraphics-boolean-) | Graphics2D-Objekt abrufen |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-) | Graphics2D-Objekt abrufen |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-) | Graphics2D-Objekt abrufen |
| [deepClone](#deepClone--) | Kloniertes Objekt abrufen |
| [getCopies](#getCopies--) | Gibt die Anzahl der Kopien des zu druckenden Dokuments zurück. |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Gibt die Standardseiteneinstellungen für diesen Drucker zurück. |
| [getDuplex](#getDuplex--) | Liest oder legt die Druckereinstellung für beidseitiges Drucken fest. |
| [getFromPage](#getFromPage--) | Liest oder legt die Seitenzahl der ersten zu druckenden Seite fest. |
| [getInstalledPrinters](#getInstalledPrinters--) | Gibt die Namen aller auf dem Computer installierten Drucker zurück. |
| [getLandscapeAngle](#getLandscapeAngle--) | Gibt den Winkel in Grad zurück, um den die Hochformat‑Ausrichtung gedreht wird, um die Querformat‑Ausrichtung zu erzeugen. |
| [getMaximumCopies](#getMaximumCopies--) | Gibt die maximale Anzahl von Kopien zurück, die der Drucker dem Benutzer gleichzeitig zum Drucken erlaubt. |
| [getMaximumPage](#getMaximumPage--) | Liest oder legt das maximale FromPage‑ oder ToPage‑Intervall fest, das im PrintDialog ausgewählt werden kann. |
| [getMinimumPage](#getMinimumPage--) | Liest oder legt das minimale FromPage‑ oder ToPage‑Intervall fest, das im PrintDialog ausgewählt werden kann. |
| [getPaperSizes](#getPaperSizes--) | Gibt die Papiergrößen zurück, die von diesem Drucker unterstützt werden. |
| [getPaperSources](#getPaperSources--) | Gibt die Papierzuführungsfächer zurück, die am Drucker verfügbar sind. |
| [getPrinterName](#getPrinterName--) | Liest oder legt den Namen des zu verwendenden Druckers fest. |
| [getPrinterResolutions](#getPrinterResolutions--) | Gibt alle Auflösungen zurück, die von diesem Drucker unterstützt werden. |
| [getPrinterSettings](#getPrinterSettings--) | PrinterSettings-Objekt zurückgeben |
| [getPrintFileName](#getPrintFileName--) | Liest oder legt den Dateinamen fest, wenn in eine Datei gedruckt wird. |
| [getPrintRange](#getPrintRange--) | Liest oder legt die Seitenzahlen fest, die der Benutzer zum Drucken angegeben hat. |
| [getSelectedPages](#getSelectedPages--) | Gibt die Anzahl der ausgewählten Seiten zum Drucken zurück. |
| [getToPage](#getToPage--) | Liest oder legt die Nummer der letzten zu druckenden Seite fest. |
| [isCollate](#isCollate--) | Liest oder legt einen Wert fest, der angibt, ob das gedruckte Dokument sortiert ist. |
| [isDefaultPrinter](#isDefaultPrinter--) | Gibt einen Wert zurück, der angibt, ob die Eigenschaft PrinterName den Standarddrucker bezeichnet, außer wenn der Benutzer PrinterName explizit festlegt. |
| [isDirectPrintingSupported](#isDirectPrintingSupported-com.aspose.pdf.ImageType-) | Gibt einen Wert zurück, der angibt, ob der Drucker Supported DirectPrinting unterstützt |
| [isDirectPrintingSupported](#isDirectPrintingSupported-java.lang.String-) | Gibt einen Wert zurück, der angibt, ob der Drucker Supported DirectPrinting unterstützt |
| [isPlotter](#isPlotter--) | Gibt einen Wert zurück, der angibt, ob der Drucker ein Plotter ist. |
| [isPrintToFile](#isPrintToFile--) | Gibt einen Wert zurück, der angibt, ob die Druckausgabe in eine Datei statt in einen Port gesendet wird. |
| [isSupportsColor](#isSupportsColor--) | Gibt einen Wert zurück, der angibt, ob dieser Drucker Farbdruck unterstützt. |
| [isValid](#isValid--) | Gibt einen Wert zurück, der angibt, ob die Eigenschaft PrinterName einen gültigen Drucker bezeichnet. |
| [setCollate](#setCollate-boolean-) | Liest oder legt einen Wert fest, der angibt, ob das gedruckte Dokument sortiert ist. |
| [setCopies](#setCopies-short-) | Legt die Anzahl der Kopien des zu druckenden Dokuments fest. |
| [setDuplex](#setDuplex-int-) | Liest oder legt die Druckereinstellung für beidseitiges Drucken fest. |
| [setFromPage](#setFromPage-int-) | Liest oder legt die Seitenzahl der ersten zu druckenden Seite fest. |
| [setMaximumPage](#setMaximumPage-int-) | Liest oder legt das maximale FromPage‑ oder ToPage‑Intervall fest, das im PrintDialog ausgewählt werden kann. |
| [setMinimumPage](#setMinimumPage-int-) | Liest oder legt das minimale FromPage‑ oder ToPage‑Intervall fest, das im PrintDialog ausgewählt werden kann. |
| [setPrinterName](#setPrinterName-java.lang.String-) | Legt den Namen des zu verwendenden Druckers fest. |
| [setPrintFileName](#setPrintFileName-java.lang.String-) | Legt den Dateinamen zum Drucken fest. |
| [setPrintRange](#setPrintRange-int-) | Legt die Seitenzahlen fest, die der Benutzer zum Drucken angegeben hat. |
| [setPrintToFile](#setPrintToFile-boolean-) | Legt einen Wert fest, der angibt, ob die Druckausgabe in eine Datei statt in einen Port gesendet wird. |
| [setSelectedPages](#setSelectedPages-int:A-) | Legt die Anzahl der ausgewählten Seiten zum Drucken fest. |
| [setToPage](#setToPage-int-) | Legt die Nummer der letzten zu druckenden Seite fest. |

### PdfPrinterSettings {#PdfPrinterSettings--}
```
public PdfPrinterSettings()
```

Initialisiert eine neue Instanz der Klasse PrinterSettings.

### canDuplex {#canDuplex--}
```
public boolean canDuplex()
```

Gibt einen Wert zurück, der angibt, ob der Drucker beidseitiges Drucken unterstützt.

**Returns:**
boolescher Wert

### createMeasurementGraphics {#createMeasurementGraphics--}
```
public Graphics2D createMeasurementGraphics()
```

Graphics2D-Objekt abrufen

**Returns:**
Graphics2D-Objekt

### createMeasurementGraphics {#createMeasurementGraphics-boolean-}
```
public Graphics2D createMeasurementGraphics(boolean value)
```

Graphics2D-Objekt abrufen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

**Returns:**
Graphics2D-Objekt

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-}
Graphics2D-Objekt abrufen

**Returns:**
Graphics2D-Objekt

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-}
Graphics2D-Objekt abrufen

**Returns:**
Graphics2D-Objekt

### deepClone {#deepClone--}
```
public PdfPrinterSettings deepClone()
```

Kloniertes Objekt abrufen

**Returns:**
PdfPrinterSettings-Objekt

### getCopies {#getCopies--}
```
public short getCopies()
```

Gibt die Anzahl der Kopien des zu druckenden Dokuments zurück.

**Returns:**
Anzahl der Kopien

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Gibt die Standardseiteneinstellungen für diesen Drucker zurück.

**Returns:**
Standardseiteneinstellungen

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Liest oder legt die Druckereinstellung für beidseitiges Drucken fest.

**Returns:**
int-Wert @see DuplexKind

### getFromPage {#getFromPage--}
```
public int getFromPage()
```

Liest oder legt die Seitenzahl der ersten zu druckenden Seite fest.

**Returns:**
int-Wert

### getInstalledPrinters {#getInstalledPrinters--}
```
public static ArrayList < String > getInstalledPrinters()
```

Gibt die Namen aller auf dem Computer installierten Drucker zurück.

**Returns:**
{@code ArrayList<String>} Objekt

### getLandscapeAngle {#getLandscapeAngle--}
```
public int getLandscapeAngle()
```

Gibt den Winkel in Grad zurück, um den die Hochformat‑Ausrichtung gedreht wird, um die Querformat‑Ausrichtung zu erzeugen.

**Returns:**
int-Wert

### getMaximumCopies {#getMaximumCopies--}
```
public int getMaximumCopies()
```

Gibt die maximale Anzahl von Kopien zurück, die der Drucker dem Benutzer gleichzeitig zum Drucken erlaubt.

**Returns:**
int-Wert

### getMaximumPage {#getMaximumPage--}
```
public int getMaximumPage()
```

Liest oder legt das maximale FromPage‑ oder ToPage‑Intervall fest, das im PrintDialog ausgewählt werden kann.

**Returns:**
int-Wert

### getMinimumPage {#getMinimumPage--}
```
public int getMinimumPage()
```

Liest oder legt das minimale FromPage‑ oder ToPage‑Intervall fest, das im PrintDialog ausgewählt werden kann.

**Returns:**
int-Wert

### getPaperSizes {#getPaperSizes--}
```
public ArrayList < PrintPaperSize > getPaperSizes()
```

Gibt die Papiergrößen zurück, die von diesem Drucker unterstützt werden.

**Returns:**
{@code ArrayList<PrintPaperSize> } Objekt

### getPaperSources {#getPaperSources--}
```
public ArrayList < PrintPaperSource > getPaperSources()
```

Gibt die Papierzuführungsfächer zurück, die am Drucker verfügbar sind.

**Returns:**
{@code ArrayList<PrintPaperSource> } Objekt

### getPrinterName {#getPrinterName--}
```
public String getPrinterName()
```

Liest oder legt den Namen des zu verwendenden Druckers fest.

**Returns:**
String‑Objekt

### getPrinterResolutions {#getPrinterResolutions--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection getPrinterResolutions()
```

Gibt alle Auflösungen zurück, die von diesem Drucker unterstützt werden.

**Returns:**
PrinterResolutionCollection-Objekt

### getPrinterSettings {#getPrinterSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings getPrinterSettings()
```

PrinterSettings-Objekt zurückgeben

**Returns:**
PrinterSettings-Objekt

### getPrintFileName {#getPrintFileName--}
```
public String getPrintFileName()
```

Liest oder legt den Dateinamen fest, wenn in eine Datei gedruckt wird.

**Returns:**
String‑Objekt

### getPrintRange {#getPrintRange--}
```
public int getPrintRange()
```

Liest oder legt die Seitenzahlen fest, die der Benutzer zum Drucken angegeben hat.

**Returns:**
int-Wert @see PdfPrintRange

### getSelectedPages {#getSelectedPages--}
```
public int[] getSelectedPages()
```

Gibt die Anzahl der ausgewählten Seiten zum Drucken zurück.

**Returns:**
pagesList int-Array @see PdfPrintRange

### getToPage {#getToPage--}
```
public int getToPage()
```

Liest oder legt die Nummer der letzten zu druckenden Seite fest.

**Returns:**
int-Wert

### isCollate {#isCollate--}
```
public boolean isCollate()
```

Liest oder legt einen Wert fest, der angibt, ob das gedruckte Dokument sortiert ist.

**Returns:**
boolescher Wert

### isDefaultPrinter {#isDefaultPrinter--}
```
public boolean isDefaultPrinter()
```

Gibt einen Wert zurück, der angibt, ob die Eigenschaft PrinterName den Standarddrucker bezeichnet, außer wenn der Benutzer PrinterName explizit festlegt.

**Returns:**
boolescher Wert

### isDirectPrintingSupported {#isDirectPrintingSupported-com.aspose.pdf.ImageType-}
Gibt einen Wert zurück, der angibt, ob der Drucker Supported DirectPrinting unterstützt

### isDirectPrintingSupported {#isDirectPrintingSupported-java.lang.String-}
Gibt einen Wert zurück, der angibt, ob der Drucker Supported DirectPrinting unterstützt

### isPlotter {#isPlotter--}
```
public boolean isPlotter()
```

Gibt einen Wert zurück, der angibt, ob der Drucker ein Plotter ist.

**Returns:**
boolescher Wert

### isPrintToFile {#isPrintToFile--}
```
public boolean isPrintToFile()
```

Gibt einen Wert zurück, der angibt, ob die Druckausgabe in eine Datei statt in einen Port gesendet wird.

**Returns:**
boolescher Wert

### isSupportsColor {#isSupportsColor--}
```
public boolean isSupportsColor()
```

Gibt einen Wert zurück, der angibt, ob dieser Drucker Farbdruck unterstützt.

**Returns:**
boolescher Wert

### isValid {#isValid--}
```
public boolean isValid()
```

Gibt einen Wert zurück, der angibt, ob die Eigenschaft PrinterName einen gültigen Drucker bezeichnet.

**Returns:**
boolescher Wert

### setCollate {#setCollate-boolean-}
```
public void setCollate(boolean value)
```

Liest oder legt einen Wert fest, der angibt, ob das gedruckte Dokument sortiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setCopies {#setCopies-short-}
```
public void setCopies(short value)
```

Legt die Anzahl der Kopien des zu druckenden Dokuments fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Anzahl der Kopien |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Liest oder legt die Druckereinstellung für beidseitiges Drucken fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert @see DuplexKind |

### setFromPage {#setFromPage-int-}
```
public void setFromPage(int value)
```

Liest oder legt die Seitenzahl der ersten zu druckenden Seite fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setMaximumPage {#setMaximumPage-int-}
```
public void setMaximumPage(int value)
```

Liest oder legt das maximale FromPage‑ oder ToPage‑Intervall fest, das im PrintDialog ausgewählt werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setMinimumPage {#setMinimumPage-int-}
```
public void setMinimumPage(int value)
```

Liest oder legt das minimale FromPage‑ oder ToPage‑Intervall fest, das im PrintDialog ausgewählt werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setPrinterName {#setPrinterName-java.lang.String-}
Legt den Namen des zu verwendenden Druckers fest.

### setPrintFileName {#setPrintFileName-java.lang.String-}
Legt den Dateinamen zum Drucken fest.

### setPrintRange {#setPrintRange-int-}
```
public void setPrintRange(int value)
```

Legt die Seitenzahlen fest, die der Benutzer zum Drucken angegeben hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | PdfPrintRange-Element @see PdfPrintRange |

### setPrintToFile {#setPrintToFile-boolean-}
```
public void setPrintToFile(boolean value)
```

Legt einen Wert fest, der angibt, ob die Druckausgabe in eine Datei statt in einen Port gesendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSelectedPages {#setSelectedPages-int:A-}
```
public void setSelectedPages(int[] pagesList)
```

Legt die Anzahl der ausgewählten Seiten zum Drucken fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pagesList |  | int-Array @see PdfPrintRange |

### setToPage {#setToPage-int-}
```
public void setToPage(int value)
```

Legt die Nummer der letzten zu druckenden Seite fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | PdfPrintRange-Element @see PdfPrintRange |
