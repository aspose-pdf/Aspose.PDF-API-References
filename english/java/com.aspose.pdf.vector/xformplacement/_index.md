---
title: XFormPlacement
second_title: Aspose.PDF for Java API Reference
description: Represents XForm placement.
type: docs
weight: 15
url: /java/com.aspose.pdf.vector/xformplacement/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.vector.GraphicElement](../../com.aspose.pdf.vector/graphicelement)
```
public final class XFormPlacement extends GraphicElement
```

Represents XForm placement. If the XForm is displayed on the page more than 1 time, all XformPlacements associated with this XForm will have common graphical elements, but different graphical states.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets name of the XForm. |
| [getXForm()](#getXForm--) | Gets XForm associated with this XFormPlacement. |
| [getElements()](#getElements--) | Gets graphic elements inside this XForm. |
| [getRectangle()](#getRectangle--) |  |
| [setPosition(Point value)](#setPosition-com.aspose.pdf.Point-) |  |
| [addOnPage(Page destination)](#addOnPage-com.aspose.pdf.Page-) | Adds current element on the page. |
### getName() {#getName--}
```
public final String getName()
```


Gets name of the XForm.

**Returns:**
java.lang.String - String value
### getXForm() {#getXForm--}
```
public final XForm getXForm()
```


Gets XForm associated with this XFormPlacement.

**Returns:**
[XForm](../../com.aspose.pdf/xform) - XForm instance
### getElements() {#getElements--}
```
public final GraphicElementCollection getElements()
```


Gets graphic elements inside this XForm.

**Returns:**
[GraphicElementCollection](../../com.aspose.pdf.vector/graphicelementcollection) - GraphicElementCollection instance
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Gets the bounding rectangle of the [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement).

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### setPosition(Point value) {#setPosition-com.aspose.pdf.Point-}
```
public void setPosition(Point value)
```


Gets or sets the position in the current coordinate space. If  Parent (\#getParent\#getParent) is not  null  then the element have xForm coordinate space.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.pdf/point) |  |

### addOnPage(Page destination) {#addOnPage-com.aspose.pdf.Page-}
```
public void addOnPage(Page destination)
```


Adds current element on the page. If there are many elements to add better use Page\#addGraphics(GraphicElementCollection,Rectangle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destination | [Page](../../com.aspose.pdf/page) | Destination page |

