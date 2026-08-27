---
title: "Path"
linktitle: "Path"
second_title: "Aspose.PDF for Java API 参考"
description: "表示弧线。"
type: docs
weight: 100
url: /zh/java/com.aspose.pdf.drawing/path/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Path, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Path

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Path extends Shape
```

表示弧线。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Path](#Path--) | 初始化 {@code Path} 类的新实例。 |
| [Path](#Path-com.aspose.pdf.drawing.Shape:A-) | 初始化 {@code Path} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 检查该项是否适合给定容器尺寸（包括边界）。 |
| [getShapes](#getShapes--) | <p> 获取或设置形状集合。 </p> |
| [getShapesInternal](#getShapesInternal--) | 获取或设置形状集合。 |

### Path {#Path--}
```
public Path()
```

初始化 {@code Path} 类的新实例。

### Path {#Path-com.aspose.pdf.drawing.Shape:A-}
初始化 {@code Path} 类的新实例。

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

### getShapes {#getShapes--}
```
public List < Shape > getShapes()
```

<p> 获取或设置形状集合。 </p>

**Returns:**
{@code java.util.List<Shape> }对象

### getShapesInternal {#getShapesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< Shape > getShapesInternal()
```

获取或设置形状集合。

**Returns:**
内部对象
