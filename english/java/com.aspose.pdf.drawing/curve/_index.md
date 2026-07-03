---
title: Curve
second_title: Aspose.PDF for Java API Reference
description: Represents bezier curve.
type: docs
weight: 30
url: /java/com.aspose.pdf.drawing/curve/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Curve, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Curve

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Curve extends Shape
```

Represents bezier curve.

## Constructors

| Constructor | Description |
| --- | --- |
| [Curve](#Curve--) | For Internal usage only |
| [Curve](#Curve-float:A-) | Initializes a new instance of the {@code Curve} class. |

## Methods

| Method | Description |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Checks if the item fits within the given container dimensions (inclusive). |
| [getPositionArray](#getPositionArray--) | Gets a float position array. |
| [setPositionArray](#setPositionArray-float:A-) | Sets a float position array. |

### Curve {#Curve--}
```
public Curve()
```

For Internal usage only

### Curve {#Curve-float:A-}
```
public Curve(float[] positionArray)
```

Initializes a new instance of the {@code Curve} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| positionArray |  | The position array of the control points of the curve.There should be four control points,so the length of the array should be eight. |

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

Gets a float position array.

**Returns:**
float[] array

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Sets a float position array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float[] array |
