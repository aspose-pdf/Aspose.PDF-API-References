---
title: Graph
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示图形 - 图形生成器段落。
type: docs
weight: 16
url: /zh/java/com.aspose.pdf.drawing/graph/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public final class Graph extends BaseParagraph
```

表示图形 - 图形生成器段落。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Graph()](#Graph--) | 仅供内部使用 |
| [Graph(float width, float height)](#Graph-float-float-) | 初始化 Graph 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 克隆图形。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBorder()](#getBorder--) | 获取边框。 |
| [getClass()](#getClass--) |  |
| [getGraphInfo()](#getGraphInfo--) | 获取一个GraphInfo对象，表示图形信息，如颜色、线宽等。 |
| [getHeight()](#getHeight--) | 获取表示图形高度的浮点值。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取段落的水平对齐方式 |
| [getHyperlink()](#getHyperlink--) | 获取片段超链接（用于 pdf 生成器）。 |
| [getLeft()](#getLeft--) | 获取表格左侧坐标。 |
| [getMargin()](#getMargin--) | 获取段落的外边距（用于生成 pdf） |
| [getShapes()](#getShapes--) | 获取一个 Shapes 集合，该集合指示图中的所有形状。 |
| [getTitle()](#getTitle--) | 获取指示图形标题的字符串值。 |
| [getTop()](#getTop--) | 获取桌面坐标。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取段落的垂直对齐方式 |
| [getWidth()](#getWidth--) | 获取指示图形宽度的浮点值。 |
| [getZIndex()](#getZIndex--) | 获取一个 int 值，该值指示图形的 Z 顺序。 |
| [hashCode()](#hashCode--) |  |
| [isChangePosition()](#isChangePosition--) | 在处理段落后获取更改当前位置。 |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [isInLineParagraph()](#isInLineParagraph--) | 获取一个段落是内联的。 |
| [isInNewPage()](#isInNewPage--) | 获取强制此段落在新页面生成的 bool 值。 |
| [isKeptWithNext()](#isKeptWithNext--) | 获取一个布尔值，该值指示当前段落是否与下一段保持在同一页面中。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | 设置边框。 |
| [setChangePosition(boolean value)](#setChangePosition-boolean-) | 在流程段落后设置更改当前位置。 |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [setGraphInfo(GraphInfo value)](#setGraphInfo-com.aspose.pdf.GraphInfo-) | 获取或设置一个GraphInfo对象，该对象指示图形信息，如颜色、线宽等。 |
| [setHeight(double value)](#setHeight-double-) | 设置指示图形高度的浮点值。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置段落的水平对齐方式 |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | 设置超链接（用于 pdf 生成器）。 |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | 设置一个段落是内联的。 |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | 设置一个布尔值，强制此段落在新页面生成。 |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | 设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。 |
| [setLeft(double value)](#setLeft-double-) | 设置表格左侧坐标。 |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | 设置段落的外边距（用于生成 pdf） |
| [setShapes(List<Shape> value)](#setShapes-java.util.List-com.aspose.pdf.drawing.Shape--) | 设置一个 Shapes 集合，指示图形中的所有形状。 |
| [setTitle(TextFragment value)](#setTitle-com.aspose.pdf.TextFragment-) | 设置指示图形标题的字符串值。 |
| [setTop(double value)](#setTop-double-) | 设置桌面坐标。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 设置段落的垂直对齐方式 |
| [setWidth(double value)](#setWidth-double-) | 设置表示图形宽度的浮点值。 |
| [setZIndex(int value)](#setZIndex-int-) | 设置一个指示图形 Z 顺序的 int 值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Graph() {#Graph--}
```
public Graph()
```


仅供内部使用

### Graph(float width, float height) {#Graph-float-float-}
```
public Graph(float width, float height)
```


初始化 Graph 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | float | 图的宽度。 |
| height | float | 图的高度。 |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆图形。

**退货：**
java.lang.Object - 克隆的对象
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```


获取边框。

**退货：**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo 元素
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getGraphInfo() {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```


获取一个GraphInfo对象，表示图形信息，如颜色、线宽等。

**退货：**
[GraphInfo](../../com.aspose.pdf/graphinfo) 图形信息对象
### getHeight() {#getHeight--}
```
public double getHeight()
```


获取表示图形高度的浮点值。单位是点。在 XML 中，默认单位是点，但也支持厘米和英寸。例如，GraphHeight="10cm" 或 GraphHeight="5inch"。

**退货：**
double - 表示图形高度的值。
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


获取段落的水平对齐方式

**退货：**
int - HorizontalAlignment 值
### getHyperlink() {#getHyperlink--}
```
public Hyperlink getHyperlink()
```


获取片段超链接（用于 pdf 生成器）。

**退货：**
[Hyperlink](../../com.aspose.pdf/hyperlink) - 片段超链接（用于 pdf 生成器）。
### getLeft() {#getLeft--}
```
public double getLeft()
```


获取表格左侧坐标。

**退货：**
双表左坐标。
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


获取段落的外边距（用于生成 pdf）

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) - 保证金信息值
### getShapes() {#getShapes--}
```
public List<Shape> getShapes()
```


获取一个 Shapes 集合，该集合指示图中的所有形状。

**退货：**
java.util.List<com.aspose.pdf.drawing.Shape> - 形状元素列表
### getTitle() {#getTitle--}
```
public TextFragment getTitle()
```


获取指示图形标题的字符串值。

**退货：**
[TextFragment](../../com.aspose.pdf/textfragment) 图表的标题。
### getTop() {#getTop--}
```
public double getTop()
```


获取桌面坐标。

**退货：**
double - 桌面坐标。
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


获取段落的垂直对齐方式

**退货：**
int - VerticalAlignment 元素
### getWidth() {#getWidth--}
```
public double getWidth()
```


获取指示图形宽度的浮点值。单位是点。在 XML 中，默认单位是点，但也支持厘米和英寸。例如，GraphWidth="10cm" 或 GraphWidth="5inch"。

**退货：**
double - 表示图形宽度的浮点值。
### getZIndex() {#getZIndex--}
```
public int getZIndex()
```


获取一个 int 值，该值指示图形的 Z 顺序。具有较大 ZIndex 的图形将被放置在具有较小 ZIndex 的图形之上。 ZIndex 可以是负数。具有负 ZIndex 的图形将放置在页面中文本的后面。

**退货：**
int - 整数值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isChangePosition() {#isChangePosition--}
```
public boolean isChangePosition()
```


在处理段落后获取更改当前位置。（默认为 true）

**退货：**
boolean - 布尔值
### isFirstParagraphInColumn() {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```


获取或设置一个 bool 值，该值指示该段落是否位于下一列。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### isInLineParagraph() {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```


获取一个段落是内联的。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


获取强制此段落在新页面生成的 bool 值。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### isKeptWithNext() {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```


获取一个布尔值，该值指示当前段落是否与下一段保持在同一页面中。默认为 false。（用于生成 pdf）

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```


设置边框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo 元素 |

### setChangePosition(boolean value) {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```


在处理段落后设置更改当前位置。（默认为 true）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


获取或设置一个 bool 值，该值指示该段落是否位于下一列。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setGraphInfo(GraphInfo value) {#setGraphInfo-com.aspose.pdf.GraphInfo-}
```
public void setGraphInfo(GraphInfo value)
```


获取或设置一个GraphInfo对象，该对象指示图形信息，如颜色、线宽等。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [GraphInfo](../../com.aspose.pdf/graphinfo) | 图形信息对象 |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


设置指示图形高度的浮点值。单位是点。在 XML 中，默认单位是点，但也支持厘米和英寸。例如，GraphHeight="10cm" 或 GraphHeight="5inch"。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 表示图形高度。 |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


设置段落的水平对齐方式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HorizontalAlignment 值 |

### setHyperlink(Hyperlink value) {#setHyperlink-com.aspose.pdf.Hyperlink-}
```
public void setHyperlink(Hyperlink value)
```


设置超链接（用于 pdf 生成器）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Hyperlink](../../com.aspose.pdf/hyperlink) | 超链接（用于 pdf 生成器）。 |

### setInLineParagraph(boolean value) {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```


设置一个段落是内联的。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


设置一个布尔值，强制此段落在新页面生成。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setKeptWithNext(boolean value) {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```


设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setLeft(double value) {#setLeft-double-}
```
public void setLeft(double value)
```


设置表格左侧坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 表左坐标。 |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


设置段落的外边距（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 对象 |

### setShapes(List<Shape> value) {#setShapes-java.util.List-com.aspose.pdf.drawing.Shape--}
```
public void setShapes(List<Shape> value)
```


设置一个 Shapes 集合，指示图形中的所有形状。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.List<com.aspose.pdf.drawing.Shape> | 形状元素列表 |

### setTitle(TextFragment value) {#setTitle-com.aspose.pdf.TextFragment-}
```
public void setTitle(TextFragment value)
```


设置指示图形标题的字符串值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextFragment](../../com.aspose.pdf/textfragment) | 图的标题。 |

### setTop(double value) {#setTop-double-}
```
public void setTop(double value)
```


设置桌面坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 桌面坐标。 |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


设置段落的垂直对齐方式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | VerticalAlignment 元素 |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


设置表示图形宽度的浮点值。单位是点。在 XML 中，默认单位是点，但也支持厘米和英寸。例如，GraphWidth="10cm" 或 GraphWidth="5inch"。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 表示图形宽度的浮点值。 |

### setZIndex(int value) {#setZIndex-int-}
```
public void setZIndex(int value)
```


设置一个指示图形 Z 顺序的 int 值。具有较大 ZIndex 的图形将被放置在具有较小 ZIndex 的图形之上。 ZIndex 可以是负数。具有负 ZIndex 的图形将放置在页面中文本的后面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
