---
title: "GraphicElement"
linktitle: "GraphicElement"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar basklass för grafiskt objekt på sidan."
type: docs
weight: 10
url: /sv/java/com.aspose.pdf.vector/graphicelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public abstract class GraphicElement extends Object implements com.aspose.ms.System.IDisposable
```

Representerar basklass för grafiskt objekt på sidan.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Lägger till aktuellt element på sidan. Om det finns många element att lägga till är det bättre att använda Page#addGraphics(GraphicElementCollection,Rectangle). |
| [dispose](#dispose--) | Frigör alla resurser som används av klassen {@link GraphicElement}. |
| [getMatrix](#getMatrix--) | Hämtar grafikelementets matris. Matrisen sätts när elementet skapas. Den ändras när SetPosition() anropas. |
| [getOperators](#getOperators--) | Hämtar en samling operatorer som representerar elementet. |
| [getParent](#getParent--) | Hämtar den aktuella {@link XFormPlacement} som elementet är placerat i. |
| [getPosition](#getPosition--) | Hämtar eller anger positionen i det aktuella koordinatrymmet. Om Parent #getParent/#setParent(XFormPlacement) inte är null har elementet xForm-koordinatrymd. |
| [getRectangle](#getRectangle--) | Hämtar den begränsande rektangeln för {@link GraphicElement}. |
| [getSourcePage](#getSourcePage--) | Hämtar sidan som det grafiska elementet extraheras från. |
| [remove](#remove--) | Tar bort det aktuella elementet från sidan. Om det finns många element att ta bort är det bättre att använda Page#deleteGraphics(GraphicElementCollection). |
| [saveToSvg](#saveToSvg--) | Konverterar elementet till en enda SVG-bild. |
| [saveToSvg](#saveToSvg-java.lang.String-) | Konverterar elementet till en enda SVG-bild. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Hämtar eller anger positionen i det aktuella koordinatrymmet. Om Parent #getParent/#setParent(XFormPlacement) inte är null har elementet xForm-koordinatrymd. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Lägger till aktuellt element på sidan. Om det finns många element att lägga till är det bättre att använda Page#addGraphics(GraphicElementCollection,Rectangle).

### dispose {#dispose--}
```
public final void dispose()
```

Frigör alla resurser som används av klassen {@link GraphicElement}.

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

Hämtar grafikelementets matris. Matrisen sätts när elementet skapas. Den ändras när SetPosition() anropas.

**Returns:**
Matrisinstans

### getOperators {#getOperators--}
```
public final List < Operator > getOperators()
```

Hämtar en samling operatorer som representerar elementet.

**Returns:**
Lista över Operator-instansier

### getParent {#getParent--}
```
public final XFormPlacement getParent()
```

Hämtar den aktuella {@link XFormPlacement} som elementet är placerat i.

**Returns:**
XFormPlacement-instans

### getPosition {#getPosition--}
```
public Point getPosition()
```

Hämtar eller anger positionen i det aktuella koordinatrymmet. Om Parent #getParent/#setParent(XFormPlacement) inte är null har elementet xForm-koordinatrymd.

**Returns:**
Point-instans

### getRectangle {#getRectangle--}
```
public abstract Rectangle getRectangle()
```

Hämtar den begränsande rektangeln för {@link GraphicElement}.

**Returns:**
Rektangelinstans

### getSourcePage {#getSourcePage--}
```
public final Page getSourcePage()
```

Hämtar sidan som det grafiska elementet extraheras från.

**Returns:**
Page-instans

### remove {#remove--}
```
public final void remove()
```

Tar bort det aktuella elementet från sidan. Om det finns många element att ta bort är det bättre att använda Page#deleteGraphics(GraphicElementCollection).

### saveToSvg {#saveToSvg--}
```
public final String saveToSvg()
```

Konverterar elementet till en enda SVG-bild.

**Returns:**
SVG-strängen.

### saveToSvg {#saveToSvg-java.lang.String-}
Konverterar elementet till en enda SVG-bild.

**Returns:**
SVG-strängen.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Hämtar eller anger positionen i det aktuella koordinatrymmet. Om Parent #getParent/#setParent(XFormPlacement) inte är null har elementet xForm-koordinatrymd.
