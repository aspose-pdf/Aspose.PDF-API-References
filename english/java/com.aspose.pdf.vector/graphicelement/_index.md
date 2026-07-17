---
title: GraphicElement
linktitle: GraphicElement
second_title: Aspose.PDF for Java API Reference
description: Represents base class for graphics object on the page.
type: docs
weight: 10
url: /java/com.aspose.pdf.vector/graphicelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public abstract class GraphicElement extends Object implements com.aspose.ms.System.IDisposable
```

Represents base class for graphics object on the page.

## Methods

| Method | Description |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Adds current element on the page. If there are many elements to add better use Page#addGraphics(GraphicElementCollection,Rectangle). |
| [dispose](#dispose--) | Releases all resources used by the {@link GraphicElement} class. |
| [getMatrix](#getMatrix--) | Gets graphic element matrix. The matrix sets when element is created. It changes when SetPosition() is called. |
| [getOperators](#getOperators--) | Gets a collection of operators representing the element. |
| [getParent](#getParent--) | Gets the current {@link XFormPlacement} in which the element is located. |
| [getPosition](#getPosition--) | Gets or sets the position in the current coordinate space. If Parent #getParent/#setParent(XFormPlacement) is not null then the element have xForm coordinate space. |
| [getRectangle](#getRectangle--) | Gets the bounding rectangle of the {@link GraphicElement}. |
| [getSourcePage](#getSourcePage--) | Gets the page from which the graphic element is extracted. |
| [remove](#remove--) | Removes current element from the page. If there are many elements to remove better use Page#deleteGraphics(GraphicElementCollection). |
| [saveToSvg](#saveToSvg--) | Converts the element into a single SVG image. |
| [saveToSvg](#saveToSvg-java.lang.String-) | Converts the element into a single SVG image. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Gets or sets the position in the current coordinate space. If Parent #getParent/#setParent(XFormPlacement) is not null then the element have xForm coordinate space. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Adds current element on the page. If there are many elements to add better use Page#addGraphics(GraphicElementCollection,Rectangle).

### dispose {#dispose--}
```
public final void dispose()
```

Releases all resources used by the {@link GraphicElement} class.

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

Gets graphic element matrix. The matrix sets when element is created. It changes when SetPosition() is called.

**Returns:**
Matrix instance

### getOperators {#getOperators--}
```
public final List < Operator > getOperators()
```

Gets a collection of operators representing the element.

**Returns:**
List of Operator instances

### getParent {#getParent--}
```
public final XFormPlacement getParent()
```

Gets the current {@link XFormPlacement} in which the element is located.

**Returns:**
XFormPlacement instance

### getPosition {#getPosition--}
```
public Point getPosition()
```

Gets or sets the position in the current coordinate space. If Parent #getParent/#setParent(XFormPlacement) is not null then the element have xForm coordinate space.

**Returns:**
Point instance

### getRectangle {#getRectangle--}
```
public abstract Rectangle getRectangle()
```

Gets the bounding rectangle of the {@link GraphicElement}.

**Returns:**
Rectangle instance

### getSourcePage {#getSourcePage--}
```
public final Page getSourcePage()
```

Gets the page from which the graphic element is extracted.

**Returns:**
Page instance

### remove {#remove--}
```
public final void remove()
```

Removes current element from the page. If there are many elements to remove better use Page#deleteGraphics(GraphicElementCollection).

### saveToSvg {#saveToSvg--}
```
public final String saveToSvg()
```

Converts the element into a single SVG image.

**Returns:**
The SVG-string.

### saveToSvg {#saveToSvg-java.lang.String-}
Converts the element into a single SVG image.

**Returns:**
The SVG-string.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Gets or sets the position in the current coordinate space. If Parent #getParent/#setParent(XFormPlacement) is not null then the element have xForm coordinate space.
