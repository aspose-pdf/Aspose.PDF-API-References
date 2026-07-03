---
title: Graph
second_title: Aspose.PDF for Java API Reference
description: Represents graph - graphics generator paragraph.
type: docs
weight: 70
url: /java/com.aspose.pdf.drawing/graph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.drawing.Graph, com.aspose.pdf.BaseParagraph, com.aspose.pdf.drawing.Graph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Graph extends BaseParagraph
```

Represents graph - graphics generator paragraph.

## Constructors

| Constructor | Description |
| --- | --- |
| [Graph](#Graph--) | For Internal usage only |
| [Graph](#Graph-double-double-) | Initializes a new instance of the {@link Graph} class. |
| [Graph](#Graph-float-float-) | Initializes a new instance of the {@code Graph} class. |

## Methods

| Method | Description |
| --- | --- |
| [deepClone](#deepClone--) | Clone the graph. |
| [getBorder](#getBorder--) | Gets the border. |
| [getGraphInfo](#getGraphInfo--) | Gets a {@code GraphInfo} object that indicates the graph info,such as color, line width,etc. |
| [getHeight](#getHeight--) | Gets float value that indicates the graph height. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphHeight="10cm" or GraphHeight="5inch". |
| [getLeft](#getLeft--) | Gets table left coordinate. |
| [getShapes](#getShapes--) | Gets a collection that indicates all shapes in the graph. |
| [getTitle](#getTitle--) | Gets string value that indicates the title of the graph. |
| [getTop](#getTop--) | Gets the table top coordinate. |
| [getWidth](#getWidth--) | Gets float value that indicates the graph width. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphWidth="10cm" or GraphWidth="5inch". |
| [isChangePosition](#isChangePosition--) | Gets change current position after process paragraph.(default true) |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Sets the border. |
| [setChangePosition](#setChangePosition-boolean-) | Sets change current position after process paragraph.(default true) |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Gets or sets a {@code GraphInfo} object that indicates the graph info,such as color, line width,etc. |
| [setHeight](#setHeight-double-) | Sets float value that indicates the graph height. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphHeight="10cm" or GraphHeight="5inch". |
| [setLeft](#setLeft-double-) | Sets table left coordinate. |
| [setShapes](#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-) | Sets a collection that indicates all shapes in the graph. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Sets string value that indicates the title of the graph. |
| [setTop](#setTop-double-) | Sets the table top coordinate. |
| [setWidth](#setWidth-double-) | Sets float value that indicates the graph width. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphWidth="10cm" or GraphWidth="5inch". |

### Graph {#Graph--}
```
public Graph()
```

For Internal usage only

### Graph {#Graph-double-double-}
```
public Graph(double width, double height)
```

Initializes a new instance of the {@link Graph} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | The width of the graph. |
| height |  | The height of the graph. |

### Graph {#Graph-float-float-}
```
@Deprecated public Graph(float width, float height)
```

Initializes a new instance of the {@code Graph} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | The width of the graph. |
| height |  | The height of the graph. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone the graph.

**Returns:**
The cloned object

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Gets the border.

**Returns:**
BorderInfo element

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Gets a {@code GraphInfo} object that indicates the graph info,such as color, line width,etc.

**Returns:**
GraphInfo object

### getHeight {#getHeight--}
```
public double getHeight()
```

Gets float value that indicates the graph height. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphHeight="10cm" or GraphHeight="5inch".

**Returns:**
value that indicates the graph height.

### getLeft {#getLeft--}
```
public double getLeft()
```

Gets table left coordinate.

**Returns:**
table left coordinate.

### getShapes {#getShapes--}
```
public final BoundsCheckableList < Shape > getShapes()
```

Gets a collection that indicates all shapes in the graph.

**Returns:**
BoundsCheckableList of Shapes.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Gets string value that indicates the title of the graph.

**Returns:**
title of the graph.

### getTop {#getTop--}
```
public double getTop()
```

Gets the table top coordinate.

**Returns:**
the table top coordinate.

### getWidth {#getWidth--}
```
public double getWidth()
```

Gets float value that indicates the graph width. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphWidth="10cm" or GraphWidth="5inch".

**Returns:**
float value that indicates the graph width.

### isChangePosition {#isChangePosition--}
```
public boolean isChangePosition()
```

Gets change current position after process paragraph.(default true)

**Returns:**
boolean value

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Sets the border.

### setChangePosition {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```

Sets change current position after process paragraph.(default true)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Gets or sets a {@code GraphInfo} object that indicates the graph info,such as color, line width,etc.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Sets float value that indicates the graph height. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphHeight="10cm" or GraphHeight="5inch".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | that indicates the graph height. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Sets table left coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | table left coordinate. |

### setShapes {#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-}
Sets a collection that indicates all shapes in the graph.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Sets string value that indicates the title of the graph.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Sets the table top coordinate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | the table top coordinate. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Sets float value that indicates the graph width. The unit is point. In XML,the default unit is point,but cm and inch are also supported. For example,GraphWidth="10cm" or GraphWidth="5inch".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value that indicates the graph width. |
