---
title: "XFormPlacement"
linktitle: "XFormPlacement"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar XForm-placering. Om XForm visas på sidan mer än 1 gång, kommer alla XformPlacements associerade med detta XForm att ha gemensamma grafiska element, men."
type: docs
weight: 70
url: /sv/java/com.aspose.pdf.vector/xformplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.XFormPlacement, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.XFormPlacement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class XFormPlacement extends GraphicElement
```

Representerar XForm-placering. Om XForm visas på sidan mer än en gång, kommer alla XformPlacements som är associerade med detta XForm att ha gemensamma grafiska element, men olika grafiska tillstånd.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Lägger till aktuellt element på sidan. Om det finns många element att lägga till är det bättre att använda Page#addGraphics(GraphicElementCollection,Rectangle). |
| [getElements](#getElements--) | Hämtar grafiska element inuti detta XForm. |
| [getName](#getName--) | Hämtar namnet på XForm. |
| [getRectangle](#getRectangle--) | Hämtar den omgivande rektangeln för GraphicElement. |
| [getXForm](#getXForm--) | Hämtar XForm som är associerad med detta XFormPlacement. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Hämtar eller anger positionen i det aktuella koordinatrymmet. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Lägger till aktuellt element på sidan. Om det finns många element att lägga till är det bättre att använda Page#addGraphics(GraphicElementCollection,Rectangle).

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Hämtar grafiska element inuti detta XForm.

**Returns:**
GraphicElementCollection-instans

### getName {#getName--}
```
public final String getName()
```

Hämtar namnet på XForm.

**Returns:**
String värde

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Hämtar den omgivande rektangeln för GraphicElement.

**Returns:**
Rektangelinstans

### getXForm {#getXForm--}
```
public final XForm getXForm()
```

Hämtar XForm som är associerad med detta XFormPlacement.

**Returns:**
XForm-instans

### setPosition {#setPosition-com.aspose.pdf.Point-}
Hämtar eller anger positionen i det aktuella koordinatrymmet.
