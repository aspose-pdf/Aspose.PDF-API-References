---
title: Rectangle
second_title: Aspose.PDF for Java API Reference
description: Represents rectangle.
type: docs
weight: 120
url: /java/com.aspose.pdf.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Rectangle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Rectangle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Rectangle extends Shape
```

Represents rectangle.

## Constructors

| Constructor | Description |
| --- | --- |
| [Rectangle](#Rectangle--) | Constructor |
| [Rectangle](#Rectangle-float-float-float-float-) | Initializes a new instance of the {@code Rectangle} class. |

## Methods

| Method | Description |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Checks if the item fits within the given container dimensions (inclusive). |
| [getBottom](#getBottom--) | Gets float value that indicates the bottom position of the rectangle. |
| [getHeight](#getHeight--) | Gets float value that indicates the height of the rectangle. |
| [getLeft](#getLeft--) | Gets float value that indicates the left position of the rectangle. |
| [getRoundedCornerRadius](#getRoundedCornerRadius--) | Gets float value that indicates the radius of rectangle corners. |
| [getWidth](#getWidth--) | Gets float value that indicates the width of the rectangle. |
| [setBottom](#setBottom-double-) | Sets float value that indicates the bottom position of the rectangle. |
| [setHeight](#setHeight-double-) | Sets float value that indicates the height of the rectangle. |
| [setLeft](#setLeft-double-) | Sets float value that indicates the left position of the rectangle. |
| [setRoundedCornerRadius](#setRoundedCornerRadius-double-) | Sets float value that indicates the radius of rectangle corners. |
| [setWidth](#setWidth-double-) | Sets float value that indicates the width of the rectangle. |

### Rectangle {#Rectangle--}
```
public Rectangle()
```

Constructor

### Rectangle {#Rectangle-float-float-float-float-}
```
public Rectangle(float left, float bottom, float width, float height)
```

Initializes a new instance of the {@code Rectangle} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left |  | The left position of the rectangle. |
| bottom |  | The bottom position of the rectangle. |
| width |  | The width of the rectangle. |
| height |  | The height of the rectangle. |

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

### getBottom {#getBottom--}
```
public double getBottom()
```

Gets float value that indicates the bottom position of the rectangle.

**Returns:**
value that indicates the bottom position of the rectangle.

### getHeight {#getHeight--}
```
public double getHeight()
```

Gets float value that indicates the height of the rectangle.

**Returns:**
value that indicates the height of the rectangle.

### getLeft {#getLeft--}
```
public double getLeft()
```

Gets float value that indicates the left position of the rectangle.

**Returns:**
float value that indicates the left position of the rectangle.

### getRoundedCornerRadius {#getRoundedCornerRadius--}
```
public double getRoundedCornerRadius()
```

Gets float value that indicates the radius of rectangle corners.

**Returns:**
value that indicates the radius of rectangle corners.

### getWidth {#getWidth--}
```
public double getWidth()
```

Gets float value that indicates the width of the rectangle.

**Returns:**
value that indicates the width of the rectangle.

### setBottom {#setBottom-double-}
```
public void setBottom(double value)
```

Sets float value that indicates the bottom position of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | value that indicates the bottom position of the rectangle. |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Sets float value that indicates the height of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | value that indicates the height of the rectangle. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Sets float value that indicates the left position of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value that indicates the left position of the rectangle. |

### setRoundedCornerRadius {#setRoundedCornerRadius-double-}
```
public void setRoundedCornerRadius(double value)
```

Sets float value that indicates the radius of rectangle corners.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | that indicates the radius of rectangle corners. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Sets float value that indicates the width of the rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | that indicates the width of the rectangle. |
