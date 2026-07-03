---
title: Line
second_title: Aspose.PDF for Java API Reference
description: Represents line.
type: docs
weight: 90
url: /java/com.aspose.pdf.drawing/line/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Line, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Line

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Line extends Shape
```

Represents line.

## Constructors

| Constructor | Description |
| --- | --- |
| [Line](#Line--) | For Internal usage only |
| [Line](#Line-float:A-) | Initializes a new instance of the {@code Line} class. |

## Methods

| Method | Description |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Checks if the item fits within the given container dimensions (inclusive). |
| [getPositionArray](#getPositionArray--) | Gets object that indicates the position array.The array is composed by coordinates of each control point of the line. directly. |
| [setPositionArray](#setPositionArray-float:A-) | Sets object that indicates the position array.The array is composed by coordinates of each control point of the line. directly. |

### Line {#Line--}
```
public Line()
```

For Internal usage only

### Line {#Line-float:A-}
```
public Line(float[] positionArray)
```

Initializes a new instance of the {@code Line} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| positionArray |  | The line position array. |

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

### getPositionArray {#getPositionArray--}
```
public float[] getPositionArray()
```

Gets object that indicates the position array.The array is composed by coordinates of each control point of the line. directly.

**Returns:**
that indicates the position array.

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Sets object that indicates the position array.The array is composed by coordinates of each control point of the line. directly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | that indicates the position array. |
