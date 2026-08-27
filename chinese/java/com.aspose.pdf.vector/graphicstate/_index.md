---
title: "GraphicState"
linktitle: "GraphicState"
second_title: "Aspose.PDF for Java API 参考"
description: "表示当前 {@link GraphicElement} 的图形状态。"
type: docs
weight: 40
url: /zh/java/com.aspose.pdf.vector/graphicstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicState

```
public class GraphicState extends Object
```

表示当前 {@link GraphicElement} 的图形状态。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getClipsAndMatrices](#getClipsAndMatrices--) | 获取表示剪辑和连接矩阵的运算符。 |
| [getColorsAndStyles](#getColorsAndStyles--) | 获取表示颜色空间、颜色和线条样式的运算符。 |
| [getMatrix](#getMatrix--) | 获取当前的变换矩阵。 |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | 获取当前的变换矩阵。 |

### getClipsAndMatrices {#getClipsAndMatrices--}
```
public final List < Operator > getClipsAndMatrices()
```

获取表示剪辑和连接矩阵的运算符。

**Returns:**
Operator 实例列表

### getColorsAndStyles {#getColorsAndStyles--}
```
public final com.aspose.ms.System.Collections.Generic.SortedDictionary< Byte , Operator > getColorsAndStyles()
```

获取表示颜色空间、颜色和线条样式的运算符。

**Returns:**
SortedDictionary 实例

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

获取当前的变换矩阵。

**Returns:**
矩阵实例

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
获取当前的变换矩阵。
