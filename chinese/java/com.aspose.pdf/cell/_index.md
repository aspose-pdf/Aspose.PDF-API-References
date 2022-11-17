---
title: Cell
second_title: 用于 Java API 参考的 Aspose.PDF
description: 代表表格行的单元格。
type: docs
weight: 52
url: /zh/java/com.aspose.pdf/cell/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
com.aspose.ms.System.ICloneable
```
public final class Cell implements System.ICloneable
```

代表表格行的一个单元格。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Cell(Rectangle rect)](#Cell-com.aspose.pdf.Rectangle-) | 初始化 Cell 类的新实例。 |
| [Cell()](#Cell--) | 初始化 Cell 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 克隆细胞。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | 获取对齐方式。 |
| [getBackgroundColor()](#getBackgroundColor--) | 获取背景颜色。 |
| [getBackgroundImage()](#getBackgroundImage--) | 获取或设置背景图片 |
| [getBackgroundImageFile()](#getBackgroundImageFile--) | 获取背景图像文件。 |
| [getBorder()](#getBorder--) | 获取边框。 |
| [getClass()](#getClass--) |  |
| [getColSpan()](#getColSpan--) | 获取或设置列跨度。 |
| [getDefaultCellTextState()](#getDefaultCellTextState--) | 获取默认的单元格文本状态。 |
| [getMargin()](#getMargin--) | 获取填充。 |
| [getParagraphs()](#getParagraphs--) | 获取单元格的格式化文本。 |
| [getRowSpan()](#getRowSpan--) | 获取行跨度。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取垂直对齐方式。 |
| [getWidth()](#getWidth--) | 获取列宽。 |
| [hashCode()](#hashCode--) |  |
| [isNoBorder()](#isNoBorder--) | 获取有边框的单元格。 |
| [isOverrideByFragment()](#isOverrideByFragment--) | 设置单元格的 TextState 属性被 TextFragment 的 TextState 属性覆盖。 |
| [isWordWrapped()](#isWordWrapped--) | 获取单元格的文本单词换行。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | 设置对齐方式。 |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | 获取或设置背景颜色。 |
| [setBackgroundImage(Image value)](#setBackgroundImage-com.aspose.pdf.Image-) | 获取或设置背景图片 |
| [setBackgroundImageFile(String value)](#setBackgroundImageFile-java.lang.String-) | 设置背景图像文件。 |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | 设置边框。 |
| [setColSpan(int value)](#setColSpan-int-) | 设置列跨度。 |
| [setDefaultCellTextState(TextState value)](#setDefaultCellTextState-com.aspose.pdf.TextState-) | 设置默认单元格文本状态。 |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | 设置填充。 |
| [setNoBorder(boolean value)](#setNoBorder-boolean-) | 设置单元格有边框。 |
| [setOverrideByFragment(boolean value)](#setOverrideByFragment-boolean-) | 设置单元格的 TextState 属性被 TextFragment 的 TextState 属性覆盖。 |
| [setParagraphs(Paragraphs value)](#setParagraphs-com.aspose.pdf.Paragraphs-) | 设置单元格的格式化文本。 |
| [setRowSpan(int value)](#setRowSpan-int-) | 设置行跨度。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 设置垂直对齐方式。 |
| [setWidth(double value)](#setWidth-double-) | 设置列宽。 |
| [setWordWrapped(boolean value)](#setWordWrapped-boolean-) | 设置单元格的文本字换行。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Cell(Rectangle rect) {#Cell-com.aspose.pdf.Rectangle-}
```
public Cell(Rectangle rect)
```


初始化 Cell 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 页面坐标中单元格的矩形。 |

### Cell() {#Cell--}
```
public Cell()
```


初始化 Cell 类的新实例。

### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆细胞。

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


获取对齐方式。

**退货：**
int - HorizontalAlignment 元素
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


获取背景颜色。

**退货：**
[Color](../../com.aspose.pdf/color) 颜色对象
### getBackgroundImage() {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```


获取或设置背景图片

**退货：**
[Image](../../com.aspose.pdf/image) 图片实例
### getBackgroundImageFile() {#getBackgroundImageFile--}
```
public String getBackgroundImageFile()
```


获取背景图像文件。

**退货：**
java.lang.String - 字符串值
### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```


获取边框。

**退货：**
[BorderInfo](../../com.aspose.pdf/borderinfo) BorderInfo 对象
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getColSpan() {#getColSpan--}
```
public int getColSpan()
```


获取或设置列跨度。

**退货：**
int - 整数值
### getDefaultCellTextState() {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```


获取默认的单元格文本状态。

**退货：**
[TextState](../../com.aspose.pdf/textstate) 文本状态对象
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


获取填充。

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) MarginInfo 对象
### getParagraphs() {#getParagraphs--}
```
public Paragraphs getParagraphs()
```


获取单元格的格式化文本。

**退货：**
[Paragraphs](../../com.aspose.pdf/paragraphs) 段落对象
### getRowSpan() {#getRowSpan--}
```
public int getRowSpan()
```


获取行跨度。

**退货：**
int - 整数值
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


获取垂直对齐方式。

**退货：**
int - VerticalAlignment 元素
### getWidth() {#getWidth--}
```
public double getWidth()
```


获取列宽。

**退货：**
双倍价值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isNoBorder() {#isNoBorder--}
```
public boolean isNoBorder()
```


获取有边框的单元格。

**退货：**
boolean - 布尔值
### isOverrideByFragment() {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```


设置单元格的 TextState 属性被 TextFragment 的 TextState 属性覆盖。

**退货：**
boolean - 布尔值
### isWordWrapped() {#isWordWrapped--}
```
public boolean isWordWrapped()
```


获取单元格的文本单词换行。

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
public void setAlignment(int value)
```


设置对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HorizontalAlignment 元素 |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.pdf.Color-}
```
public void setBackgroundColor(Color value)
```


获取或设置背景颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 颜色对象 |

### setBackgroundImage(Image value) {#setBackgroundImage-com.aspose.pdf.Image-}
```
public final void setBackgroundImage(Image value)
```


获取或设置背景图片

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Image](../../com.aspose.pdf/image) | 图片实例 |

### setBackgroundImageFile(String value) {#setBackgroundImageFile-java.lang.String-}
```
public void setBackgroundImageFile(String value)
```


设置背景图像文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 颜色对象 |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```


设置边框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo 对象 |

### setColSpan(int value) {#setColSpan-int-}
```
public void setColSpan(int value)
```


设置列跨度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setDefaultCellTextState(TextState value) {#setDefaultCellTextState-com.aspose.pdf.TextState-}
```
public void setDefaultCellTextState(TextState value)
```


设置默认单元格文本状态。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextState](../../com.aspose.pdf/textstate) | 文本状态对象 |

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


设置填充。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 对象 |

### setNoBorder(boolean value) {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```


设置单元格有边框。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setOverrideByFragment(boolean value) {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```


设置单元格的 TextState 属性被 TextFragment 的 TextState 属性覆盖。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setParagraphs(Paragraphs value) {#setParagraphs-com.aspose.pdf.Paragraphs-}
```
public void setParagraphs(Paragraphs value)
```


设置单元格的格式化文本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Paragraphs](../../com.aspose.pdf/paragraphs) | 段落对象 |

### setRowSpan(int value) {#setRowSpan-int-}
```
public void setRowSpan(int value)
```


设置行跨度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


设置垂直对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | VerticalAlignment 元素 |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


设置列宽。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setWordWrapped(boolean value) {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```


设置单元格的文本字换行。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

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
