---
title: GraphicElement
second_title: Aspose.PDF for Java API Reference
description: Represents base class for graphics object on the page.
type: docs
weight: 10
url: /java/com.aspose.pdf.vector/graphicelement/
---
**Inheritance:**
java.lang.Object
```
public abstract class GraphicElement
```

Represents base class for graphics object on the page.
## Methods

| Method | Description |
| --- | --- |
| [getRectangle()](#getRectangle--) | Gets the bounding rectangle of the [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement). |
| [getPosition()](#getPosition--) | Gets or sets the position in the current coordinate space. |
| [setPosition(Point value)](#setPosition-com.aspose.pdf.Point-) | Gets or sets the position in the current coordinate space. |
| [remove()](#remove--) | Removes current element from the page. |
| [addOnPage(Page destination)](#addOnPage-com.aspose.pdf.Page-) | Adds current element on the page. |
| [getParent()](#getParent--) | Gets the current [XFormPlacement](../../com.aspose.pdf.vector/xformplacement) in which the element is located. |
| [getOperators()](#getOperators--) | Gets a collection of operators representing the element. |
### getRectangle() {#getRectangle--}
```
public abstract Rectangle getRectangle()
```


Gets the bounding rectangle of the [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement).

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle instance
### getPosition() {#getPosition--}
```
public Point getPosition()
```


Gets or sets the position in the current coordinate space. If @link \#getParent is not null then the element have xForm coordinate space.

**Returns:**
[Point](../../com.aspose.pdf/point) - Point instance
### setPosition(Point value) {#setPosition-com.aspose.pdf.Point-}
```
public void setPosition(Point value)
```


Gets or sets the position in the current coordinate space. If  Parent (\#getParent\#getParent) is not  null  then the element have xForm coordinate space.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.pdf/point) | Point instance |

### remove() {#remove--}
```
public final void remove()
```


Removes current element from the page. If there are many elements to remove better use Page\#deleteGraphics(GraphicElementCollection).

### addOnPage(Page destination) {#addOnPage-com.aspose.pdf.Page-}
```
public void addOnPage(Page destination)
```


Adds current element on the page. If there are many elements to add better use Page\#addGraphics(GraphicElementCollection,Rectangle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destination | [Page](../../com.aspose.pdf/page) | Destination page |

### getParent() {#getParent--}
```
public final XFormPlacement getParent()
```


Gets the current [XFormPlacement](../../com.aspose.pdf.vector/xformplacement) in which the element is located.

**Returns:**
[XFormPlacement](../../com.aspose.pdf.vector/xformplacement) - XFormPlacement instance
### getOperators() {#getOperators--}
```
public final List<Operator> getOperators()
```


Gets a collection of operators representing the element.

**Returns:**
java.util.List<com.aspose.pdf.Operator> - List of Operator instances
