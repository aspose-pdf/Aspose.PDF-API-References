---
title: Image
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示图像。
type: docs
weight: 166
url: /zh/java/com.aspose.pdf/image/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph)
```
public final class Image extends BaseParagraph
```

表示图像。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Image()](#Image--) | 默认构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [convertToJpeg(InputStream value)](#convertToJpeg-java.io.InputStream-) | 尝试将 bmp/png/gif/tiff 图像流转换为 JPG 格式图像流。 |
| [deepClone()](#deepClone--) | 克隆图像。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferedImage()](#getBufferedImage--) | 获取 java awt 图像。 |
| [getClass()](#getClass--) |  |
| [getFile()](#getFile--) | 获取图像文件。 |
| [getFileType()](#getFileType--) | 获取图像文件类型。 |
| [getFixHeight()](#getFixHeight--) | 获取图像高度。 |
| [getFixWidth()](#getFixWidth--) | 获取图像宽度。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取段落的水平对齐方式 |
| [getHyperlink()](#getHyperlink--) | 获取片段超链接（用于 pdf 生成器）。 |
| [getImageScale()](#getImageScale--) | 获取图像比例。 |
| [getImageStream()](#getImageStream--) | 获取图像流。 |
| [getMargin()](#getMargin--) | 获取段落的外边距（用于生成 pdf） |
| [getMimeType(System.Drawing.Image i)](#getMimeType-com.aspose.ms.System.Drawing.Image-) | 返回图像的 MIME 类型。 |
| [getTitle()](#getTitle--) | 获取一个字符串值，该值指示图像的标题。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取段落的垂直对齐方式 |
| [getZIndex()](#getZIndex--) | 获取一个 int 值，该值指示图形的 Z 顺序。 |
| [hashCode()](#hashCode--) |  |
| [isApplyResolution()](#isApplyResolution--) | 获取或设置一个布尔值，指示图像在生成过程中是否使用分辨率 |
| [isBlackWhite()](#isBlackWhite--) | 获取一个布尔值，该值指示图像是否强制为黑白。 |
| [isBlackWhiteForGrayScale()](#isBlackWhiteForGrayScale--) | 尝试为灰度图像检测和使用 1bpp 编码默认值 == FALSE |
| [isFirstParagraphInColumn()](#isFirstParagraphInColumn--) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [isInLineParagraph()](#isInLineParagraph--) | 获取一个段落是内联的。 |
| [isInNewPage()](#isInNewPage--) | 获取强制此段落在新页面生成的 bool 值。 |
| [isKeptWithNext()](#isKeptWithNext--) | 获取一个布尔值，该值指示当前段落是否与下一段保持在同一页面中。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyResolution(boolean value)](#setApplyResolution-boolean-) | 获取或设置一个布尔值，指示图像在生成过程中是否使用分辨率 |
| [setBlackWhite(boolean value)](#setBlackWhite-boolean-) | 设置一个布尔值，指示图像是否强制为黑白。 |
| [setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)](#setBlackWhiteForGrayScale-boolean-) | 尝试对灰度图像检测并使用 1bpp 编码。 |
| [setBufferedImage(BufferedImage value)](#setBufferedImage-java.awt.image.BufferedImage-) | 设置 java awt 图像。 |
| [setFile(String value)](#setFile-java.lang.String-) | 设置图像文件。 |
| [setFileType(int value)](#setFileType-int-) | 设置图像文件类型。 |
| [setFirstParagraphInColumn(boolean value)](#setFirstParagraphInColumn-boolean-) | 获取或设置一个 bool 值，该值指示该段落是否位于下一列。 |
| [setFixHeight(double value)](#setFixHeight-double-) | 设置图像高度。 |
| [setFixWidth(double value)](#setFixWidth-double-) | 设置图像宽度。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置段落的水平对齐方式 |
| [setHyperlink(Hyperlink value)](#setHyperlink-com.aspose.pdf.Hyperlink-) | 设置超链接（用于 pdf 生成器）。 |
| [setImageScale(double value)](#setImageScale-double-) | 设置图像比例。 |
| [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | 设置图像流。 |
| [setInLineParagraph(boolean value)](#setInLineParagraph-boolean-) | 设置一个段落是内联的。 |
| [setInNewPage(boolean value)](#setInNewPage-boolean-) | 设置一个布尔值，强制此段落在新页面生成。 |
| [setKeptWithNext(boolean value)](#setKeptWithNext-boolean-) | 设置一个布尔值，指示当前段落是否与下一段保持在同一页面中。 |
| [setMargin(MarginInfo value)](#setMargin-com.aspose.pdf.MarginInfo-) | 设置段落的外边距（用于生成 pdf） |
| [setTitle(TextFragment value)](#setTitle-com.aspose.pdf.TextFragment-) | 设置指示图像标题的字符串值。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 设置段落的垂直对齐方式 |
| [setZIndex(int value)](#setZIndex-int-) | 设置一个指示图形 Z 顺序的 int 值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Image() {#Image--}
```
public Image()
```


默认构造函数

### convertToJpeg(InputStream value) {#convertToJpeg-java.io.InputStream-}
```
public static InputStream convertToJpeg(InputStream value)
```


尝试将 bmp/png/gif/tiff 图像流转换为 JPG 格式图像流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.InputStream | 输入流实例 |

**退货：**
java.io.InputStream - InputStream 实例
### deepClone() {#deepClone--}
```
public Object deepClone()
```


克隆图像。

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
### getBufferedImage() {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```


获取 java awt 图像。

**退货：**
java.awt.image.BufferedImage - BufferedImage 对象
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getFile() {#getFile--}
```
public String getFile()
```


获取图像文件。

**退货：**
java.lang.String - 字符串值
### getFileType() {#getFileType--}
```
public int getFileType()
```


获取图像文件类型。

**退货：**
int - 整数值
### getFixHeight() {#getFixHeight--}
```
public double getFixHeight()
```


获取图像高度。

**退货：**
双倍价值
### getFixWidth() {#getFixWidth--}
```
public double getFixWidth()
```


获取图像宽度。

**退货：**
双倍价值
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
### getImageScale() {#getImageScale--}
```
public double getImageScale()
```


获取图像比例。

**退货：**
双倍价值
### getImageStream() {#getImageStream--}
```
public InputStream getImageStream()
```


获取图像流。

**退货：**
java.io.InputStream - InputStream 对象
### getMargin() {#getMargin--}
```
public MarginInfo getMargin()
```


获取段落的外边距（用于生成 pdf）

**退货：**
[MarginInfo](../../com.aspose.pdf/margininfo) - 保证金信息值
### getMimeType(System.Drawing.Image i) {#getMimeType-com.aspose.ms.System.Drawing.Image-}
```
public static String getMimeType(System.Drawing.Image i)
```


返回图像的 MIME 类型。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| i | com.aspose.ms.System.Drawing.Image | 图像对象/ |

**退货：**
java.lang.String - 如果找到，Mime 类型为字符串；否则，“图像/未知”值。
### getTitle() {#getTitle--}
```
public TextFragment getTitle()
```


获取一个字符串值，该值指示图像的标题。

**退货：**
[TextFragment](../../com.aspose.pdf/textfragment) - TextFragment 值
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


获取段落的垂直对齐方式

**退货：**
int - VerticalAlignment 元素
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
### isApplyResolution() {#isApplyResolution--}
```
public boolean isApplyResolution()
```


获取或设置一个布尔值，指示图像在生成过程中是否使用分辨率

**退货：**
boolean - 布尔值
### isBlackWhite() {#isBlackWhite--}
```
public boolean isBlackWhite()
```


获取一个布尔值，该值指示图像是否强制为黑白。如果使用 CCITT 子格式的 TIFF 图像，则必须将此属性设置为 true。

**退货：**
boolean - 布尔值
### isBlackWhiteForGrayScale() {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```


尝试为灰度图像检测和使用 1bpp 编码默认值 == FALSE

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




### setApplyResolution(boolean value) {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```


获取或设置一个布尔值，指示图像在生成过程中是否使用分辨率

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setBlackWhite(boolean value) {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```


设置一个布尔值，指示图像是否强制为黑白。如果使用 CCITT 子格式的 TIFF 图像，则必须将此属性设置为 true。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale) {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```


尝试对灰度图像检测并使用 1bpp 编码。默认值 == 假

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| blackWhiteForGrayScale | boolean | 布尔值 |

### setBufferedImage(BufferedImage value) {#setBufferedImage-java.awt.image.BufferedImage-}
```
public void setBufferedImage(BufferedImage value)
```


设置 java awt 图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.awt.image.BufferedImage | BufferedImage 对象 |

### setFile(String value) {#setFile-java.lang.String-}
```
public void setFile(String value)
```


设置图像文件。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### setFileType(int value) {#setFileType-int-}
```
public void setFileType(int value)
```


设置图像文件类型。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setFirstParagraphInColumn(boolean value) {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```


获取或设置一个 bool 值，该值指示该段落是否位于下一列。默认为 false。（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setFixHeight(double value) {#setFixHeight-double-}
```
public void setFixHeight(double value)
```


设置图像高度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setFixWidth(double value) {#setFixWidth-double-}
```
public void setFixWidth(double value)
```


设置图像宽度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

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

### setImageScale(double value) {#setImageScale-double-}
```
public void setImageScale(double value)
```


设置图像比例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public void setImageStream(InputStream value)
```


设置图像流。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.io.InputStream | 输入流值 |

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

### setMargin(MarginInfo value) {#setMargin-com.aspose.pdf.MarginInfo-}
```
public void setMargin(MarginInfo value)
```


设置段落的外边距（用于生成 pdf）

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo 对象 |

### setTitle(TextFragment value) {#setTitle-com.aspose.pdf.TextFragment-}
```
public void setTitle(TextFragment value)
```


设置指示图像标题的字符串值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextFragment](../../com.aspose.pdf/textfragment) | 文本片段值 |

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
