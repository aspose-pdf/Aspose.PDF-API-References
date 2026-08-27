---
title: "PrintPageSettings"
linktitle: "PrintPageSettings"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Specifica le impostazioni che si applicano a una singola pagina stampata."
type: docs
weight: 90
url: /it/java/com.aspose.pdf.printing/printpagesettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPageSettings

```
public class PrintPageSettings extends Object
```

Specifica le impostazioni che si applicano a una singola pagina stampata.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PrintPageSettings](#PrintPageSettings--) | Inizializza una nuova istanza della classe PageSettings utilizzando la stampante predefinita. |
| [PrintPageSettings](#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Inizializza una nuova istanza della classe PageSettings utilizzando la stampante predefinita. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds](#getBounds--) | Ottiene le dimensioni della pagina, tenendo conto dell'orientamento della pagina specificato dalla proprietà Landscape. |
| [getHardMarginX](#getHardMarginX--) | Ottiene la coordinata x, in centesimi di pollice, del margine fisso a sinistra della pagina. |
| [getHardMarginY](#getHardMarginY--) | Ottiene la coordinata y, in centesimi di pollice, del margine fisso in alto della pagina. |
| [getMargins](#getMargins--) | Ottiene i margini per questa pagina. |
| [getPageSettings](#getPageSettings--) | Ottiene le impostazioni della pagina |
| [getPaperSize](#getPaperSize--) | Ottiene le dimensioni della carta per la pagina. |
| [getPaperSource](#getPaperSource--) | Ottiene la sorgente della carta della pagina; ad esempio, il vassoio superiore della stampante. |
| [getPrintableArea](#getPrintableArea--) | Ottiene i limiti dell'area stampabile della pagina per la stampante. |
| [getPrinterResolution](#getPrinterResolution--) | Ottiene la risoluzione della stampante per la pagina. |
| [getPrinterSettings](#getPrinterSettings--) | Ottiene le impostazioni della stampante associate alla pagina. |
| [isColor](#isColor--) | Ottiene o imposta un valore che indica se la pagina deve essere stampata a colori. |
| [isLandscape](#isLandscape--) | Ottiene o imposta un valore che indica se la pagina è stampata in orientamento orizzontale o verticale. |
| [setColor](#setColor-boolean-) | Ottiene o imposta un valore che indica se la pagina deve essere stampata a colori. |
| [setLandscape](#setLandscape-boolean-) | Ottiene o imposta un valore che indica se la pagina è stampata in orientamento orizzontale o verticale. |
| [setMargins](#setMargins-com.aspose.pdf.printing.PrinterMargins-) | Imposta i margini per questa pagina. |
| [setPaperSize](#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Imposta le dimensioni della carta per la pagina. |
| [setPaperSource](#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-) | Imposta la sorgente della carta della pagina; ad esempio, il vassoio superiore della stampante. |
| [setPrinterResolution](#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-) | Imposta la risoluzione della stampante per la pagina. |
| [setPrinterSettings](#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Imposta le impostazioni della stampante associate alla pagina. |

### PrintPageSettings {#PrintPageSettings--}
```
public PrintPageSettings()
```

Inizializza una nuova istanza della classe PageSettings utilizzando la stampante predefinita.

### PrintPageSettings {#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Inizializza una nuova istanza della classe PageSettings utilizzando la stampante predefinita.

### getBounds {#getBounds--}
```
public Rectangle getBounds()
```

Ottiene le dimensioni della pagina, tenendo conto dell'orientamento della pagina specificato dalla proprietà Landscape.

**Returns:**
oggetto Rectangle

### getHardMarginX {#getHardMarginX--}
```
public float getHardMarginX()
```

Ottiene la coordinata x, in centesimi di pollice, del margine fisso a sinistra della pagina.

**Returns:**
valore float

### getHardMarginY {#getHardMarginY--}
```
public float getHardMarginY()
```

Ottiene la coordinata y, in centesimi di pollice, del margine fisso in alto della pagina.

**Returns:**
valore float

### getMargins {#getMargins--}
```
public PrinterMargins getMargins()
```

Ottiene i margini per questa pagina.

**Returns:**
Oggetto PrinterMargins

### getPageSettings {#getPageSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PageSettings getPageSettings()
```

Ottiene le impostazioni della pagina

**Returns:**
Oggetto PageSettings

### getPaperSize {#getPaperSize--}
```
public PrintPaperSize getPaperSize()
```

Ottiene le dimensioni della carta per la pagina.

**Returns:**
Oggetto PrintPaperSize

### getPaperSource {#getPaperSource--}
```
public PrintPaperSource getPaperSource()
```

Ottiene la sorgente della carta della pagina; ad esempio, il vassoio superiore della stampante.

**Returns:**
Oggetto PrintPaperSource

### getPrintableArea {#getPrintableArea--}
```
public Rectangle getPrintableArea()
```

Ottiene i limiti dell'area stampabile della pagina per la stampante.

**Returns:**
oggetto Rectangle

### getPrinterResolution {#getPrinterResolution--}
```
public PdfPrinterResolution getPrinterResolution()
```

Ottiene la risoluzione della stampante per la pagina.

**Returns:**
Oggetto PdfPrinterResolution

### getPrinterSettings {#getPrinterSettings--}
```
public PdfPrinterSettings getPrinterSettings()
```

Ottiene le impostazioni della stampante associate alla pagina.

**Returns:**
Oggetto PdfPrinterSettings

### isColor {#isColor--}
```
public boolean isColor()
```

Ottiene o imposta un valore che indica se la pagina deve essere stampata a colori.

**Returns:**
valore booleano

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

Ottiene o imposta un valore che indica se la pagina è stampata in orientamento orizzontale o verticale.

**Returns:**
valore booleano

### setColor {#setColor-boolean-}
```
public void setColor(boolean value)
```

Ottiene o imposta un valore che indica se la pagina deve essere stampata a colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

Ottiene o imposta un valore che indica se la pagina è stampata in orientamento orizzontale o verticale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMargins {#setMargins-com.aspose.pdf.printing.PrinterMargins-}
Imposta i margini per questa pagina.

### setPaperSize {#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Imposta le dimensioni della carta per la pagina.

### setPaperSource {#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-}
Imposta la sorgente della carta della pagina; ad esempio, il vassoio superiore della stampante.

### setPrinterResolution {#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-}
Imposta la risoluzione della stampante per la pagina.

### setPrinterSettings {#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Imposta le impostazioni della stampante associate alla pagina.
