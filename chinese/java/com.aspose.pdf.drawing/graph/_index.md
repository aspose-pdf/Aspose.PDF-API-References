---
title: "Graph"
linktitle: "Graph"
second_title: "Aspose.PDF for Java API 参考"
description: "表示图形 - 图形生成器段落。"
type: docs
weight: 70
url: /zh/java/com.aspose.pdf.drawing/graph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.drawing.Graph, com.aspose.pdf.BaseParagraph, com.aspose.pdf.drawing.Graph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Graph extends BaseParagraph
```

表示图形 - 图形生成器段落。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Graph](#Graph--) | 仅供内部使用 |
| [Graph](#Graph-double-double-) | 初始化 {@link Graph} 类的新实例。 |
| [Graph](#Graph-float-float-) | 初始化 {@code Graph} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone](#deepClone--) | 克隆图形。 |
| [getBorder](#getBorder--) | 获取边框。 |
| [getGraphInfo](#getGraphInfo--) | 获取一个 {@code GraphInfo} 对象，用于指示图形信息，例如颜色、线宽等。 |
| [getHeight](#getHeight--) | 获取表示图形高度的浮点值。单位为点。在 XML 中，默认单位是点，但也支持厘米和英寸。例如，GraphHeight=\"10cm\" 或 GraphHeight=\"5inch\"。 |
| [getLeft](#getLeft--) | 获取表格左坐标。 |
| [getShapes](#getShapes--) | 获取一个集合，指示图形中的所有形状。 |
| [getTitle](#getTitle--) | 获取指示图形标题的字符串值。 |
| [getTop](#getTop--) | 获取表格顶部坐标。 |
| [getWidth](#getWidth--) | 获取表示图形宽度的浮点值。单位为点。在 XML 中，默认单位是点，但也支持厘米和英寸。例如，GraphWidth=\"10cm\" 或 GraphWidth=\"5inch\"。 |
| [isChangePosition](#isChangePosition--) | 获取在处理段落后是否更改当前位置信息。（默认 true） |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | 设置边框。 |
| [setChangePosition](#setChangePosition-boolean-) | 设置在处理段落后是否更改当前位置信息。（默认 true） |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | 获取或设置一个 {@code GraphInfo} 对象，用于指示图形信息，例如颜色、线宽等。 |
| [setHeight](#setHeight-double-) | 设置表示图形高度的浮点值。单位为点。在 XML 中，默认单位是点，但也支持厘米和英寸。例如，GraphHeight=\"10cm\" 或 GraphHeight=\"5inch\"。 |
| [setLeft](#setLeft-double-) | 设置表格左坐标。 |
| [setShapes](#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-) | 设置一个集合，指示图形中的所有形状。 |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | 设置指示图表标题的字符串值。 |
| [setTop](#setTop-double-) | 设置表格顶部坐标。 |
| [setWidth](#setWidth-double-) | 设置指示图表宽度的浮点值。单位是点。在 XML 中，默认单位是点，但也支持厘米和英寸。例如，GraphWidth="10cm" 或 GraphWidth="5inch"。 |

### Graph {#Graph--}
```
public Graph()
```

仅供内部使用

### Graph {#Graph-double-double-}
```
public Graph(double width, double height)
```

初始化 {@link Graph} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 图表的宽度。 |
| 高度 |  | 图表的高度。 |

### Graph {#Graph-float-float-}
```
@Deprecated public Graph(float width, float height)
```

初始化 {@code Graph} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 图表的宽度。 |
| 高度 |  | 图表的高度。 |

### deepClone {#deepClone--}
```
public Object deepClone()
```

克隆图形。

**Returns:**
克隆的对象。

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

获取边框。

**Returns:**
BorderInfo 元素。

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

获取一个 {@code GraphInfo} 对象，用于指示图形信息，例如颜色、线宽等。

**Returns:**
GraphInfo 对象。

### getHeight {#getHeight--}
```
public double getHeight()
```

获取表示图形高度的浮点值。单位为点。在 XML 中，默认单位是点，但也支持厘米和英寸。例如，GraphHeight=\"10cm\" 或 GraphHeight=\"5inch\"。

**Returns:**
指示图表高度的值。

### getLeft {#getLeft--}
```
public double getLeft()
```

获取表格左坐标。

**Returns:**
表格左侧坐标。

### getShapes {#getShapes--}
```
public final BoundsCheckableList < Shape > getShapes()
```

获取一个集合，指示图形中的所有形状。

**Returns:**
Shapes 的 BoundsCheckableList。

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

获取指示图形标题的字符串值。

**Returns:**
图表的标题。

### getTop {#getTop--}
```
public double getTop()
```

获取表格顶部坐标。

**Returns:**
表格顶部坐标。

### getWidth {#getWidth--}
```
public double getWidth()
```

获取表示图形宽度的浮点值。单位为点。在 XML 中，默认单位是点，但也支持厘米和英寸。例如，GraphWidth=\"10cm\" 或 GraphWidth=\"5inch\"。

**Returns:**
指示图表宽度的浮点值。

### isChangePosition {#isChangePosition--}
```
public boolean isChangePosition()
```

获取在处理段落后是否更改当前位置信息。（默认 true）

**Returns:**
布尔值

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
设置边框。

### setChangePosition {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```

设置在处理段落后是否更改当前位置信息。（默认 true）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
获取或设置一个 {@code GraphInfo} 对象，用于指示图形信息，例如颜色、线宽等。

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

设置表示图形高度的浮点值。单位为点。在 XML 中，默认单位是点，但也支持厘米和英寸。例如，GraphHeight=\"10cm\" 或 GraphHeight=\"5inch\"。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示图表高度的。 |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

设置表格左坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 表格左侧坐标。 |

### setShapes {#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-}
设置一个集合，指示图形中的所有形状。

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
设置指示图表标题的字符串值。

### setTop {#setTop-double-}
```
public void setTop(double value)
```

设置表格顶部坐标。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 表格顶部坐标。 |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

设置指示图表宽度的浮点值。单位是点。在 XML 中，默认单位是点，但也支持厘米和英寸。例如，GraphWidth="10cm" 或 GraphWidth="5inch"。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 指示图表宽度的浮点值。 |
