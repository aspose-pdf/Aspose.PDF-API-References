---
title: "Ellipse"
linktitle: "Ellipse"
second_title: "Aspose.PDF for Java API 参考"
description: "表示椭圆。"
type: docs
weight: 40
url: /zh/java/com.aspose.pdf.drawing/ellipse/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Ellipse, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Ellipse

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Ellipse extends Shape
```

表示椭圆。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Ellipse](#Ellipse--) | 仅供内部使用 |
| [Ellipse](#Ellipse-double-double-double-double-) | 初始化 {@code Ellipse} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 检查该项是否适合给定容器尺寸（包括边界）。 |
| [getBottom](#getBottom--) | 获取指示椭圆底部位置的 float 值。 |
| [getHeight](#getHeight--) | 获取指示椭圆高度的 float 值。 |
| [getLeft](#getLeft--) | 获取指示椭圆左侧位置的 float 值。 |
| [getWidth](#getWidth--) | 获取指示椭圆宽度的 float 值。 |
| [setBottom](#setBottom-double-) | 设置指示椭圆底部位置的 float 值。 |
| [setHeight](#setHeight-double-) | 设置指示椭圆高度的 float 值。 |
| [setLeft](#setLeft-double-) | 设置指示椭圆左侧位置的 float 值。 |
| [setWidth](#setWidth-double-) | 获取指示椭圆宽度的 float 值。 |

### Ellipse {#Ellipse--}
```
public Ellipse()
```

仅供内部使用

### Ellipse {#Ellipse-double-double-double-double-}
```
public Ellipse(double left, double bottom, double width, double height)
```

初始化 {@code Ellipse} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left |  | 椭圆的左侧位置。 |
| bottom |  | 椭圆的底部位置。 |
| 宽度 |  | 椭圆的宽度。 |
| 高度 |  | 椭圆的高度。 |

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

获取指示椭圆底部位置的 float 值。

**Returns:**
指示椭圆底部位置的值。

### getHeight {#getHeight--}
```
public double getHeight()
```

获取指示椭圆高度的 float 值。

**Returns:**
指示椭圆高度的值

### getLeft {#getLeft--}
```
public double getLeft()
```

获取指示椭圆左侧位置的 float 值。

**Returns:**
指示椭圆左侧位置的值。

### getWidth {#getWidth--}
```
public double getWidth()
```

获取指示椭圆宽度的 float 值。

**Returns:**
指示椭圆宽度的值。

### setBottom {#setBottom-double-}
```
public void setBottom(double value)
```

设置指示椭圆底部位置的 float 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示椭圆底部位置的。 |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

设置指示椭圆高度的 float 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示椭圆高度的 |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

设置指示椭圆左侧位置的 float 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示椭圆左侧位置的。 |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

获取指示椭圆宽度的 float 值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示椭圆宽度的。 |
