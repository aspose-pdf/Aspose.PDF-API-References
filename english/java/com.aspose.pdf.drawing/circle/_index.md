---
title: Circle
linktitle: Circle
second_title: Aspose.PDF for Java API Reference
description: Represents circle.
type: docs
weight: 20
url: /java/com.aspose.pdf.drawing/circle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Circle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Circle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Circle extends Shape
```

Represents circle.

## Constructors

| Constructor | Description |
| --- | --- |
| [Circle](#Circle--) | For Internal usage only |
| [Circle](#Circle-float-float-float-) | Initializes a new instance of the {@code Circle} class. |

## Methods

| Method | Description |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Checks if the item fits within the given container dimensions (inclusive). |
| [getPosX](#getPosX--) | Gets float value that indicates the x-coordinate of the center of the arc. |
| [getPosY](#getPosY--) | Gets float value that indicates the y-coordinate of the center of the arc. |
| [getRadius](#getRadius--) | Gets float value that indicates the radius of the circle. |
| [setPosX](#setPosX-double-) | Sets float value that indicates the x-coordinate of the center of the arc. |
| [setPosY](#setPosY-double-) | Sets float value that indicates the y-coordinate of the center of the arc. |
| [setRadius](#setRadius-double-) | Sets float value that indicates the radius of the circle. |

### Circle {#Circle--}
```
public Circle()
```

For Internal usage only

### Circle {#Circle-float-float-float-}
```
public Circle(float posX, float posY, float radius)
```

Initializes a new instance of the {@code Circle} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| posX |  | The x-coordinate of the center of the circle. |
| posY |  | The y-coordinate of the center of the circle. |
| radius |  | The radius of the circle. |

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

### getPosX {#getPosX--}
```
public double getPosX()
```

Gets float value that indicates the x-coordinate of the center of the arc.

**Returns:**
x-coordinate of the center of the arc.

### getPosY {#getPosY--}
```
public double getPosY()
```

Gets float value that indicates the y-coordinate of the center of the arc.

**Returns:**
y-coordinate of the center of the arc.

### getRadius {#getRadius--}
```
public double getRadius()
```

Gets float value that indicates the radius of the circle.

**Returns:**
value that indicates the radius of the circle.

### setPosX {#setPosX-double-}
```
public void setPosX(double value)
```

Sets float value that indicates the x-coordinate of the center of the arc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | x-coordinate of the center of the arc. |

### setPosY {#setPosY-double-}
```
public void setPosY(double value)
```

Sets float value that indicates the y-coordinate of the center of the arc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | y-coordinate of the center of the arc. |

### setRadius {#setRadius-double-}
```
public void setRadius(double value)
```

Sets float value that indicates the radius of the circle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | that indicates the radius of the circle. |
