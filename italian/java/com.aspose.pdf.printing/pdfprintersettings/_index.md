---
title: "PdfPrinterSettings"
linktitle: "PdfPrinterSettings"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Specifica le informazioni su come un documento viene stampato, inclusa la stampante che lo stampa."
type: docs
weight: 50
url: /it/java/com.aspose.pdf.printing/pdfprintersettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrinterSettings

```
public class PdfPrinterSettings extends Object
```

Specifica le informazioni su come un documento viene stampato, inclusa la stampante che lo stampa.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfPrinterSettings](#PdfPrinterSettings--) | Inizializza una nuova istanza della classe PrinterSettings. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [canDuplex](#canDuplex--) | Ottiene un valore che indica se la stampante supporta la stampa fronte/retro. |
| [createMeasurementGraphics](#createMeasurementGraphics--) | Ottieni l'oggetto Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-boolean-) | Ottieni l'oggetto Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-) | Ottieni l'oggetto Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-) | Ottieni l'oggetto Graphics2D |
| [deepClone](#deepClone--) | Ottieni l'oggetto clonato |
| [getCopies](#getCopies--) | Ottiene il numero di copie del documento da stampare. |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Ottiene le impostazioni predefinite della pagina per questa stampante. |
| [getDuplex](#getDuplex--) | Ottiene o imposta l'impostazione della stampante per la stampa fronte/retro. |
| [getFromPage](#getFromPage--) | Ottiene o imposta il numero di pagina della prima pagina da stampare. |
| [getInstalledPrinters](#getInstalledPrinters--) | Ottiene i nomi di tutte le stampanti installata sul computer. |
| [getLandscapeAngle](#getLandscapeAngle--) | Ottiene l'angolo, in gradi, con cui l'orientamento verticale è ruotato per produrre l'orientamento orizzontale. |
| [getMaximumCopies](#getMaximumCopies--) | Ottiene il numero massimo di copie che la stampante consente all'utente di stampare contemporaneamente. |
| [getMaximumPage](#getMaximumPage--) | Ottiene o imposta il valore massimo di FromPage o ToPage che può essere selezionato in una PrintDialog. |
| [getMinimumPage](#getMinimumPage--) | Ottiene o imposta il valore minimo di FromPage o ToPage che può essere selezionato in una PrintDialog. |
| [getPaperSizes](#getPaperSizes--) | Ottiene le dimensioni della carta supportate da questa stampante. |
| [getPaperSources](#getPaperSources--) | Ottiene i vassoi di origine della carta disponibili sulla stampante. |
| [getPrinterName](#getPrinterName--) | Ottiene o imposta il nome della stampante da utilizzare. |
| [getPrinterResolutions](#getPrinterResolutions--) | Ottiene tutte le risoluzioni supportate da questa stampante. |
| [getPrinterSettings](#getPrinterSettings--) | Restituisce l'oggetto PrinterSettings |
| [getPrintFileName](#getPrintFileName--) | Ottiene o imposta il nome del file, quando si stampa su file. |
| [getPrintRange](#getPrintRange--) | Ottiene o imposta i numeri di pagina che l'utente ha specificato per la stampa. |
| [getSelectedPages](#getSelectedPages--) | Ottiene il numero di pagine selezionate da stampare. |
| [getToPage](#getToPage--) | Ottiene o imposta il numero dell'ultima pagina da stampare. |
| [isCollate](#isCollate--) | Ottiene o imposta un valore che indica se il documento stampato è raggruppato. |
| [isDefaultPrinter](#isDefaultPrinter--) | Ottiene un valore che indica se la proprietà PrinterName designa la stampante predefinita, eccetto quando l'utente imposta esplicitamente PrinterName. |
| [isDirectPrintingSupported](#isDirectPrintingSupported-com.aspose.pdf.ImageType-) | Ottiene un valore che indica se la stampante supporta DirectPrinting. |
| [isDirectPrintingSupported](#isDirectPrintingSupported-java.lang.String-) | Ottiene un valore che indica se la stampante supporta DirectPrinting. |
| [isPlotter](#isPlotter--) | Ottiene un valore che indica se la stampante è un plotter. |
| [isPrintToFile](#isPrintToFile--) | Ottiene un valore che indica se l'output di stampa è inviato a un file invece che a una porta. |
| [isSupportsColor](#isSupportsColor--) | Ottiene un valore che indica se questa stampante supporta la stampa a colori. |
| [isValid](#isValid--) | Ottiene un valore che indica se la proprietà PrinterName designa una stampante valida. |
| [setCollate](#setCollate-boolean-) | Ottiene o imposta un valore che indica se il documento stampato è raggruppato. |
| [setCopies](#setCopies-short-) | Imposta il numero di copie del documento da stampare. |
| [setDuplex](#setDuplex-int-) | Ottiene o imposta l'impostazione della stampante per la stampa fronte/retro. |
| [setFromPage](#setFromPage-int-) | Ottiene o imposta il numero di pagina della prima pagina da stampare. |
| [setMaximumPage](#setMaximumPage-int-) | Ottiene o imposta il valore massimo di FromPage o ToPage che può essere selezionato in una PrintDialog. |
| [setMinimumPage](#setMinimumPage-int-) | Ottiene o imposta il valore minimo di FromPage o ToPage che può essere selezionato in una PrintDialog. |
| [setPrinterName](#setPrinterName-java.lang.String-) | Imposta il nome della stampante da utilizzare. |
| [setPrintFileName](#setPrintFileName-java.lang.String-) | Imposta il nome file da stampare. |
| [setPrintRange](#setPrintRange-int-) | Imposta i numeri di pagina specificati dall'utente da stampare. |
| [setPrintToFile](#setPrintToFile-boolean-) | Imposta un valore che indica se l'output di stampa viene inviato a un file invece che a una porta. |
| [setSelectedPages](#setSelectedPages-int:A-) | Imposta il numero di pagine selezionate da stampare. |
| [setToPage](#setToPage-int-) | Imposta il numero dell'ultima pagina da stampare. |

### PdfPrinterSettings {#PdfPrinterSettings--}
```
public PdfPrinterSettings()
```

Inizializza una nuova istanza della classe PrinterSettings.

### canDuplex {#canDuplex--}
```
public boolean canDuplex()
```

Ottiene un valore che indica se la stampante supporta la stampa fronte/retro.

**Returns:**
valore booleano

### createMeasurementGraphics {#createMeasurementGraphics--}
```
public Graphics2D createMeasurementGraphics()
```

Ottieni l'oggetto Graphics2D

**Returns:**
oggetto Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-boolean-}
```
public Graphics2D createMeasurementGraphics(boolean value)
```

Ottieni l'oggetto Graphics2D

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

**Returns:**
oggetto Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-}
Ottieni l'oggetto Graphics2D

**Returns:**
oggetto Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-}
Ottieni l'oggetto Graphics2D

**Returns:**
oggetto Graphics2D

### deepClone {#deepClone--}
```
public PdfPrinterSettings deepClone()
```

Ottieni l'oggetto clonato

**Returns:**
Oggetto PdfPrinterSettings

### getCopies {#getCopies--}
```
public short getCopies()
```

Ottiene il numero di copie del documento da stampare.

**Returns:**
numero di copie

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Ottiene le impostazioni predefinite della pagina per questa stampante.

**Returns:**
impostazioni predefinite della pagina

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Ottiene o imposta l'impostazione della stampante per la stampa fronte/retro.

**Returns:**
valore int @see DuplexKind

### getFromPage {#getFromPage--}
```
public int getFromPage()
```

Ottiene o imposta il numero di pagina della prima pagina da stampare.

**Returns:**
valore int

### getInstalledPrinters {#getInstalledPrinters--}
```
public static ArrayList < String > getInstalledPrinters()
```

Ottiene i nomi di tutte le stampanti installata sul computer.

**Returns:**
oggetto {@code ArrayList<String>}

### getLandscapeAngle {#getLandscapeAngle--}
```
public int getLandscapeAngle()
```

Ottiene l'angolo, in gradi, con cui l'orientamento verticale è ruotato per produrre l'orientamento orizzontale.

**Returns:**
valore int

### getMaximumCopies {#getMaximumCopies--}
```
public int getMaximumCopies()
```

Ottiene il numero massimo di copie che la stampante consente all'utente di stampare contemporaneamente.

**Returns:**
valore int

### getMaximumPage {#getMaximumPage--}
```
public int getMaximumPage()
```

Ottiene o imposta il valore massimo di FromPage o ToPage che può essere selezionato in una PrintDialog.

**Returns:**
valore int

### getMinimumPage {#getMinimumPage--}
```
public int getMinimumPage()
```

Ottiene o imposta il valore minimo di FromPage o ToPage che può essere selezionato in una PrintDialog.

**Returns:**
valore int

### getPaperSizes {#getPaperSizes--}
```
public ArrayList < PrintPaperSize > getPaperSizes()
```

Ottiene le dimensioni della carta supportate da questa stampante.

**Returns:**
oggetto {@code ArrayList<PrintPaperSize> }

### getPaperSources {#getPaperSources--}
```
public ArrayList < PrintPaperSource > getPaperSources()
```

Ottiene i vassoi di origine della carta disponibili sulla stampante.

**Returns:**
oggetto {@code ArrayList<PrintPaperSource> }

### getPrinterName {#getPrinterName--}
```
public String getPrinterName()
```

Ottiene o imposta il nome della stampante da utilizzare.

**Returns:**
oggetto stringa

### getPrinterResolutions {#getPrinterResolutions--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection getPrinterResolutions()
```

Ottiene tutte le risoluzioni supportate da questa stampante.

**Returns:**
oggetto PrinterResolutionCollection

### getPrinterSettings {#getPrinterSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings getPrinterSettings()
```

Restituisce l'oggetto PrinterSettings

**Returns:**
oggetto PrinterSettings

### getPrintFileName {#getPrintFileName--}
```
public String getPrintFileName()
```

Ottiene o imposta il nome del file, quando si stampa su file.

**Returns:**
oggetto stringa

### getPrintRange {#getPrintRange--}
```
public int getPrintRange()
```

Ottiene o imposta i numeri di pagina che l'utente ha specificato per la stampa.

**Returns:**
valore int @see PdfPrintRange

### getSelectedPages {#getSelectedPages--}
```
public int[] getSelectedPages()
```

Ottiene il numero di pagine selezionate da stampare.

**Returns:**
array int pagesList @see PdfPrintRange

### getToPage {#getToPage--}
```
public int getToPage()
```

Ottiene o imposta il numero dell'ultima pagina da stampare.

**Returns:**
valore int

### isCollate {#isCollate--}
```
public boolean isCollate()
```

Ottiene o imposta un valore che indica se il documento stampato è raggruppato.

**Returns:**
valore booleano

### isDefaultPrinter {#isDefaultPrinter--}
```
public boolean isDefaultPrinter()
```

Ottiene un valore che indica se la proprietà PrinterName designa la stampante predefinita, eccetto quando l'utente imposta esplicitamente PrinterName.

**Returns:**
valore booleano

### isDirectPrintingSupported {#isDirectPrintingSupported-com.aspose.pdf.ImageType-}
Ottiene un valore che indica se la stampante supporta DirectPrinting.

### isDirectPrintingSupported {#isDirectPrintingSupported-java.lang.String-}
Ottiene un valore che indica se la stampante supporta DirectPrinting.

### isPlotter {#isPlotter--}
```
public boolean isPlotter()
```

Ottiene un valore che indica se la stampante è un plotter.

**Returns:**
valore booleano

### isPrintToFile {#isPrintToFile--}
```
public boolean isPrintToFile()
```

Ottiene un valore che indica se l'output di stampa è inviato a un file invece che a una porta.

**Returns:**
valore booleano

### isSupportsColor {#isSupportsColor--}
```
public boolean isSupportsColor()
```

Ottiene un valore che indica se questa stampante supporta la stampa a colori.

**Returns:**
valore booleano

### isValid {#isValid--}
```
public boolean isValid()
```

Ottiene un valore che indica se la proprietà PrinterName designa una stampante valida.

**Returns:**
valore booleano

### setCollate {#setCollate-boolean-}
```
public void setCollate(boolean value)
```

Ottiene o imposta un valore che indica se il documento stampato è raggruppato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setCopies {#setCopies-short-}
```
public void setCopies(short value)
```

Imposta il numero di copie del documento da stampare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | numero di copie |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Ottiene o imposta l'impostazione della stampante per la stampa fronte/retro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int @see DuplexKind |

### setFromPage {#setFromPage-int-}
```
public void setFromPage(int value)
```

Ottiene o imposta il numero di pagina della prima pagina da stampare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setMaximumPage {#setMaximumPage-int-}
```
public void setMaximumPage(int value)
```

Ottiene o imposta il valore massimo di FromPage o ToPage che può essere selezionato in una PrintDialog.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setMinimumPage {#setMinimumPage-int-}
```
public void setMinimumPage(int value)
```

Ottiene o imposta il valore minimo di FromPage o ToPage che può essere selezionato in una PrintDialog.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setPrinterName {#setPrinterName-java.lang.String-}
Imposta il nome della stampante da utilizzare.

### setPrintFileName {#setPrintFileName-java.lang.String-}
Imposta il nome file da stampare.

### setPrintRange {#setPrintRange-int-}
```
public void setPrintRange(int value)
```

Imposta i numeri di pagina specificati dall'utente da stampare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | elemento PdfPrintRange @see PdfPrintRange |

### setPrintToFile {#setPrintToFile-boolean-}
```
public void setPrintToFile(boolean value)
```

Imposta un valore che indica se l'output di stampa viene inviato a un file invece che a una porta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSelectedPages {#setSelectedPages-int:A-}
```
public void setSelectedPages(int[] pagesList)
```

Imposta il numero di pagine selezionate da stampare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagesList |  | array int @see PdfPrintRange |

### setToPage {#setToPage-int-}
```
public void setToPage(int value)
```

Imposta il numero dell'ultima pagina da stampare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | elemento PdfPrintRange @see PdfPrintRange |
