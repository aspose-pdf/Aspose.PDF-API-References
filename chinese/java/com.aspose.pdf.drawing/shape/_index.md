---
title: "Shape"
linktitle: "Shape"
second_title: "Aspose.PDF for Java API 参考"
description: "表示形状 - 基础图形对象。"
type: docs
weight: 130
url: /zh/java/com.aspose.pdf.drawing/shape/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public abstract class Shape extends Object implements IBoundsCheckableItem
```

表示形状 - 基础图形对象。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Shape](#Shape--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | 检查该项是否适合给定容器尺寸（包括边界）。 |
| [getGraphInfo](#getGraphInfo--) | 获取指示图表信息的对象，例如颜色、线宽等。 |
| [getText](#getText--) | 获取或设置形状的文本。 |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | 设置指示图表信息的对象，例如颜色、线宽等。 |
| [setText](#setText-com.aspose.pdf.TextFragment-) | 获取或设置形状的文本。 |

### Shape {#Shape--}
```
public Shape()
```



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

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

获取指示图表信息的对象，例如颜色、线宽等。

**Returns:**
指示图表信息的对象。

### getText {#getText--}
```
public TextFragment getText()
```

获取或设置形状的文本。

**Returns:**
TextFragment 对象。

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
设置指示图表信息的对象，例如颜色、线宽等。

### setText {#setText-com.aspose.pdf.TextFragment-}
获取或设置形状的文本。
