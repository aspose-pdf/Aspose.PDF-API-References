---
title: XFormPlacement
linktitle: XFormPlacement
second_title: Aspose.PDF for Java API Reference
description: Represents XForm placement. If the XForm is displayed on the page more than 1 time, all XformPlacements associated with this XForm will have common graphical elements, but.
type: docs
weight: 70
url: /java/com.aspose.pdf.vector/xformplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.XFormPlacement, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.XFormPlacement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class XFormPlacement extends GraphicElement
```

Represents XForm placement. If the XForm is displayed on the page more than 1 time, all XformPlacements associated with this XForm will have common graphical elements, but different graphical states.

## Methods

| Method | Description |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Adds current element on the page. If there are many elements to add better use Page#addGraphics(GraphicElementCollection,Rectangle). |
| [getElements](#getElements--) | Gets graphic elements inside this XForm. |
| [getName](#getName--) | Gets name of the XForm. |
| [getRectangle](#getRectangle--) | Gets the bounding rectangle of the GraphicElement . |
| [getXForm](#getXForm--) | Gets XForm associated with this XFormPlacement. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Gets or sets the position in the current coordinate space. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Adds current element on the page. If there are many elements to add better use Page#addGraphics(GraphicElementCollection,Rectangle).

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Gets graphic elements inside this XForm.

**Returns:**
GraphicElementCollection instance

### getName {#getName--}
```
public final String getName()
```

Gets name of the XForm.

**Returns:**
String value

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Gets the bounding rectangle of the GraphicElement .

**Returns:**
Rectangle instance

### getXForm {#getXForm--}
```
public final XForm getXForm()
```

Gets XForm associated with this XFormPlacement.

**Returns:**
XForm instance

### setPosition {#setPosition-com.aspose.pdf.Point-}
Gets or sets the position in the current coordinate space.
