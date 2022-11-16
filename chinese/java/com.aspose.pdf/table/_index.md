---
title: Table
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示可以添加到页面的表格。
type: docs
weight: 352
url: /zh/java/com.aspose.pdf/table/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public final class Table extends BaseParagraph
```

表示可以添加到页面的表格。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Table()](#Table--) | 默认构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 克隆表。 |
| [drawRoundedRectangle(GraphInfo info, Point topLeft, Point rightBottom, List<Operator> operators, double radius)](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-com.aspose.pdf.Operator--double-) | 为矩形添加运算符。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | 获取表格对齐方式。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取表格背景色 |
| [getBorder()](#getBorder--) | 获取边框。 |
| [getBreakText()](#getBreakText--) | 获取表格的中断文本 |
| [getBroken()](#getBroken--) | 获取或设置表格垂直断开； |
| [getClass()](#getClass--) |  |
| [getColumnAdjustment()](#getColumnAdjustment--) | 获取表格列调整。 |
| [getColumnWidth(String stringColumnWidth)](#getColumnWidth-java.lang.String-) | 获取列宽 |
| [getColumnWidths()](#getColumnWidths--) | 获取表格的列宽。 |
| [getCornerStyle()](#getCornerStyle--) | 获取边框角的样式 |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | 获取默认单元格边框； |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | 获取默认的单元格填充。 |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | 获取默认的单元格文本状态。 |
| [getDefaultColumnWidth()](#getDefaultColumnWidth--) | 获取默认单元格边框； |
| [getHeight()](#getHeight--) | 获取高度。 |
| [getHeight(Page parentPage)](#getHeight-com.aspose.pdf.Page-) | 获取高度。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取段落的水平对齐方式 |
| [getHyperlink()](#getHyperlink--) | 获取片段超链接（用于 pdf 生成器）。 |
| [getLeft()](#getLeft--) | 获取表格左侧坐标。 |
| [getMargin()](#getMargin--) | 获取段落的外边距（用于生成 pdf） |
| [getRepeatingColumnsCount()](#getRepeatingColumnsCount--) | 获取或设置表的最大列数 |
| [getRepeatingRowsCount()](#getRepeatingRowsCount--) | 获取多页重复的第一行计数 |
| [getRepeatingRowsStyle()](#getRepeatingRowsStyle--) | 获取重复行的样式 |
| [getRows()](#getRows--) | 获取表的行。 |
| [getTop()](#getTop--) | 获取桌面坐标。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取段落的垂直对齐方式 |
| [getWidth()](#getWidth--) | 获取宽度。 |
| [getZIndex()](#getZIndex--) | 获取一个 int 值，该值指示图形的 Z 顺序。 |
| [hashCode()](#hashCode--) |  |
| [isBordersIncluded()](#isBordersIncluded--) | 获取包含在列宽中的边框。 |
| [isBroken()](#isBroken--) | 获取表格已损坏 - 将被截断以供下一页使用。 |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [isInLineParagraph()](#isInLineParagraph--) | 获取一个段落是内联的。 |
| [isInNewPage()](#isInNewPage--) | 获取强制此段落在新页面生成的 bool 值。 |
| [isKeptWithNext()](#isKeptWithNext--) | 获取一个布尔值，该值指示当前段落是否与下一段保持在同一页面中。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | 设置表格对齐方式。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | 设置表格背景颜色 |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | 设置边框。 |
| [setBordersIncluded(boolean value)](#setBordersIncluded-boolean-) | 设置包含在列宽中的边框。 |
| [setBreakText(TextFragment value)](#setBreakText-com.aspose.pdf.TextFragment-) | 设置表格的中断文本 |
| [setBroken(boolean value)](#setBroken-boolean-) | 设置表格已损坏 - 将被截断以供下一页使用。 |
| [setBroken(int value)](#setBroken-int-) | 获取或设置表格垂直断开； |
| [setColumnAdjustment(int value)](#setColumnAdjustment-int-) | 设置表格列调整。 |
| [setColumnTextState(int colNumber, TextState textState)](#setColumnTextState-int-com.aspose.pdf.TextState-) | 设置高度。 |
| [setColumnWidths(String value)](#setColumnWidths-java.lang.String-) | 获取表格的列宽。 |
| [setCornerStyle(int value)](#setCornerStyle-int-) | 获取或设置边框角的样式 |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | 获取默认单元格边框； |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | 设置默认单元格填充。 |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | 设置默认单元格文本状态。 |
| [setDefaultColumnWidth(String value)](#setDefaultColumnWidth-java.lang.String-) | 获取默认单元格边框； |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置段落的水平对齐方式 |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | 设置超链接（用于 pdf 生成器）。 |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | 设置一个段落是内联的。 |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | 设置一个布尔值，强制此段落在新页面生成。 |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | 设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。 |
| [setLeft(float value)](#setLeft-float-) | 设置表格左侧坐标。 |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | 设置段落的外边距（用于生成 pdf） |
| [setRepeatingColumnsCount(int value)](#setRepeatingColumnsCount-int-) | 获取或设置表的最大列数 |
| [setRepeatingRowsCount(int value)](#setRepeatingRowsCount-int-) | 获取多页重复的第一行计数 |
| [setRepeatingRowsStyle(TextState value)](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | 获取重复行的样式 |
| [setTop(float value)](#setTop-float-) | 设置桌面坐标。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 设置段落的垂直对齐方式 |
| [setZIndex(int value)](#setZIndex-int-) | 设置一个指示图形 Z 顺序的 int 值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Table() {#Table--}
```
public Table()
```


默认构造函数

### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆表。

**退货：**
java.lang.Object - 克隆的对象
### drawRoundedRectangle(GraphInfo info, Point topLeft, Point rightBottom, List<Operator> operators, double radius) {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-com.aspose.pdf.Operator--double-}
```
public static void drawRoundedRectangle(GraphInfo info, Point topLeft, Point rightBottom, List<Operator> operators, double radius)
```


为矩形添加运算符。

仅供内部使用。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| info | [GraphInfo](../../com.aspose.pdf/graphinfo) | 边框样式。 |
| topLeft | [Point](../../com.aspose.pdf/point) | 左上角。 |
| rightBottom | [Point](../../com.aspose.pdf/point) | 右下角。 |
| operators | java.util.List<com.aspose.pdf.Operator> | 要添加到页面内容中的运算符列表。 |
| radius | double | 边界半径。 |

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
### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


获取表格对齐方式。

**退货：**
int - HorizontalAlignment 值
### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


获取表格背景色

**退货：**
[Color](../../com.aspose.pdf/color) 颜色对象
### getBorder() {#getBorder--}
```
public final BorderInfo getBorder()
```


获取边框。

**退货：**
[BorderInfo](../../com.aspose.pdf/borderinfo) BorderInfo 对象
### getBreakText() {#getBreakText--}
```
public final TextFragment getBreakText()
```


获取表格的中断文本

**退货：**
[TextFragment](../../com.aspose.pdf/textfragment) - TextFragment 对象
### getBroken() {#getBroken--}
```
public final int getBroken()
```


获取或设置表格垂直断开；

**退货：**
int - TableBroken 值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getColumnAdjustment() {#getColumnAdjustment--}
```
public final int getColumnAdjustment()
```


获取表格列调整。

**退货：**
int - 列调整值
### getColumnWidth(String stringColumnWidth) {#getColumnWidth-java.lang.String-}
```
public static double getColumnWidth(String stringColumnWidth)
```


获取列宽

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stringColumnWidth | java.lang.String | 字符串表示。 |

**退货：**
双倍价值
### getColumnWidths() {#getColumnWidths--}
```
public final String getColumnWidths()
```


获取表格的列宽。

**退货：**
java.lang.String - 字符串值
### getCornerStyle() {#getCornerStyle--}
```
public final int getCornerStyle()
```


获取边框角的样式

**退货：**
int - BorderCornerStyle 值
### getDefaultCellBorder() {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```


获取默认单元格边框；

**退货：**
[BorderInfo](../../com.aspose.pdf/borderinfo) BorderInfo 对象
### getDefaultCellPadding() {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```


获取默认的单元格填充。

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) MarginInfo 对象
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```


获取默认的单元格文本状态。

**退货：**
[TextState](../../com.aspose.pdf/textstate) - 文本状态值
### getDefaultColumnWidth() {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```


获取默认单元格边框；

**退货：**
java.lang.String - 字符串对象
### getHeight() {#getHeight--}
```
public double getHeight()
```


获取高度。

**退货：**
double - 桌子高度
### getHeight(Page parentPage) {#getHeight-com.aspose.pdf.Page-}
```
public double getHeight(Page parentPage)
```


获取高度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| parentPage | [Page](../../com.aspose.pdf/page) | 表的父页面 |

**退货：**
double - 桌子高度
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
public final float getLeft()
```


获取表格左侧坐标。

**退货：**
float - 浮点值
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


获取段落的外边距（用于生成 pdf）

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) - 保证金信息值
### getRepeatingColumnsCount() {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```


获取或设置表的最大列数

**退货：**
int - 整数值
### getRepeatingRowsCount() {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```


获取多页重复的第一行计数

**退货：**
int - 整数值
### getRepeatingRowsStyle() {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```


获取重复行的样式

**退货：**
[TextState](../../com.aspose.pdf/textstate) 文本状态对象
### getRows() {#getRows--}
```
public final Rows getRows()
```


获取表的行。

**退货：**
[Rows](../../com.aspose.pdf/rows) 行对象
### getTop() {#getTop--}
```
public final float getTop()
```


获取桌面坐标。

**退货：**
float - 浮点值
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


获取宽度。

**退货：**
double - 表格宽度
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
### isBordersIncluded() {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```


获取包含在列宽中的边框。

**退货：**
boolean - 布尔值
### isBroken() {#isBroken--}
```
public final boolean isBroken()
```


获取表格已损坏 - 将被截断以供下一页使用。

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




### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


设置表格对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HorizontalAlignment 值 |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public final void setBackgroundColor(Color value)
```


设置表格背景颜色

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 颜色对象 |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public final void setBorder(BorderInfo value)
```


设置边框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo 对象 |

### setBordersIncluded(boolean value) {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```


设置包含在列宽中的边框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setBreakText(TextFragment value) {#setBreakText-com.aspose.pdf.TextFragment-}
```
public final void setBreakText(TextFragment value)
```


设置表格的中断文本

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextFragment](../../com.aspose.pdf/textfragment) | 文本片段对象 |

### setBroken(boolean value) {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```


设置表格已损坏 - 将被截断以供下一页使用。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setBroken(int value) {#setBroken-int-}
```
public final void setBroken(int value)
```


获取或设置表格垂直断开；

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 破表值 |

### setColumnAdjustment(int value) {#setColumnAdjustment-int-}
```
public final void setColumnAdjustment(int value)
```


设置表格列调整。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 列调整值 |

### setColumnTextState(int colNumber, TextState textState) {#setColumnTextState-int-com.aspose.pdf.TextState-}
```
public void setColumnTextState(int colNumber, TextState textState)
```


设置高度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| colNumber | int | 列号。 |
| textState | [TextState](../../com.aspose.pdf/textstate) | 列的文本状态。 |

### setColumnWidths(String value) {#setColumnWidths-java.lang.String-}
```
public final void setColumnWidths(String value)
```


获取表格的列宽。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setCornerStyle(int value) {#setCornerStyle-int-}
```
public final void setCornerStyle(int value)
```


获取或设置边框角的样式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | BorderCornerStyle 值 |

### setDefaultCellBorder(BorderInfo value) {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
```
public final void setDefaultCellBorder(BorderInfo value)
```


获取默认单元格边框；

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo 对象 |

### setDefaultCellPadding(MarginInfo value) {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
```
public final void setDefaultCellPadding(MarginInfo value)
```


设置默认单元格填充。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 对象 |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public final void setDefaultCellTextState(TextState value)
```


设置默认单元格文本状态。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | 文本状态值 |

### setDefaultColumnWidth(String value) {#setDefaultColumnWidth-java.lang.String-}
```
public final void setDefaultColumnWidth(String value)
```


获取默认单元格边框；

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串对象 |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


获取或设置一个 bool 值，该值指示该段落是否位于下一列。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

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

### setLeft(float value) {#setLeft-float-}
```
public final void setLeft(float value)
```


设置表格左侧坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


设置段落的外边距（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 对象 |

### setRepeatingColumnsCount(int value) {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```


获取或设置表的最大列数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setRepeatingRowsCount(int value) {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```


获取多页重复的第一行计数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setRepeatingRowsStyle(TextState value) {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
```
public final void setRepeatingRowsStyle(TextState value)
```


获取重复行的样式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | 文本状态对象 |

### setTop(float value) {#setTop-float-}
```
public final void setTop(float value)
```


设置桌面坐标。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


设置段落的垂直对齐方式

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | VerticalAlignment 元素 |

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
