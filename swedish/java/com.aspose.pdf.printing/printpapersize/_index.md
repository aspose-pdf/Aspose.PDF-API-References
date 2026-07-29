---
title: "PrintPaperSize"
linktitle: "PrintPaperSize"
second_title: "Aspose.PDF för Java API-referens"
description: "Anger storleken på ett papper."
type: docs
weight: 100
url: /sv/java/com.aspose.pdf.printing/printpapersize/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPaperSize

```
public class PrintPaperSize extends Object
```

Anger storleken på ett papper.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PrintPaperSize](#PrintPaperSize--) | Initierar en ny instans av klassen PaperSize. |
| [PrintPaperSize](#PrintPaperSize-int-java.lang.String-int-int-) | Initierar en ny instans av klassen PaperSize. |
| [PrintPaperSize](#PrintPaperSize-java.lang.String-int-int-) | Initierar en ny instans av klassen PaperSize. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeight](#getHeight--) | Hämtar eller anger höjden på papperet, i hundradelar av en tum. |
| [getKind](#getKind--) | Hämtar papperstypen. |
| [getPaperName](#getPaperName--) | Hämtar eller anger namnet på papperstypen. |
| [getRawKind](#getRawKind--) | Hämtar eller anger ett heltal som representerar ett av PaperSize-värdena eller ett anpassat värde. |
| [getWidth](#getWidth--) | Hämtar eller anger bredden på papperet, i hundradelar av en tum. |
| [setHeight](#setHeight-int-) | Hämtar eller anger höjden på papperet, i hundradelar av en tum. |
| [setPaperName](#setPaperName-java.lang.String-) | Hämtar namnet på papperstypen. |
| [setWidth](#setWidth-int-) | Anger bredden på papperet, i hundradelar av en tum. |
| [toNativePaperSize](#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Konverterar {@link PaperSize} till Windows-specifik System.Drawing.Printing.PaperSize. |
| [toString](#toString--) | Hämtar namnet på den här instansen. |

### PrintPaperSize {#PrintPaperSize--}
```
public PrintPaperSize()
```

Initierar en ny instans av klassen PaperSize.

### PrintPaperSize {#PrintPaperSize-int-java.lang.String-int-int-}
Initierar en ny instans av klassen PaperSize.

### PrintPaperSize {#PrintPaperSize-java.lang.String-int-int-}
Initierar en ny instans av klassen PaperSize.

### getHeight {#getHeight--}
```
public int getHeight()
```

Hämtar eller anger höjden på papperet, i hundradelar av en tum.

**Returns:**
int‑värde

### getKind {#getKind--}
```
public int getKind()
```

Hämtar papperstypen.

**Returns:**
int‑värde @see PrinterPaperKind

### getPaperName {#getPaperName--}
```
public String getPaperName()
```

Hämtar eller anger namnet på papperstypen.

**Returns:**
String värde

### getRawKind {#getRawKind--}
```
public int getRawKind()
```

Hämtar eller anger ett heltal som representerar ett av PaperSize-värdena eller ett anpassat värde.

**Returns:**
int‑värde

### getWidth {#getWidth--}
```
public int getWidth()
```

Hämtar eller anger bredden på papperet, i hundradelar av en tum.

**Returns:**
int‑värde

### setHeight {#setHeight-int-}
```
public void setHeight(int value)
```

Hämtar eller anger höjden på papperet, i hundradelar av en tum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setPaperName {#setPaperName-java.lang.String-}
Hämtar namnet på papperstypen.

### setWidth {#setWidth-int-}
```
public void setWidth(int value)
```

Anger bredden på papperet, i hundradelar av en tum.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### toNativePaperSize {#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Konverterar {@link PaperSize} till Windows-specifik System.Drawing.Printing.PaperSize.

### toString {#toString--}
```
public String toString()
```

Hämtar namnet på den här instansen.

**Returns:**
String värde
