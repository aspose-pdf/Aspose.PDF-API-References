---
title: "Kurve"
linktitle: "Kurve"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Bézier‑Kurve dar."
type: docs
weight: 30
url: /de/java/com.aspose.pdf.drawing/curve/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Curve, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Curve

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Curve extends Shape
```

Stellt eine Bézier‑Kurve dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Curve](#Curve--) | Nur für den internen Gebrauch |
| [Curve](#Curve-float:A-) | Initialisiert eine neue Instanz der {@code Curve}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Überprüft, ob das Element innerhalb der angegebenen Containerabmessungen (einschließlich) passt. |
| [getPositionArray](#getPositionArray--) | Gibt ein Float-Positionsarray zurück. |
| [setPositionArray](#setPositionArray-float:A-) | Setzt ein Float-Positionsarray. |

### Curve {#Curve--}
```
public Curve()
```

Nur für den internen Gebrauch

### Curve {#Curve-float:A-}
```
public Curve(float[] positionArray)
```

Initialisiert eine neue Instanz der {@code Curve}-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| positionArray |  | Das Positionsarray der Kontrollpunkte der Kurve. Es sollten vier Kontrollpunkte vorhanden sein, sodass die Länge des Arrays acht betragen sollte. |

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

Gibt ein Float-Positionsarray zurück.

**Returns:**
float[] array

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Setzt ein Float-Positionsarray.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float[] array |
