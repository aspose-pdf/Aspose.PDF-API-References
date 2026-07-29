---
title: "Line"
linktitle: "Line"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Linie dar."
type: docs
weight: 90
url: /de/java/com.aspose.pdf.drawing/line/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Line, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Line

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Line extends Shape
```

Stellt eine Linie dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Line](#Line--) | Nur für den internen Gebrauch |
| [Line](#Line-float:A-) | Initialisiert eine neue Instanz der {@code Line} Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Überprüft, ob das Element innerhalb der angegebenen Containerabmessungen (einschließlich) passt. |
| [getPositionArray](#getPositionArray--) | Liest das Objekt, das das Positionsarray angibt. Das Array besteht aus den Koordinaten jedes Kontrollpunkts der Linie. direkt. |
| [setPositionArray](#setPositionArray-float:A-) | Setzt das Objekt, das das Positionsarray angibt. Das Array besteht aus den Koordinaten jedes Kontrollpunkts der Linie. direkt. |

### Line {#Line--}
```
public Line()
```

Nur für den internen Gebrauch

### Line {#Line-float:A-}
```
public Line(float[] positionArray)
```

Initialisiert eine neue Instanz der {@code Line} Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| positionArray |  | Das Linienpositionsarray. |

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

### getPositionArray {#getPositionArray--}
```
public float[] getPositionArray()
```

Liest das Objekt, das das Positionsarray angibt. Das Array besteht aus den Koordinaten jedes Kontrollpunkts der Linie. direkt.

**Returns:**
die das Positionsarray angibt.

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Setzt das Objekt, das das Positionsarray angibt. Das Array besteht aus den Koordinaten jedes Kontrollpunkts der Linie. direkt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | die das Positionsarray angibt. |
