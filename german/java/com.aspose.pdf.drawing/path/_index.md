---
title: "Path"
linktitle: "Path"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt einen Bogen dar."
type: docs
weight: 100
url: /de/java/com.aspose.pdf.drawing/path/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Path, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Path

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Path extends Shape
```

Stellt einen Bogen dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Path](#Path--) | Initialisiert eine neue Instanz der {@code Path} Klasse. |
| [Path](#Path-com.aspose.pdf.drawing.Shape:A-) | Initialisiert eine neue Instanz der {@code Path} Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Überprüft, ob das Element innerhalb der angegebenen Containerabmessungen (einschließlich) passt. |
| [getShapes](#getShapes--) | <p> Erhält oder setzt Formensammlung. </p> |
| [getShapesInternal](#getShapesInternal--) | Erhält oder setzt Formensammlung. |

### Path {#Path--}
```
public Path()
```

Initialisiert eine neue Instanz der {@code Path} Klasse.

### Path {#Path-com.aspose.pdf.drawing.Shape:A-}
Initialisiert eine neue Instanz der {@code Path} Klasse.

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

### getShapes {#getShapes--}
```
public List < Shape > getShapes()
```

<p> Erhält oder setzt Formensammlung. </p>

**Returns:**
{@code java.util.List<Shape> }Objekt

### getShapesInternal {#getShapesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< Shape > getShapesInternal()
```

Erhält oder setzt Formensammlung.

**Returns:**
internes Objekt
