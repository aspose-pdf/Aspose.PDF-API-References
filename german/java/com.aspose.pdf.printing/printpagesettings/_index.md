---
title: "PrintPageSettings"
linktitle: "PrintPageSettings"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Gibt Einstellungen an, die für eine einzelne gedruckte Seite gelten."
type: docs
weight: 90
url: /de/java/com.aspose.pdf.printing/printpagesettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPageSettings

```
public class PrintPageSettings extends Object
```

Gibt Einstellungen an, die für eine einzelne gedruckte Seite gelten.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PrintPageSettings](#PrintPageSettings--) | Initialisiert eine neue Instanz der PageSettings-Klasse mit dem Standarddrucker. |
| [PrintPageSettings](#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Initialisiert eine neue Instanz der PageSettings-Klasse mit dem Standarddrucker. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBounds](#getBounds--) | Ruft die Größe der Seite ab, wobei die durch die Landscape-Eigenschaft angegebene Seitenausrichtung berücksichtigt wird. |
| [getHardMarginX](#getHardMarginX--) | Ruft die x-Koordinate, in Hundertstel Zoll, des festen Randes links auf der Seite ab. |
| [getHardMarginY](#getHardMarginY--) | Ruft die y-Koordinate, in Hundertstel Zoll, des festen Randes oben auf der Seite ab. |
| [getMargins](#getMargins--) | Ruft die Ränder für diese Seite ab. |
| [getPageSettings](#getPageSettings--) | Ruft Seiteneinstellungen ab |
| [getPaperSize](#getPaperSize--) | Ruft die Papiergröße für die Seite ab. |
| [getPaperSource](#getPaperSource--) | Ruft die Papierquelle der Seite ab; zum Beispiel das obere Fach des Druckers. |
| [getPrintableArea](#getPrintableArea--) | Ruft die Grenzen des druckbaren Bereichs der Seite für den Drucker ab. |
| [getPrinterResolution](#getPrinterResolution--) | Ruft die Druckerauflösung für die Seite ab. |
| [getPrinterSettings](#getPrinterSettings--) | Ruft die dem Seite zugeordneten Druckereinstellungen ab |
| [isColor](#isColor--) | Liest oder setzt einen Wert, der angibt, ob die Seite in Farbe gedruckt werden soll. |
| [isLandscape](#isLandscape--) | Liest oder setzt einen Wert, der angibt, ob die Seite im Quer- oder Hochformat gedruckt wird. |
| [setColor](#setColor-boolean-) | Liest oder setzt einen Wert, der angibt, ob die Seite in Farbe gedruckt werden soll. |
| [setLandscape](#setLandscape-boolean-) | Liest oder setzt einen Wert, der angibt, ob die Seite im Quer- oder Hochformat gedruckt wird. |
| [setMargins](#setMargins-com.aspose.pdf.printing.PrinterMargins-) | Legt die Ränder für diese Seite fest. |
| [setPaperSize](#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Legt die Papiergröße für die Seite fest. |
| [setPaperSource](#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-) | Legt die Papierquelle der Seite fest; zum Beispiel das obere Fach des Druckers. |
| [setPrinterResolution](#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-) | Legt die Druckerauflösung für die Seite fest. |
| [setPrinterSettings](#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Legt die dem Seite zugeordneten Druckereinstellungen fest. |

### PrintPageSettings {#PrintPageSettings--}
```
public PrintPageSettings()
```

Initialisiert eine neue Instanz der PageSettings-Klasse mit dem Standarddrucker.

### PrintPageSettings {#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Initialisiert eine neue Instanz der PageSettings-Klasse mit dem Standarddrucker.

### getBounds {#getBounds--}
```
public Rectangle getBounds()
```

Ruft die Größe der Seite ab, wobei die durch die Landscape-Eigenschaft angegebene Seitenausrichtung berücksichtigt wird.

**Returns:**
Rectangle-Objekt

### getHardMarginX {#getHardMarginX--}
```
public float getHardMarginX()
```

Ruft die x-Koordinate, in Hundertstel Zoll, des festen Randes links auf der Seite ab.

**Returns:**
float-Wert

### getHardMarginY {#getHardMarginY--}
```
public float getHardMarginY()
```

Ruft die y-Koordinate, in Hundertstel Zoll, des festen Randes oben auf der Seite ab.

**Returns:**
float-Wert

### getMargins {#getMargins--}
```
public PrinterMargins getMargins()
```

Ruft die Ränder für diese Seite ab.

**Returns:**
PrinterMargins-Objekt

### getPageSettings {#getPageSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PageSettings getPageSettings()
```

Ruft Seiteneinstellungen ab

**Returns:**
PageSettings-Objekt

### getPaperSize {#getPaperSize--}
```
public PrintPaperSize getPaperSize()
```

Ruft die Papiergröße für die Seite ab.

**Returns:**
PrintPaperSize-Objekt

### getPaperSource {#getPaperSource--}
```
public PrintPaperSource getPaperSource()
```

Ruft die Papierquelle der Seite ab; zum Beispiel das obere Fach des Druckers.

**Returns:**
PrintPaperSource-Objekt

### getPrintableArea {#getPrintableArea--}
```
public Rectangle getPrintableArea()
```

Ruft die Grenzen des druckbaren Bereichs der Seite für den Drucker ab.

**Returns:**
Rectangle-Objekt

### getPrinterResolution {#getPrinterResolution--}
```
public PdfPrinterResolution getPrinterResolution()
```

Ruft die Druckerauflösung für die Seite ab.

**Returns:**
PdfPrinterResolution-Objekt

### getPrinterSettings {#getPrinterSettings--}
```
public PdfPrinterSettings getPrinterSettings()
```

Ruft die dem Seite zugeordneten Druckereinstellungen ab

**Returns:**
PdfPrinterSettings-Objekt

### isColor {#isColor--}
```
public boolean isColor()
```

Liest oder setzt einen Wert, der angibt, ob die Seite in Farbe gedruckt werden soll.

**Returns:**
boolescher Wert

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

Liest oder setzt einen Wert, der angibt, ob die Seite im Quer- oder Hochformat gedruckt wird.

**Returns:**
boolescher Wert

### setColor {#setColor-boolean-}
```
public void setColor(boolean value)
```

Liest oder setzt einen Wert, der angibt, ob die Seite in Farbe gedruckt werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

Liest oder setzt einen Wert, der angibt, ob die Seite im Quer- oder Hochformat gedruckt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMargins {#setMargins-com.aspose.pdf.printing.PrinterMargins-}
Legt die Ränder für diese Seite fest.

### setPaperSize {#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Legt die Papiergröße für die Seite fest.

### setPaperSource {#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-}
Legt die Papierquelle der Seite fest; zum Beispiel das obere Fach des Druckers.

### setPrinterResolution {#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-}
Legt die Druckerauflösung für die Seite fest.

### setPrinterSettings {#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Legt die dem Seite zugeordneten Druckereinstellungen fest.
