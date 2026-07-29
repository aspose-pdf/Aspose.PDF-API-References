---
title: "Rectangle"
linktitle: "Rectangle"
second_title: "Aspose.PDF for Java API 参考"
description: "表示矩形。"
type: docs
weight: 120
url: /zh/java/com.aspose.pdf.drawing/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Rectangle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Rectangle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Rectangle extends Shape
```

表示矩形。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Rectangle](#Rectangle--) | 构造函数 |
| [Rectangle](#Rectangle-float-float-float-float-) | 初始化 {@code Rectangle} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 检查该项是否适合给定容器尺寸（包括边界）。 |
| [getBottom](#getBottom--) | 获取指示矩形底部位置的浮点值。 |
| [getHeight](#getHeight--) | 获取指示矩形高度的浮点值。 |
| [getLeft](#getLeft--) | 获取指示矩形左侧位置的浮点值。 |
| [getRoundedCornerRadius](#getRoundedCornerRadius--) | 获取指示矩形角半径的浮点值。 |
| [getWidth](#getWidth--) | 获取指示矩形宽度的浮点值。 |
| [setBottom](#setBottom-double-) | 设置指示矩形底部位置的浮点值。 |
| [setHeight](#setHeight-double-) | 设置指示矩形高度的浮点值。 |
| [setLeft](#setLeft-double-) | 设置指示矩形左侧位置的浮点值。 |
| [setRoundedCornerRadius](#setRoundedCornerRadius-double-) | 设置指示矩形角半径的浮点值。 |
| [setWidth](#setWidth-double-) | 设置指示矩形宽度的浮点值。 |

### Rectangle {#Rectangle--}
```
public Rectangle()
```

构造函数

### Rectangle {#Rectangle-float-float-float-float-}
```
public Rectangle(float left, float bottom, float width, float height)
```

初始化 {@code Rectangle} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left |  | 矩形的左侧位置。 |
| bottom |  | 矩形的底部位置。 |
| 宽度 |  | 矩形的宽度。 |
| 高度 |  | 矩形的高度。 |

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

### getBottom {#getBottom--}
```
public double getBottom()
```

获取指示矩形底部位置的浮点值。

**Returns:**
指示矩形底部位置的值。

### getHeight {#getHeight--}
```
public double getHeight()
```

获取指示矩形高度的浮点值。

**Returns:**
指示矩形高度的值。

### getLeft {#getLeft--}
```
public double getLeft()
```

获取指示矩形左侧位置的浮点值。

**Returns:**
指示矩形左侧位置的浮点值。

### getRoundedCornerRadius {#getRoundedCornerRadius--}
```
public double getRoundedCornerRadius()
```

获取指示矩形角半径的浮点值。

**Returns:**
指示矩形角半径的值。

### getWidth {#getWidth--}
```
public double getWidth()
```

获取指示矩形宽度的浮点值。

**Returns:**
指示矩形宽度的值。

### setBottom {#setBottom-double-}
```
public void setBottom(double value)
```

设置指示矩形底部位置的浮点值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示矩形底部位置的值。 |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

设置指示矩形高度的浮点值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示矩形高度的值。 |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

设置指示矩形左侧位置的浮点值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示矩形左侧位置的浮点值。 |

### setRoundedCornerRadius {#setRoundedCornerRadius-double-}
```
public void setRoundedCornerRadius(double value)
```

设置指示矩形角半径的浮点值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示矩形角半径的。 |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

设置指示矩形宽度的浮点值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示矩形宽度的。 |
