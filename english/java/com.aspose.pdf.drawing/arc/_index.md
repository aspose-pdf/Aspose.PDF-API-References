---
title: Arc
linktitle: Arc
second_title: Aspose.PDF for Java API Reference
description: Represents arc.
type: docs
weight: 10
url: /java/com.aspose.pdf.drawing/arc/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Arc, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Arc

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Arc extends Shape
```

Represents arc.

## Constructors

| Constructor | Description |
| --- | --- |
| [Arc](#Arc--) | For Internal usage only |
| [Arc](#Arc-double-double-double-double-double-) | Initializes a new instance of the {@code Arc} class. |

## Methods

| Method | Description |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Checks if the item fits within the given container dimensions (inclusive). |
| [getAlpha](#getAlpha--) | Gets float value that indicates the beginning angle degree of the arc. |
| [getBeta](#getBeta--) | Gets float value that indicates the ending angle degree of the arc. |
| [getPosX](#getPosX--) | Gets float value that indicates the x-coordinate of the center of the arc. |
| [getPosY](#getPosY--) | Gets float value that indicates the y-coordinate of the center of the arc. |
| [getRadius](#getRadius--) | Gets float value that indicates the radius of the arc. |
| [setAlpha](#setAlpha-double-) | Sets float value that indicates the beginning angle degree of the arc. |
| [setBeta](#setBeta-double-) | Sets float value that indicates the ending angle degree of the arc. |
| [setPosX](#setPosX-double-) | Sets float value that indicates the x-coordinate of the center of the arc. |
| [setPosY](#setPosY-double-) | Sets float value that indicates the y-coordinate of the center of the arc. |
| [setRadius](#setRadius-double-) | Sets float value that indicates the radius of the arc. |

### Arc {#Arc--}
```
public Arc()
```

For Internal usage only

### Arc {#Arc-double-double-double-double-double-}
```
public Arc(double posX, double posY, double radius, double alpha, double beta)
```

Initializes a new instance of the {@code Arc} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| posX |  | The x-coordinate of the center point of the arc. |
| posY |  | The y-coordinate of the center point of the arc. |
| radius |  | The radius value of the arc. |
| alpha |  | The beginning angle value of the arc. |
| beta |  | The end angle value of the arc. |

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

### getAlpha {#getAlpha--}
```
public double getAlpha()
```

Gets float value that indicates the beginning angle degree of the arc.

**Returns:**
alpha value.

### getBeta {#getBeta--}
```
public double getBeta()
```

Gets float value that indicates the ending angle degree of the arc.

**Returns:**
beta value

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

Gets float value that indicates the radius of the arc.

**Returns:**
value that indicates the radius of the arc.

### setAlpha {#setAlpha-double-}
```
public void setAlpha(double value)
```

Sets float value that indicates the beginning angle degree of the arc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | alpha value. |

### setBeta {#setBeta-double-}
```
public void setBeta(double value)
```

Sets float value that indicates the ending angle degree of the arc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | beta value |

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

Sets float value that indicates the radius of the arc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | that indicates the radius of the arc. |
