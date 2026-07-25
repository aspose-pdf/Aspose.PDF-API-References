---
title: "Line"
linktitle: "Line"
second_title: "Aspose.PDF for Java API 参考"
description: "表示直线。"
type: docs
weight: 90
url: /zh/java/com.aspose.pdf.drawing/line/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Line, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Line

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Line extends Shape
```

表示直线。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Line](#Line--) | 仅供内部使用 |
| [Line](#Line-float:A-) | 初始化 {@code Line} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 检查该项是否适合给定容器尺寸（包括边界）。 |
| [getPositionArray](#getPositionArray--) | 获取指示位置数组的对象。数组由线的每个控制点的坐标组成。直接。 |
| [setPositionArray](#setPositionArray-float:A-) | 设置指示位置数组的对象。数组由线的每个控制点的坐标组成。直接。 |

### Line {#Line--}
```
public Line()
```

仅供内部使用

### Line {#Line-float:A-}
```
public Line(float[] positionArray)
```

初始化 {@code Line} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| positionArray |  | 线的位置数组。 |

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

获取指示位置数组的对象。数组由线的每个控制点的坐标组成。直接。

**Returns:**
指示位置数组的。

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

设置指示位置数组的对象。数组由线的每个控制点的坐标组成。直接。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示位置数组的。 |
