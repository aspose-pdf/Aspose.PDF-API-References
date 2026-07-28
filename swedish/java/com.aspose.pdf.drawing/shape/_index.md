---
title: "Form"
linktitle: "Form"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar form - det grundläggande grafikobjektet."
type: docs
weight: 130
url: /sv/java/com.aspose.pdf.drawing/shape/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public abstract class Shape extends Object implements IBoundsCheckableItem
```

Representerar form - det grundläggande grafikobjektet.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Shape](#Shape--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Kontrollerar om objektet passar inom de angivna behållardimensionerna (inklusive). |
| [getGraphInfo](#getGraphInfo--) | Hämtar objekt som indikerar diagraminformation, såsom färg, linjebredd, etc. |
| [getText](#getText--) | Hämtar eller anger en text för form |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Ställer in objekt som indikerar diagraminformation, såsom färg, linjebredd, etc. |
| [setText](#setText-com.aspose.pdf.TextFragment-) | Hämtar eller anger en text för form |

### Shape {#Shape--}
```
public Shape()
```



### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Kontrollerar om objektet passar inom de angivna behållardimensionerna (inklusive).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
Sant om det passar; annars falskt.

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Hämtar objekt som indikerar diagraminformation, såsom färg, linjebredd, etc.

**Returns:**
objekt som indikerar grafinformationen.

### getText {#getText--}
```
public TextFragment getText()
```

Hämtar eller anger en text för form

**Returns:**
TextFragment objekt

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Ställer in objekt som indikerar diagraminformation, såsom färg, linjebredd, etc.

### setText {#setText-com.aspose.pdf.TextFragment-}
Hämtar eller anger en text för form
