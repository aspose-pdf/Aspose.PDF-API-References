---
title: "圆形"
linktitle: "圆形"
second_title: "Aspose.PDF for Java API 参考"
description: "表示圆。"
type: docs
weight: 20
url: /zh/java/com.aspose.pdf.drawing/circle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Circle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Circle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Circle extends Shape
```

表示圆。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Circle](#Circle--) | 仅供内部使用 |
| [Circle](#Circle-float-float-float-) | 初始化 {@code Circle} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 检查该项是否适合给定容器尺寸（包括边界）。 |
| [getPosX](#getPosX--) | 获取指示弧线中心 x 坐标的浮点值。 |
| [getPosY](#getPosY--) | 获取指示弧线中心 y 坐标的浮点值。 |
| [getRadius](#getRadius--) | 获取指示圆半径的浮点值。 |
| [setPosX](#setPosX-double-) | 设置指示弧线中心 x 坐标的浮点值。 |
| [setPosY](#setPosY-double-) | 设置指示弧线中心 y 坐标的浮点值。 |
| [setRadius](#setRadius-double-) | 设置指示圆半径的浮点值。 |

### Circle {#Circle--}
```
public Circle()
```

仅供内部使用

### Circle {#Circle-float-float-float-}
```
public Circle(float posX, float posY, float radius)
```

初始化 {@code Circle} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| posX |  | 圆心的 x 坐标。 |
| posY |  | 圆心的 y 坐标。 |
| 半径 |  | 圆的半径。 |

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

检查该项是否适合给定容器尺寸（包括边界）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
如果匹配则为 true；否则为 false。

### getPosX {#getPosX--}
```
public double getPosX()
```

获取指示弧线中心 x 坐标的浮点值。

**Returns:**
弧的中心的 x 坐标。

### getPosY {#getPosY--}
```
public double getPosY()
```

获取指示弧线中心 y 坐标的浮点值。

**Returns:**
弧的中心的 y 坐标。

### getRadius {#getRadius--}
```
public double getRadius()
```

获取指示圆半径的浮点值。

**Returns:**
指示圆半径的值。

### setPosX {#setPosX-double-}
```
public void setPosX(double value)
```

设置指示弧线中心 x 坐标的浮点值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 弧的中心的 x 坐标。 |

### setPosY {#setPosY-double-}
```
public void setPosY(double value)
```

设置指示弧线中心 y 坐标的浮点值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 弧的中心的 y 坐标。 |

### setRadius {#setRadius-double-}
```
public void setRadius(double value)
```

设置指示圆半径的浮点值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示圆半径的。 |
