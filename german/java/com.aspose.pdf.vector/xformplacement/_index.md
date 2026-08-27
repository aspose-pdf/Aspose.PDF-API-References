---
title: "XFormPlacement"
linktitle: "XFormPlacement"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Platzierung des XForm dar. Wenn das XForm mehr als einmal auf der Seite angezeigt wird, haben alle mit diesem XForm verbundenen XformPlacements gemeinsame grafische Elemente, jedoch."
type: docs
weight: 70
url: /de/java/com.aspose.pdf.vector/xformplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.XFormPlacement, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.XFormPlacement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class XFormPlacement extends GraphicElement
```

Stellt die Platzierung von XForm dar. Wenn das XForm mehr als einmal auf der Seite angezeigt wird, haben alle mit diesem XForm verbundenen XformPlacements gemeinsame grafische Elemente, jedoch unterschiedliche grafische Zustände.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Fügt das aktuelle Element auf der Seite hinzu. Wenn viele Elemente hinzuzufügen sind, verwenden Sie besser Page#addGraphics(GraphicElementCollection,Rectangle). |
| [getElements](#getElements--) | Liefert die grafischen Elemente innerhalb dieses XForm. |
| [getName](#getName--) | Liefert den Namen des XForm. |
| [getRectangle](#getRectangle--) | Liefert das begrenzende Rechteck des GraphicElement. |
| [getXForm](#getXForm--) | Liefert das XForm, das mit diesem XFormPlacement verknüpft ist. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Liefert oder setzt die Position im aktuellen Koordinatenraum. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Fügt das aktuelle Element auf der Seite hinzu. Wenn viele Elemente hinzuzufügen sind, verwenden Sie besser Page#addGraphics(GraphicElementCollection,Rectangle).

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Liefert die grafischen Elemente innerhalb dieses XForm.

**Returns:**
GraphicElementCollection-Instanz

### getName {#getName--}
```
public final String getName()
```

Liefert den Namen des XForm.

**Returns:**
String Wert

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Liefert das begrenzende Rechteck des GraphicElement.

**Returns:**
Rechteck-Instanz

### getXForm {#getXForm--}
```
public final XForm getXForm()
```

Liefert das XForm, das mit diesem XFormPlacement verknüpft ist.

**Returns:**
XForm-Instanz

### setPosition {#setPosition-com.aspose.pdf.Point-}
Liefert oder setzt die Position im aktuellen Koordinatenraum.
