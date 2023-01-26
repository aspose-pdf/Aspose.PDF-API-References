---
title: Graph
second_title: Aspose.PDF for Java API Reference
description: Represents graph - graphics generator paragraph.
type: docs
weight: 16
url: /java/com.aspose.pdf.drawing/graph/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public final class Graph extends BaseParagraph
```

Represents graph - graphics generator paragraph.
## Constructors

| Constructor | Description |
| --- | --- |
| [Graph()](#Graph--) | For Internal usage only |
| [Graph(float width, float height)](#Graph-float-float-) | Initializes a new instance of the  Graph  class. |
## Methods

| Method | Description |
| --- | --- |
| [getGraphInfo()](#getGraphInfo--) | Gets a  GraphInfo  object that indicates the graph info,such as color, line width,etc. |
| [setGraphInfo(GraphInfo value)](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Gets or sets a  GraphInfo  object that indicates the graph info,such as color, line width,etc. |
| [getBorder()](#getBorder--) | Gets the border. |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | Sets the border. |
| [isChangePosition()](#isChangePosition--) | Gets change current position after process paragraph.(default true) |
| [setChangePosition(boolean value)](#setChangePosition-boolean-) | Sets change current position after process paragraph.(default true) |
| [getLeft()](#getLeft--) | Gets table left coordinate. |
| [setLeft(double value)](#setLeft-double-) | Sets table left coordinate. |
| [getTop()](#getTop--) | Gets the table top coordinate. |
| [setTop(double value)](#setTop-double-) | Sets the table top coordinate. |
| [getShapes()](#getShapes--) | Gets a  Shapes  collection that indicates all shapes in the graph. |
| [setShapes(List<Shape> value)](#setShapes-java.util.List-com.aspose.pdf.drawing.Shape--) | Sets a  Shapes  collection that indicates all shapes in the graph. |
| [getTitle()](#getTitle--) | Gets string value that indicates the title of the graph. |
| [setTitle(TextFragment value)](#setTitle-com.aspose.pdf.TextFragment-) | Sets string value that indicates the title of the graph. |
| [getWidth()](#getWidth--) | Gets float value that indicates the graph width. |
| [setWidth(double value)](#setWidth-double-) | Sets float value that indicates the graph width. |
| [getHeight()](#getHeight--) | Gets float value that indicates the graph height. |
| [setHeight(double value)](#setHeight-double-) | Sets float value that indicates the graph height. |
| [deepClone()](#deepClone--) | Clone the graph. |
### Graph() {#Graph--}
```
public Graph()
```


For Internal usage only

### Graph(float width, float height) {#Graph-float-float-}
```
public Graph(float width, float height)
```


Initializes a new instance of the  Graph  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | The width of the graph. |
| height | float | The height of the graph. |

### getGraphInfo() {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```


Gets a  GraphInfo  object that indicates the graph info,such as color, line width,etc.

**Returns:**
[GraphInfo](../../com.aspose.pdf/graphinfo) - GraphInfo object
### setGraphInfo(GraphInfo value) {#setGraphInfo-com.aspose.pdf.GraphInfo-}
```
public void setGraphInfo(GraphInfo value)
```


Gets or sets a  GraphInfo  object that indicates the graph info,such as color, line width,etc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [GraphInfo](../../com.aspose.pdf/graphinfo) | GraphInfo object |

### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```


Gets the border.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo element
### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```


Sets the border.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo element |

### isChangePosition() {#isChangePosition--}
```
public boolean isChangePosition()
```


Gets change current position after process paragraph.(default true)

**Returns:**
boolean - boolean value
### setChangePosition(boolean value) {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```


Sets change current position after process paragraph.(default true)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getLeft() {#getLeft--}
```
public double getLeft()
```


Gets table left coordinate.

**Returns:**
double - table left coordinate.
### setLeft(double value) {#setLeft-double-}
```
public void setLeft(double value)
```


Sets table left coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | table left coordinate. |

### getTop() {#getTop--}
```
public double getTop()
```


Gets the table top coordinate.

**Returns:**
double - the table top coordinate.
### setTop(double value) {#setTop-double-}
```
public void setTop(double value)
```


Sets the table top coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | the table top coordinate. |

### getShapes() {#getShapes--}
```
public List<Shape> getShapes()
```


Gets a  Shapes  collection that indicates all shapes in the graph.

**Returns:**
java.util.List<com.aspose.pdf.drawing.Shape> - List of Shape elements
### setShapes(List<Shape> value) {#setShapes-java.util.List-com.aspose.pdf.drawing.Shape--}
```
public void setShapes(List<Shape> value)
```


Sets a  Shapes  collection that indicates all shapes in the graph.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.aspose.pdf.drawing.Shape> | List of Shape elements |

### getTitle() {#getTitle--}
```
public TextFragment getTitle()
```


Gets string value that indicates the title of the graph.

**Returns:**
[TextFragment](../../com.aspose.pdf/textfragment) - title of the graph.
### setTitle(TextFragment value) {#setTitle-com.aspose.pdf.TextFragment-}
```
public void setTitle(TextFragment value)
```


Sets string value that indicates the title of the graph.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TextFragment](../../com.aspose.pdf/textfragment) | title of the graph. |

### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets float value that indicates the graph width. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphWidth="10cm" or GraphWidth="5inch".

**Returns:**
double - float value that indicates the graph width.
### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets float value that indicates the graph width. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphWidth="10cm" or GraphWidth="5inch".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | float value that indicates the graph width. |

### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets float value that indicates the graph height. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphHeight="10cm" or GraphHeight="5inch".

**Returns:**
double - value that indicates the graph height.
### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Sets float value that indicates the graph height. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphHeight="10cm" or GraphHeight="5inch".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | that indicates the graph height. |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone the graph.

**Returns:**
java.lang.Object - The cloned object
