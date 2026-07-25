---
title: "Curve"
linktitle: "Curve"
second_title: "Aspose.PDF for Java API 参考"
description: "表示贝塞尔曲线。"
type: docs
weight: 30
url: /zh/java/com.aspose.pdf.drawing/curve/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Curve, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Curve

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Curve extends Shape
```

表示贝塞尔曲线。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Curve](#Curve--) | 仅供内部使用 |
| [Curve](#Curve-float:A-) | 初始化 {@code Curve} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 检查该项是否适合给定容器尺寸（包括边界）。 |
| [getPositionArray](#getPositionArray--) | 获取一个浮点位置数组。 |
| [setPositionArray](#setPositionArray-float:A-) | 设置一个浮点位置数组。 |

### Curve {#Curve--}
```
public Curve()
```

仅供内部使用

### Curve {#Curve-float:A-}
```
public Curve(float[] positionArray)
```

初始化 {@code Curve} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| positionArray |  | 曲线控制点的位置数组。应该有四个控制点，因此数组的长度应为八。 |

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

### getPositionArray {#getPositionArray--}
```
public float[] getPositionArray()
```

获取一个浮点位置数组。

**Returns:**
float[] array

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

设置一个浮点位置数组。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float[] array |
