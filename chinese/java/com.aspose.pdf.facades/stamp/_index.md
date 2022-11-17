---
title: Stamp
second_title: 用于 Java API 参考的 Aspose.PDF
description: 班级代表邮票。
type: docs
weight: 59
url: /zh/java/com.aspose.pdf.facades/stamp/
---
**遗产：**
java.lang.Object
```
public final class Stamp
```

班级代表邮票。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Stamp()](#Stamp--) | Stamp 对象的构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [bindImage(InputStream image)](#bindImage-java.io.InputStream-) | 设置将用作图章的图像。 |
| [bindImage(String imageFile)](#bindImage-java.lang.String-) | 将图像设置为图章。 |
| [bindLogo(FormattedText formattedText)](#bindLogo-com.aspose.pdf.facades.FormattedText-) | 将文本设置为图章。 |
| [bindPdf(InputStream pdfStream, int pageNumber)](#bindPdf-java.io.InputStream-int-) | 设置 PDF 文件和将用作图章的页数。 |
| [bindPdf(String pdfFile, int pageNumber)](#bindPdf-java.lang.String-int-) | 设置 PDF 文件和将用作图章的页数。 |
| [bindTextState(TextState textState)](#bindTextState-com.aspose.pdf.TextState-) | 设置戳记文本的文本状态。 |
| [close()](#close--) | 关闭这个实例 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendingSpace()](#getBlendingSpace--) | 获取一个 BlendingColorSpace 值，该值定义用于在页面上执行透明度和混合操作的颜色空间。 |
| [getClass()](#getClass--) |  |
| [getOpacity()](#getOpacity--) | 获取图章的不透明度。 |
| [getPageNumber()](#getPageNumber--) | 获取页码。 |
| [getPages()](#getPages--) | 获取包含将受标记影响的页数的数组。 |
| [getQuality()](#getQuality--) | 以百分比获取图像标记的质量。 |
| [getRotation()](#getRotation--) | 获取图章的旋转度数。 |
| [getStampId()](#getStampId--) | 获取邮票的标识符。 |
| [hashCode()](#hashCode--) |  |
| [isBackground()](#isBackground--) | 获取后台状态。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackground(boolean value)](#setBackground-boolean-) | 设置后台状态。 |
| [setBlendingSpace(int value)](#setBlendingSpace-int-) | 设置一个 BlendingColorSpace 值，该值定义用于在页面上执行透明度和混合操作的颜色空间。 |
| [setImageSize(float width, float height)](#setImageSize-float-float-) | 设置图像标记的大小。 |
| [setOpacity(float value)](#setOpacity-float-) | 设置图章的不透明度。 |
| [setOrigin(float originX, float originY)](#setOrigin-float-float-) | 设置页面上放置图章的位置。 |
| [setPageNumber(int value)](#setPageNumber-int-) | 设置页码。 |
| [setPages(int[] value)](#setPages-int---) | 设置包含将受标记影响的页数的数组。 |
| [setQuality(int value)](#setQuality-int-) | 以百分比设置图像标记的质量。 |
| [setRotation(float value)](#setRotation-float-) | 获取或设置图章的旋转度数。 |
| [setStampId(int value)](#setStampId-int-) | 设置邮票的标识符。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Stamp() {#Stamp--}
```
public Stamp()
```


Stamp 对象的构造函数。

### bindImage(InputStream image) {#bindImage-java.io.InputStream-}
```
public void bindImage(InputStream image)
```


设置将用作图章的图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | java.io.InputStream | 包含图像数据的流。 |

### bindImage(String imageFile) {#bindImage-java.lang.String-}
```
public void bindImage(String imageFile)
```


将图像设置为图章。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 Stamp stamp = new Stamp();
 stamp.bindImage("image.jpg");
 fileStamp.addStamp(stamp);
 fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| imageFile | java.lang.String | 图像文件名和路径。 |

### bindLogo(FormattedText formattedText) {#bindLogo-com.aspose.pdf.facades.FormattedText-}
```
public void bindLogo(FormattedText formattedText)
```


将文本设置为图章。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formattedText | [FormattedText](../../com.aspose.pdf.facades/formattedtext) | 指定文本和文本属性的 FormattedText 对象。 |

### bindPdf(InputStream pdfStream, int pageNumber) {#bindPdf-java.io.InputStream-int-}
```
public void bindPdf(InputStream pdfStream, int pageNumber)
```


设置 PDF 文件和将用作图章的页数。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 Stamp stamp = new Stamp();
 //第一页将用作邮票。
 InputStream stream = new FileInputStream("stamp.pdf");
 stamp.bindPdf(stream, 1);
 fileStamp.addStamp(stamp);
 fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfStream | java.io.InputStream | 包含 PDF 文档的流。 |
| pageNumber | int | 将用作图章的文档的页面索引。 |

### bindPdf(String pdfFile, int pageNumber) {#bindPdf-java.lang.String-int-}
```
public void bindPdf(String pdfFile, int pageNumber)
```


设置 PDF 文件和将用作图章的页数。

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 Stamp stamp = new Stamp();
 //第一页将用作邮票。
 stamp.bindPdf("stamp.pdf", 1);
 stamp.isBackground (true);
 fileStamp.addStamp(stamp);
 fileStamp.close();
```

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfFile | java.lang.String | PDF 文件的路径。 |
| pageNumber | int | PDF 文件中的页数 |

### bindTextState(TextState textState) {#bindTextState-com.aspose.pdf.TextState-}
```
public void bindTextState(TextState textState)
```


设置戳记文本的文本状态。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| textState | [TextState](../../com.aspose.pdf/textstate) | 指定文本属性的 TextState 对象。 |

### close() {#close--}
```
public void close()
```


关闭这个实例

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
### getBlendingSpace() {#getBlendingSpace--}
```
public int getBlendingSpace()
```


获取一个 BlendingColorSpace 值，该值定义用于在页面上执行透明度和混合操作的颜色空间。

**退货：**
int - 整数值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


获取图章的不透明度。

**退货：**
float - 浮点值
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


获取页码。

**退货：**
int - 整数值
### getPages() {#getPages--}
```
public int[] getPages()
```


获取包含将受标记影响的页数的数组。

**退货：**
整数[] - 整数数组
### getQuality() {#getQuality--}
```
public int getQuality()
```


以百分比获取图像标记的质量。价值 0..100%。

**退货：**
int - 整数值
### getRotation() {#getRotation--}
```
public float getRotation()
```


获取图章的旋转度数。

**退货：**
float - 浮点值
### getStampId() {#getStampId--}
```
public int getStampId()
```


获取邮票的标识符。

**退货：**
int - 整数值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isBackground() {#isBackground--}
```
public boolean isBackground()
```


获取后台状态。如果为真，邮票将作为垃圾邮件页面的背景放置。默认情况下设置为 false。

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




### setBackground(boolean value) {#setBackground-boolean-}
```
public void setBackground(boolean value)
```


设置后台状态。如果为真，邮票将作为垃圾邮件页面的背景放置。默认情况下设置为 false。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setBlendingSpace(int value) {#setBlendingSpace-int-}
```
public void setBlendingSpace(int value)
```


设置一个 BlendingColorSpace 值，该值定义用于在页面上执行透明度和混合操作的颜色空间。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setImageSize(float width, float height) {#setImageSize-float-float-}
```
public void setImageSize(float width, float height)
```


设置图像标记的大小。图像将根据指定的值进行缩放。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | float | 图像宽度。 |
| height | float | 图像高度。 |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


设置图章的不透明度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | 浮点值 |

### setOrigin(float originX, float originY) {#setOrigin-float-float-}
```
public void setOrigin(float originX, float originY)
```


设置页面上放置图章的位置。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| originX | float | 图章的 X 坐标。 |
| originY | float | 图章的 Y 坐标。 |

### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


设置页码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


设置包含将受标记影响的页数的数组。如果 Pages = null 文档的所有页面都会受到影响。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int[] | 整型数组

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
 Stamp stamp = new com.aspose.pdf.facades.Stamp();
 stamp.bindLogo(new FormattedText(text));
 //只在第 1、4 和 6 页上盖章。
 stamp.setPages(new int[] { 1, 4, 6 });
 fileStamp.addStamp(stamp);
 fileStamp.close();
``` |

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int 值)
```


Sets quality of image stamp in percent. Valiued values 0..100%.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setRotation(float value) {#setRotation-float-}
```
public void setRotation（浮动值）
```


Gets or sets rotation of the stamp in degrees.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value

--------------------

```
PdfFileStamp fileStamp = new PdfFileStamp("输入.pdf", "输出.pdf");
 邮票 stamp = new Stamp();
 stamp.bindLogo(new FormattedText("STAMP"));
 stamp.setRotation(90);
 fileStamp.addStamp(邮票);
 文件戳.close();
``` |

### setStampId(int value) {#setStampId-int-}
```
public void setStampId(int 值)
```


Sets identifier of stamp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### toString() {#toString--}
```
公共字符串 toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
公共最终无效等待（）
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
公共最终无效等待（长 arg0，int arg1）
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
