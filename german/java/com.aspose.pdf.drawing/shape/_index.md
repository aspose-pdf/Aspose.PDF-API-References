---
title: "Shape"
linktitle: "Shape"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Form – das Basis‑Grafikobjekt dar."
type: docs
weight: 130
url: /de/java/com.aspose.pdf.drawing/shape/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public abstract class Shape extends Object implements IBoundsCheckableItem
```

Stellt Form – das Basis‑Grafikobjekt dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Shape](#Shape--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Überprüft, ob das Element innerhalb der angegebenen Containerabmessungen (einschließlich) passt. |
| [getGraphInfo](#getGraphInfo--) | Ermittelt das Objekt, das die Diagramminformationen angibt, wie Farbe, Linienbreite usw. |
| [getText](#getText--) | Liest oder setzt einen Text für die Form |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Setzt ein Objekt, das die Graphinformationen angibt, wie Farbe, Linienbreite usw. |
| [setText](#setText-com.aspose.pdf.TextFragment-) | Liest oder setzt einen Text für die Form |

### Shape {#Shape--}
```
public Shape()
```



### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Überprüft, ob das Element innerhalb der angegebenen Containerabmessungen (einschließlich) passt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
Wahr, wenn es passt; andernfalls falsch.

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Ermittelt das Objekt, das die Diagramminformationen angibt, wie Farbe, Linienbreite usw.

**Returns:**
Objekt, das die Graphinformationen angibt.

### getText {#getText--}
```
public TextFragment getText()
```

Liest oder setzt einen Text für die Form

**Returns:**
TextFragment-Objekt

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Setzt ein Objekt, das die Graphinformationen angibt, wie Farbe, Linienbreite usw.

### setText {#setText-com.aspose.pdf.TextFragment-}
Liest oder setzt einen Text für die Form
