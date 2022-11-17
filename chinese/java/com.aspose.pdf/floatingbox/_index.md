---
title: FloatingBox
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 Pdf 文档中的 FloatingBox。
type: docs
weight: 128
url: /zh/java/com.aspose.pdf/floatingbox/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public class FloatingBox extends BaseParagraph
```

表示 Pdf 文档中的 FloatingBox。 FloatingBox 是自定义定位的。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FloatingBox(float width, float height)](#FloatingBox-float-float-) | 使用指定的宽度和高度初始化 FloatingBox 类的新实例。 |
| [FloatingBox()](#FloatingBox--) | 初始化 FloatingBox 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [deepClone()](#deepClone--) | 克隆一个新的 FloatingBox 对象。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | 获取一个对象，该对象指示浮动框的背景颜色。 |
| [getBackgroundImage()](#getBackgroundImage--) | 获取或设置页面的背景图像（仅适用于生成器）。 |
| [getBorder()](#getBorder--) | 获取一个对象，该对象表示浮动框的边框信息。 |
| [getClass()](#getClass--) |  |
| [getColumnInfo()](#getColumnInfo--) | 获取列信息 |
| [getHeight()](#getHeight--) | 获取一个浮点值，该值指示浮动框的高度。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取段落的水平对齐方式 |
| [getHyperlink()](#getHyperlink--) | 获取片段超链接（用于 pdf 生成器）。 |
| [getLeft()](#getLeft--) | 获取表格左侧坐标。 |
| [getMargin()](#getMargin--) | 获取段落的外边距（用于生成 pdf） |
| [getPadding()](#getPadding--) | 获取一个对象，该对象指示浮动框的填充。 |
| [getParagraphs()](#getParagraphs--) | 获取一个集合，该集合指示单元格中的所有段落。 |
| [getTop()](#getTop--) | 获取桌面坐标。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取段落的垂直对齐方式 |
| [getWidth()](#getWidth--) | 获取一个浮点值，该值指示浮动框的宽度。 |
| [getZIndex()](#getZIndex--) | 获取一个 int 值，该值指示图形的 Z 顺序。 |
| [hashCode()](#hashCode--) |  |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [isInLineParagraph()](#isInLineParagraph--) | 获取一个段落是内联的。 |
| [isInNewPage()](#isInNewPage--) | 获取强制此段落在新页面生成的 bool 值。 |
| [isKeptWithNext()](#isKeptWithNext--) | 获取一个布尔值，该值指示当前段落是否与下一段保持在同一页面中。 |
| [isNeedRepeating()](#isNeedRepeating--) | 获取一个布尔值，该值指示该段落是否需要在下一页重复。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.pdf.Color-) | 设置一个对象，指示浮动框的背景颜色。 |
| [setBackgroundImage(Image value)](#setBackgroundImage-com.aspose.pdf.Image-) | 获取或设置页面的背景图像（仅适用于生成器）。 |
| [setBorder(BorderInfo value)](#setBorder-com.aspose.pdf.BorderInfo-) | 设置一个指示浮动框边框信息的对象。 |
| [setColumnInfo(ColumnInfo value)](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | 设置列信息 |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [setHeight(double value)](#setHeight-double-) | 设置一个浮点值，表示浮动框的高度。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置段落的水平对齐方式 |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | 设置超链接（用于 pdf 生成器）。 |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | 设置一个段落是内联的。 |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | 设置一个布尔值，强制此段落在新页面生成。 |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | 设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。 |
| [setLeft(double value)](#setLeft-double-) | 设置表格左侧坐标。 |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | 设置段落的外边距（用于生成 pdf） |
| [setNeedRepeating(boolean value)](#setNeedRepeating-boolean-) | 设置一个布尔值，指示该段落是否需要在下一页重复。 |
| [setPadding(MarginInfo value)](#setPadding-com.aspose.pdf.MarginInfo-) | 设置一个对象，指示浮动框的填充。 |
| [setParagraphs(Paragraphs value)](#setParagraphs-com.aspose.pdf.Paragraphs-) | 设置一个指示单元格中所有段落的集合。 |
| [setTop(double value)](#setTop-double-) | 设置桌面坐标。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 设置段落的垂直对齐方式 |
| [setWidth(double value)](#setWidth-double-) | 设置一个浮点值，表示浮动框的宽度。 |
| [setZIndex(int value)](#setZIndex-int-) | 设置一个指示图形 Z 顺序的 int 值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FloatingBox(float width, float height) {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```


使用指定的宽度和高度初始化 FloatingBox 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | float | 盒子的宽度。 |
| height | float | 盒子的高度。 |

### FloatingBox() {#FloatingBox--}
```
public FloatingBox()
```


初始化 FloatingBox 类的新实例。

### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆一个新的 FloatingBox 对象。浮动框中的段落不会被复制。

**退货：**
java.lang.Object - 新的 FloatingBox 对象。
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


获取一个对象，该对象指示浮动框的背景颜色。

**退货：**
[Color](../../com.aspose.pdf/color) - 指示背景颜色的对象。
### getBackgroundImage() {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```


获取或设置页面的背景图像（仅适用于生成器）。

**退货：**
[Image](../../com.aspose.pdf/image) 图片实例
### getBorder() {#getBorder--}
```
public BorderInfo getBorder()
```


获取一个对象，该对象表示浮动框的边框信息。

**退货：**
[BorderInfo](../../com.aspose.pdf/borderinfo) - 表示边界信息的对象。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getColumnInfo() {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```


获取列信息

**退货：**
[ColumnInfo](../../com.aspose.pdf/columninfo) - ColumnInfo 对象
### getHeight() {#getHeight--}
```
public double getHeight()
```


获取一个浮点值，该值指示浮动框的高度。

**退货：**
double - 表示高度的值。
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
### getPadding() {#getPadding--}
```
public MarginInfo getPadding()
```


获取一个对象，该对象指示浮动框的填充。

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) - 指示填充的对象。
### getParagraphs() {#getParagraphs--}
```
public Paragraphs getParagraphs()
```


获取一个集合，该集合指示单元格中的所有段落。

**退货：**
[Paragraphs](../../com.aspose.pdf/paragraphs) - 指示所有段落的集合。
### getTop() {#getTop--}
```
public double getTop()
```


获取桌面坐标。

**退货：**
双桌面坐标。
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


获取一个浮点值，该值指示浮动框的宽度。

**退货：**
双倍价值
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
### isNeedRepeating() {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```


获取一个布尔值，该值指示该段落是否需要在下一页重复。默认值为 true。仅当段落本身及其 ReferenceParagraphID 引用的对象都包含在 RepeatingRows 中时，该属性才有效。

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


设置一个对象，指示浮动框的背景颜色。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Color](../../com.aspose.pdf/color) | 指示背景颜色的对象。 |

### setBackgroundImage(Image value) {#setBackgroundImage-com.aspose.pdf.Image-}
```
public final void setBackgroundImage(Image value)
```


获取或设置页面的背景图像（仅适用于生成器）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Image](../../com.aspose.pdf/image) | 图片实例 |

### setBorder(BorderInfo value) {#setBorder-com.aspose.pdf.BorderInfo-}
```
public void setBorder(BorderInfo value)
```


设置一个指示浮动框边框信息的对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [BorderInfo](../../com.aspose.pdf/borderinfo) | 指示边框信息的对象。 |

### setColumnInfo(ColumnInfo value) {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
```
public void setColumnInfo(ColumnInfo value)
```


设置列信息

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [ColumnInfo](../../com.aspose.pdf/columninfo) | 列信息值 |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


获取或设置一个 bool 值，该值指示该段落是否位于下一列。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


设置一个浮点值，表示浮动框的高度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 表示高度的值。 |

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

### setNeedRepeating(boolean value) {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```


设置一个布尔值，指示该段落是否需要在下一页重复。默认值为 true。仅当段落本身及其 ReferenceParagraphID 引用的对象都包含在 RepeatingRows 中时，该属性才有效。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setPadding(MarginInfo value) {#setPadding-com.aspose.pdf.MarginInfo-}
```
public void setPadding(MarginInfo value)
```


设置一个对象，指示浮动框的填充。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | 指示填充的对象。 |

### setParagraphs(Paragraphs value) {#setParagraphs-com.aspose.pdf.Paragraphs-}
```
public void setParagraphs(Paragraphs value)
```


设置一个指示单元格中所有段落的集合。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Paragraphs](../../com.aspose.pdf/paragraphs) | 指示所有段落的集合。 |

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


设置一个浮点值，表示浮动框的宽度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

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
