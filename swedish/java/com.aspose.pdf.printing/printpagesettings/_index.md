---
title: "PrintPageSettings"
linktitle: "PrintPageSettings"
second_title: "Aspose.PDF för Java API-referens"
description: "Anger inställningar som gäller för en enskild utskriven sida."
type: docs
weight: 90
url: /sv/java/com.aspose.pdf.printing/printpagesettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPageSettings

```
public class PrintPageSettings extends Object
```

Anger inställningar som gäller för en enskild utskriven sida.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PrintPageSettings](#PrintPageSettings--) | Initierar en ny instans av PageSettings-klassen med standardskrivaren. |
| [PrintPageSettings](#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Initierar en ny instans av PageSettings-klassen med standardskrivaren. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds](#getBounds--) | Hämtar sidans storlek med hänsyn till sidorienteringen som anges av egenskapen Landscape. |
| [getHardMarginX](#getHardMarginX--) | Hämtar x-koordinaten, i hundradelar av tum, för den hårda marginalen till vänster på sidan. |
| [getHardMarginY](#getHardMarginY--) | Hämtar y-koordinaten, i hundradelar av tum, för den hårda marginalen högst upp på sidan. |
| [getMargins](#getMargins--) | Hämtar marginalerna för den här sidan. |
| [getPageSettings](#getPageSettings--) | Hämtar sidinställningar |
| [getPaperSize](#getPaperSize--) | Hämtar pappersstorleken för sidan. |
| [getPaperSource](#getPaperSource--) | Hämtar sidans papperskälla; till exempel skrivarens övre fack. |
| [getPrintableArea](#getPrintableArea--) | Hämtar gränserna för det utskrivbara området på sidan för skrivaren. |
| [getPrinterResolution](#getPrinterResolution--) | Hämtar skrivarupplösningen för sidan. |
| [getPrinterSettings](#getPrinterSettings--) | Hämtar skrivarinställningarna som är associerade med sidan. |
| [isColor](#isColor--) | Hämtar eller anger ett värde som indikerar om sidan ska skrivas ut i färg. |
| [isLandscape](#isLandscape--) | Hämtar eller anger ett värde som indikerar om sidan skrivs ut i liggande eller stående orientering. |
| [setColor](#setColor-boolean-) | Hämtar eller anger ett värde som indikerar om sidan ska skrivas ut i färg. |
| [setLandscape](#setLandscape-boolean-) | Hämtar eller anger ett värde som indikerar om sidan skrivs ut i liggande eller stående orientering. |
| [setMargins](#setMargins-com.aspose.pdf.printing.PrinterMargins-) | Ställer in marginalerna för den här sidan. |
| [setPaperSize](#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Ställer in pappersstorleken för sidan. |
| [setPaperSource](#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-) | Ställer in sidans papperskälla; till exempel skrivarens övre fack. |
| [setPrinterResolution](#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-) | Ställer in skrivarupplösningen för sidan. |
| [setPrinterSettings](#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Ställer in skrivarinställningarna som är associerade med sidan. |

### PrintPageSettings {#PrintPageSettings--}
```
public PrintPageSettings()
```

Initierar en ny instans av PageSettings-klassen med standardskrivaren.

### PrintPageSettings {#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Initierar en ny instans av PageSettings-klassen med standardskrivaren.

### getBounds {#getBounds--}
```
public Rectangle getBounds()
```

Hämtar sidans storlek med hänsyn till sidorienteringen som anges av egenskapen Landscape.

**Returns:**
Rectangle‑objekt

### getHardMarginX {#getHardMarginX--}
```
public float getHardMarginX()
```

Hämtar x-koordinaten, i hundradelar av tum, för den hårda marginalen till vänster på sidan.

**Returns:**
flyttalsvärde

### getHardMarginY {#getHardMarginY--}
```
public float getHardMarginY()
```

Hämtar y-koordinaten, i hundradelar av tum, för den hårda marginalen högst upp på sidan.

**Returns:**
flyttalsvärde

### getMargins {#getMargins--}
```
public PrinterMargins getMargins()
```

Hämtar marginalerna för den här sidan.

**Returns:**
PrinterMargins-objekt

### getPageSettings {#getPageSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PageSettings getPageSettings()
```

Hämtar sidinställningar

**Returns:**
PageSettings-objekt

### getPaperSize {#getPaperSize--}
```
public PrintPaperSize getPaperSize()
```

Hämtar pappersstorleken för sidan.

**Returns:**
PrintPaperSize-objekt

### getPaperSource {#getPaperSource--}
```
public PrintPaperSource getPaperSource()
```

Hämtar sidans papperskälla; till exempel skrivarens övre fack.

**Returns:**
PrintPaperSource-objekt

### getPrintableArea {#getPrintableArea--}
```
public Rectangle getPrintableArea()
```

Hämtar gränserna för det utskrivbara området på sidan för skrivaren.

**Returns:**
Rectangle‑objekt

### getPrinterResolution {#getPrinterResolution--}
```
public PdfPrinterResolution getPrinterResolution()
```

Hämtar skrivarupplösningen för sidan.

**Returns:**
PdfPrinterResolution-objekt

### getPrinterSettings {#getPrinterSettings--}
```
public PdfPrinterSettings getPrinterSettings()
```

Hämtar skrivarinställningarna som är associerade med sidan.

**Returns:**
PdfPrinterSettings-objekt

### isColor {#isColor--}
```
public boolean isColor()
```

Hämtar eller anger ett värde som indikerar om sidan ska skrivas ut i färg.

**Returns:**
booleskt värde

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

Hämtar eller anger ett värde som indikerar om sidan skrivs ut i liggande eller stående orientering.

**Returns:**
booleskt värde

### setColor {#setColor-boolean-}
```
public void setColor(boolean value)
```

Hämtar eller anger ett värde som indikerar om sidan ska skrivas ut i färg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

Hämtar eller anger ett värde som indikerar om sidan skrivs ut i liggande eller stående orientering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMargins {#setMargins-com.aspose.pdf.printing.PrinterMargins-}
Ställer in marginalerna för den här sidan.

### setPaperSize {#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Ställer in pappersstorleken för sidan.

### setPaperSource {#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-}
Ställer in sidans papperskälla; till exempel skrivarens övre fack.

### setPrinterResolution {#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-}
Ställer in skrivarupplösningen för sidan.

### setPrinterSettings {#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Ställer in skrivarinställningarna som är associerade med sidan.
