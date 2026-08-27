---
title: "GraphicElement"
linktitle: "GraphicElement"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Basisklasse für ein Grafikobjekt auf der Seite bereit."
type: docs
weight: 10
url: /de/java/com.aspose.pdf.vector/graphicelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public abstract class GraphicElement extends Object implements com.aspose.ms.System.IDisposable
```

Stellt die Basisklasse für ein Grafikobjekt auf der Seite bereit.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Fügt das aktuelle Element auf der Seite hinzu. Wenn viele Elemente hinzuzufügen sind, verwenden Sie besser Page#addGraphics(GraphicElementCollection,Rectangle). |
| [dispose](#dispose--) | Gibt alle von der {@link GraphicElement}-Klasse verwendeten Ressourcen frei. |
| [getMatrix](#getMatrix--) | Gibt die Matrix des Grafikelements zurück. Die Matrix wird beim Erstellen des Elements festgelegt. Sie ändert sich, wenn SetPosition() aufgerufen wird. |
| [getOperators](#getOperators--) | Gibt eine Sammlung von Operatoren zurück, die das Element darstellen. |
| [getParent](#getParent--) | Gibt die aktuelle {@link XFormPlacement} zurück, in der sich das Element befindet. |
| [getPosition](#getPosition--) | Liest oder setzt die Position im aktuellen Koordinatenraum. Wenn Parent #getParent/#setParent(XFormPlacement) nicht null ist, hat das Element einen xForm-Koordinatenraum. |
| [getRectangle](#getRectangle--) | Gibt das Begrenzungsrechteck des {@link GraphicElement} zurück. |
| [getSourcePage](#getSourcePage--) | Gibt die Seite zurück, von der das Grafikelement extrahiert wird. |
| [remove](#remove--) | Entfernt das aktuelle Element von der Seite. Wenn viele Elemente zu entfernen sind, sollte besser Page#deleteGraphics(GraphicElementCollection) verwendet werden. |
| [saveToSvg](#saveToSvg--) | Konvertiert das Element in ein einzelnes SVG-Bild. |
| [saveToSvg](#saveToSvg-java.lang.String-) | Konvertiert das Element in ein einzelnes SVG-Bild. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Liest oder setzt die Position im aktuellen Koordinatenraum. Wenn Parent #getParent/#setParent(XFormPlacement) nicht null ist, hat das Element einen xForm-Koordinatenraum. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Fügt das aktuelle Element auf der Seite hinzu. Wenn viele Elemente hinzuzufügen sind, verwenden Sie besser Page#addGraphics(GraphicElementCollection,Rectangle).

### dispose {#dispose--}
```
public final void dispose()
```

Gibt alle von der {@link GraphicElement}-Klasse verwendeten Ressourcen frei.

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

Gibt die Matrix des Grafikelements zurück. Die Matrix wird beim Erstellen des Elements festgelegt. Sie ändert sich, wenn SetPosition() aufgerufen wird.

**Returns:**
Matrixinstanz

### getOperators {#getOperators--}
```
public final List < Operator > getOperators()
```

Gibt eine Sammlung von Operatoren zurück, die das Element darstellen.

**Returns:**
Liste von Operator-Instanzen

### getParent {#getParent--}
```
public final XFormPlacement getParent()
```

Gibt die aktuelle {@link XFormPlacement} zurück, in der sich das Element befindet.

**Returns:**
XFormPlacement-Instanz

### getPosition {#getPosition--}
```
public Point getPosition()
```

Liest oder setzt die Position im aktuellen Koordinatenraum. Wenn Parent #getParent/#setParent(XFormPlacement) nicht null ist, hat das Element einen xForm-Koordinatenraum.

**Returns:**
Point-Instanz

### getRectangle {#getRectangle--}
```
public abstract Rectangle getRectangle()
```

Gibt das Begrenzungsrechteck des {@link GraphicElement} zurück.

**Returns:**
Rechteck-Instanz

### getSourcePage {#getSourcePage--}
```
public final Page getSourcePage()
```

Gibt die Seite zurück, von der das Grafikelement extrahiert wird.

**Returns:**
Seiteninstanz

### remove {#remove--}
```
public final void remove()
```

Entfernt das aktuelle Element von der Seite. Wenn viele Elemente zu entfernen sind, sollte besser Page#deleteGraphics(GraphicElementCollection) verwendet werden.

### saveToSvg {#saveToSvg--}
```
public final String saveToSvg()
```

Konvertiert das Element in ein einzelnes SVG-Bild.

**Returns:**
Die SVG-Zeichenkette.

### saveToSvg {#saveToSvg-java.lang.String-}
Konvertiert das Element in ein einzelnes SVG-Bild.

**Returns:**
Die SVG-Zeichenkette.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Liest oder setzt die Position im aktuellen Koordinatenraum. Wenn Parent #getParent/#setParent(XFormPlacement) nicht null ist, hat das Element einen xForm-Koordinatenraum.
