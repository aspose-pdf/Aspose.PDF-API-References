---
title: Row
second_title: 用于 Java API 参考的 Aspose.PDF
description: 代表表格的一行。
type: docs
weight: 316
url: /zh/java/com.aspose.pdf/row/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
com.aspose.ms.System.ICloneable
```
public final class Row implements System.ICloneable
```

代表表格的一行。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Row()](#Row--) | 初始化 Row 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 克隆该行。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | 获取背景颜色。 |
| [getBorder()](#getBorder--) | 获取边框。 |
| [getCells()](#getCells--) | 获取行的 getCells()。 |
| [getClass()](#getClass--) |  |
| [getDefaultCellBorder()](#getDefaultCellBorder--) | 获取默认单元格边框； |
| [getDefaultCellPadding()](#getDefaultCellPadding--) | 获取行的默认边距 getCells() |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | 获取或设置行的默认文本状态 getCells() |
| [getFixedRowHeight()](#getFixedRowHeight--) | 获取固定的行高——行可能有固定的高度； |
| [getMinRowHeight()](#getMinRowHeight--) | 获取行的高度； |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取或设置垂直对齐方式。 |
| [hashCode()](#hashCode--) |  |
| [isInNewPage()](#isInNewPage--) | 获取固定行在新页面中 - 具有此属性的页面应打印到下一页默认 false； |
| [isRowBroken()](#isRowBroken--) | 获取是行可以在两页之间断开 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | 设置背景颜色。 |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | 设置边框。 |
| [setCells(Cells value)](#setCells-com.aspose.pdf.Cells-) | 设置行的 getCells()。 |
| [setDefaultCellBorder(BorderInfo value)](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | 设置默认单元格边框； |
| [setDefaultCellPadding(MarginInfo value)](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | 设置行的默认边距 getCells() |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | 设置行的默认文本状态 getCells() |
| [setFixedRowHeight(double value)](#setFixedRowHeight-double-) | 设置固定的行高——行可以有固定的高度； |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | 设置是行可以在两页之间断开 |
| [setMinRowHeight(double value)](#setMinRowHeight-double-) | 设置行高； |
| [setRowBroken(boolean value)](#setRowBroken-boolean-) | 设置是行可以在两页之间断开 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 获取或设置垂直对齐方式。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Row() {#Row--}
```
public Row()
```


初始化 Row 类的新实例。

### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆该行。

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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


获取背景颜色。

**退货：**
[Color](../../com.aspose.pdf/color) - 颜色值
### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```


获取边框。

**退货：**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo 值
### getCells() {#getCells--}
```
public Cells getCells()
```


获取行的 getCells()。

**退货：**
[Cells](../../com.aspose.pdf/cells) getCells() 值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getDefaultCellBorder() {#getDefaultCellBorder--}
```
public BorderInfo getDefaultCellBorder()
```


获取默认单元格边框；

**退货：**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo 值
### getDefaultCellPadding() {#getDefaultCellPadding--}
```
public MarginInfo getDefaultCellPadding()
```


获取行的默认边距 getCells()

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) - 保证金信息值
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```


获取或设置行的默认文本状态 getCells()

获取行的默认文本状态 getCells()

**退货：**
[TextState](../../com.aspose.pdf/textstate) - 文本状态值
### getFixedRowHeight() {#getFixedRowHeight--}
```
public double getFixedRowHeight()
```


获取固定的行高——行可能有固定的高度；

**退货：**
双倍价值
### getMinRowHeight() {#getMinRowHeight--}
```
public double getMinRowHeight()
```


获取行的高度；

**退货：**
双倍价值
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


获取或设置垂直对齐方式。

**退货：**
int - VerticalAlignment 元素
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isInNewPage() {#isInNewPage--}
```
public boolean isInNewPage()
```


获取固定行在新页面中 - 具有此属性的页面应打印到下一页默认 false；

**退货：**
boolean - 布尔值
### isRowBroken() {#isRowBroken--}
```
public boolean isRowBroken()
```


获取是行可以在两页之间断开

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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


设置背景颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 色值 |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```


设置边框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo 值 |

### setCells(Cells value) {#setCells-com.aspose.pdf.Cells-}
```
public void setCells(Cells value)
```


设置行的 getCells()。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Cells](../../com.aspose.pdf/cells) | getCells() 值 |

### setDefaultCellBorder(BorderInfo value) {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
```
public void setDefaultCellBorder(BorderInfo value)
```


设置默认单元格边框；

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo 值 |

### setDefaultCellPadding(MarginInfo value) {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
```
public void setDefaultCellPadding(MarginInfo value)
```


设置行的默认边距 getCells()

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 值 |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public void setDefaultCellTextState(TextState value)
```


设置行的默认文本状态 getCells()

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | 文本状态值 |

### setFixedRowHeight(double value) {#setFixedRowHeight-double-}
```
public void setFixedRowHeight(double value)
```


设置固定的行高——行可以有固定的高度；

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setInNewPage(boolean value) {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```


设置是行可以在两页之间断开

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setMinRowHeight(double value) {#setMinRowHeight-double-}
```
public void setMinRowHeight(double value)
```


设置行高；

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setRowBroken(boolean value) {#setRowBroken-boolean-}
```
public void setRowBroken(boolean value)
```


设置是行可以在两页之间断开

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


获取或设置垂直对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | VerticalAlignment 元素 |

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
