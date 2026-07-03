---
title: Shape
second_title: Aspose.PDF for Java API Reference
description: Represents shape - the base graphics object.
type: docs
weight: 130
url: /java/com.aspose.pdf.drawing/shape/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public abstract class Shape extends Object implements IBoundsCheckableItem
```

Represents shape - the base graphics object.

## Constructors

| Constructor | Description |
| --- | --- |
| [Shape](#Shape--) |  |

## Methods

| Method | Description |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Checks if the item fits within the given container dimensions (inclusive). |
| [getGraphInfo](#getGraphInfo--) | Gets object that indicates the graph info,such as color, line width,etc. |
| [getText](#getText--) | Gets or sets a text for shape |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Sets object that indicates the graph info,such as color, line width,etc. |
| [setText](#setText-com.aspose.pdf.TextFragment-) | Gets or sets a text for shape |

### Shape {#Shape--}
```
public Shape()
```



### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Checks if the item fits within the given container dimensions (inclusive).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
True if fits; otherwise, false.

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Gets object that indicates the graph info,such as color, line width,etc.

**Returns:**
object that indicates the graph info.

### getText {#getText--}
```
public TextFragment getText()
```

Gets or sets a text for shape

**Returns:**
TextFragment object

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Sets object that indicates the graph info,such as color, line width,etc.

### setText {#setText-com.aspose.pdf.TextFragment-}
Gets or sets a text for shape
