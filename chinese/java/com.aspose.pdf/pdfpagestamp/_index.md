---
title: PdfPageStamp
second_title: 用于 Java API 参考的 Aspose.PDF
description: 类表示使用 PDF 页面作为图章的图章。
type: docs
weight: 279
url: /zh/java/com.aspose.pdf/pdfpagestamp/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.Stamp](../../com.aspose.pdf/stamp)
```
public final class PdfPageStamp extends Stamp
```

类表示使用 PDF 页面作为图章的图章。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfPageStamp(Page pdfPage)](#PdfPageStamp-com.aspose.pdf.Page-) | PdfPageStamp 的构造函数。 |
| [PdfPageStamp(String fileName, int pageIndex)](#PdfPageStamp-java.lang.String-int-) | 从指定文件中文档的指定页面创建 Pdf 页面戳记。 |
| [PdfPageStamp(InputStream stream, int pageIndex)](#PdfPageStamp-java.io.InputStream-int-) | 从流中的文档中的指定页面创建 Pdf 页面戳记。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) | 关闭实例 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottomMargin()](#getBottomMargin--) | 获取图章的底部边距。 |
| [getClass()](#getClass--) |  |
| [getHeight()](#getHeight--) | 获取页面上图章所需的高度。 |
| [getHorizontalAlignment()](#getHorizontalAlignment--) | 获取页面上图章的水平对齐方式。 |
| [getLeftMargin()](#getLeftMargin--) | 获取邮票的左边距。 |
| [getOpacity()](#getOpacity--) | 获取一个值以指示图章不透明度。 |
| [getOutlineOpacity()](#getOutlineOpacity--) | 获取一个值以指示图章轮廓不透明度。 |
| [getOutlineWidth()](#getOutlineWidth--) | 获取图章轮廓宽度的值。 |
| [getPdfPage()](#getPdfPage--) | 获取将用作图章的页面。 |
| [getRightMargin()](#getRightMargin--) | 获取邮票的右边距。 |
| [getRotate()](#getRotate--) | 根据旋转值获取图章内容的旋转。 |
| [getRotateAngle()](#getRotateAngle--) | 获取图章的旋转角度（以度为单位）。 |
| [getStampId()](#getStampId--) | 获取邮票 ID。 |
| [getTopMargin()](#getTopMargin--) | 获取邮票的上边距。 |
| [getVerticalAlignment()](#getVerticalAlignment--) | 获取页面上图章的垂直对齐方式。 |
| [getWidth()](#getWidth--) | 获取页面上图章所需的宽度。 |
| [getXIndent()](#getXIndent--) | 获取水平标记坐标，从左侧开始。 |
| [getYIndent()](#getYIndent--) | 从底部开始获取垂直图章坐标。 |
| [getZoom()](#getZoom--) | 获取图章的缩放因子。 |
| [getZoomX()](#getZoomX--) | 获取图章的水平缩放因子。 |
| [getZoomY()](#getZoomY--) | 获取图章的垂直缩放因子。 |
| [hashCode()](#hashCode--) |  |
| [isBackground()](#isBackground--) | 获取一个 bool 值，指示内容被标记为背景。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [put(Page page)](#put-com.aspose.pdf.Page-) | 在指定的页面上盖章。 |
| [setBackground(boolean value)](#setBackground-boolean-) | 设置一个 bool 值，指示内容被标记为背景。 |
| [setBottomMargin(double value)](#setBottomMargin-double-) | 设置图章的下边距。 |
| [setHeight(double value)](#setHeight-double-) | 设置页面上图章的所需高度。 |
| [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 设置页面上图章的水平对齐方式。 |
| [setLeftMargin(double value)](#setLeftMargin-double-) | 设置图章的左边距。 |
| [setOpacity(double value)](#setOpacity-double-) | 设置一个值以指示图章不透明度。 |
| [setOutlineOpacity(double value)](#setOutlineOpacity-double-) | 设置一个值以指示图章轮廓不透明度。 |
| [setOutlineWidth(double value)](#setOutlineWidth-double-) | 设置图章轮廓宽度的值。 |
| [setPdfPage(Page value)](#setPdfPage-com.aspose.pdf.Page-) | 设置将用作图章的页面。 |
| [setRightMargin(double value)](#setRightMargin-double-) | 设置图章的右边距。 |
| [setRotate(int value)](#setRotate-int-) | 根据旋转值设置图章内容的旋转。 |
| [setRotateAngle(double value)](#setRotateAngle-double-) | 设置图章的旋转角度（以度为单位）。 |
| [setStampId(int value)](#setStampId-int-) | 设置戳记 ID。 |
| [setTopMargin(double value)](#setTopMargin-double-) | 设置图章的上边距。 |
| [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 设置页面上图章的垂直对齐方式。 |
| [setWidth(double value)](#setWidth-double-) | 设置页面上图章的所需宽度。 |
| [setXIndent(double value)](#setXIndent-double-) | 设置水平标记坐标，从左侧开始。 |
| [setYIndent(double value)](#setYIndent-double-) | 设置垂直图章坐标，从底部开始。 |
| [setZoom(double value)](#setZoom-double-) | 获取图章的缩放因子。 |
| [setZoomX(double value)](#setZoomX-double-) | 设置图章的水平缩放系数。 |
| [setZoomY(double value)](#setZoomY-double-) | 设置图章的垂直缩放系数。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfPageStamp(Page pdfPage) {#PdfPageStamp-com.aspose.pdf.Page-}
```
public PdfPageStamp(Page pdfPage)
```


PdfPageStamp 的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pdfPage | [Page](../../com.aspose.pdf/page) | 用于冲压的页面。 |

### PdfPageStamp(String fileName, int pageIndex) {#PdfPageStamp-java.lang.String-int-}
```
public PdfPageStamp(String fileName, int pageIndex)
```


从指定文件中文档的指定页面创建 Pdf 页面戳记。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileName | java.lang.String | PDF 文件的名称和页面。 |
| pageIndex | int | 页面索引。 |

### PdfPageStamp(InputStream stream, int pageIndex) {#PdfPageStamp-java.io.InputStream-int-}
```
public PdfPageStamp(InputStream stream, int pageIndex)
```


从流中的文档中的指定页面创建 Pdf 页面戳记。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含 PDF 的流 |
| pageIndex | int | 页面索引。 |

### close() {#close--}
```
public void close()
```


关闭实例

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
### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


获取图章的底部边距。

**退货：**
双倍价值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getHeight() {#getHeight--}
```
public double getHeight()
```


获取页面上图章所需的高度。

**退货：**
双倍价值
### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public int getHorizontalAlignment()
```


获取页面上图章的水平对齐方式。

**退货：**
int - HorizontalAlignment 值
### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


获取邮票的左边距。

**退货：**
双倍价值
### getOpacity() {#getOpacity--}
```
public double getOpacity()
```


获取一个值以指示图章不透明度。该值从 0.0 到 1.0。默认情况下，该值为 1.0。

**退货：**
双倍价值
### getOutlineOpacity() {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```


获取一个值以指示图章轮廓不透明度。该值从 0.0 到 1.0。默认情况下，该值为 1.0。

**退货：**
双倍价值
### getOutlineWidth() {#getOutlineWidth--}
```
public double getOutlineWidth()
```


获取图章轮廓宽度的值。默认情况下，该值为 1.0。

**退货：**
双倍价值
### getPdfPage() {#getPdfPage--}
```
public Page getPdfPage()
```


获取将用作图章的页面。

**退货：**
[Page](../../com.aspose.pdf/page) 页面价值
### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


获取邮票的右边距。

**退货：**
双倍价值
### getRotate() {#getRotate--}
```
public int getRotate()
```


根据旋转值获取图章内容的旋转。笔记。此属性适用于 90 度的倍数（0、90、180、270 度）的设置角度。要设置任意角度，请使用 RotateAngle 属性。如果 ArbitraryAngle 设置的角度不是 90 的倍数，则 Rotate 属性返回 Rotation.None。

**退货：**
int - 旋转值
### getRotateAngle() {#getRotateAngle--}
```
public double getRotateAngle()
```


获取图章的旋转角度（以度为单位）。此属性允许设置任意旋转角度。

**退货：**
双倍价值
### getStampId() {#getStampId--}
```
public int getStampId()
```


获取邮票 ID。

**退货：**
int - 邮票的标识符。
### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


获取邮票的上边距。

**退货：**
双倍价值
### getVerticalAlignment() {#getVerticalAlignment--}
```
public int getVerticalAlignment()
```


获取页面上图章的垂直对齐方式。

**退货：**
int - VerticalAlignment 值
### getWidth() {#getWidth--}
```
public double getWidth()
```


获取页面上图章所需的宽度。

**退货：**
双倍价值
### getXIndent() {#getXIndent--}
```
public double getXIndent()
```


获取水平标记坐标，从左侧开始。

**退货：**
双倍价值
### getYIndent() {#getYIndent--}
```
public double getYIndent()
```


从底部开始获取垂直图章坐标。

**退货：**
双倍价值
### getZoom() {#getZoom--}
```
public double getZoom()
```


获取图章的缩放因子。允许缩放图章。请注意，一对属性 ZoomX 和 ZoomY 允许分别为每个轴设置缩放因子。此属性的设置会同时更改 ZoomX 和 ZoomY 属性。如果 ZoomX 和 ZoomY 不同，则 Zoom 属性返回 ZoomX 值。

**退货：**
双倍价值
### getZoomX() {#getZoomX--}
```
public double getZoomX()
```


获取图章的水平缩放因子。允许水平缩放图章。

**退货：**
双倍价值
### getZoomY() {#getZoomY--}
```
public double getZoomY()
```


获取图章的垂直缩放因子。允许垂直缩放图章。

**退货：**
双倍价值
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


获取一个 bool 值，指示内容被标记为背景。如果该值为 true，则戳记内容位于底部。默认情况下，该值为 false，戳记内容位于顶部。

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




### put(Page page) {#put-com.aspose.pdf.Page-}
```
public void put(Page page)
```


在指定的页面上盖章。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 放置邮票的页面。 |

### setBackground(boolean value) {#setBackground-boolean-}
```
public void setBackground(boolean value)
```


设置一个 bool 值，指示内容被标记为背景。如果该值为 true，则戳记内容位于底部。默认情况下，该值为 false，戳记内容位于顶部。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setBottomMargin(double value) {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```


设置图章的下边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


设置页面上图章的所需高度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public void setHorizontalAlignment(int value)
```


设置页面上图章的水平对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | HorizontalAlignment 值 |

### setLeftMargin(double value) {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```


设置图章的左边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setOpacity(double value) {#setOpacity-double-}
```
public void setOpacity(double value)
```


设置一个值以指示图章不透明度。该值从 0.0 到 1.0。默认情况下，该值为 1.0。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setOutlineOpacity(double value) {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```


设置一个值以指示图章轮廓不透明度。该值从 0.0 到 1.0。默认情况下，该值为 1.0。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setOutlineWidth(double value) {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```


设置图章轮廓宽度的值。默认情况下，该值为 1.0。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setPdfPage(Page value) {#setPdfPage-com.aspose.pdf.Page-}
```
public void setPdfPage(Page value)
```


设置将用作图章的页面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [Page](../../com.aspose.pdf/page) | 页面对象 |

### setRightMargin(double value) {#setRightMargin-double-}
```
public void setRightMargin(double value)
```


设置图章的右边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setRotate(int value) {#setRotate-int-}
```
public void setRotate(int value)
```


根据旋转值设置图章内容的旋转。笔记。此属性适用于 90 度的倍数（0、90、180、270 度）的设置角度。要设置任意角度，请使用 RotateAngle 属性。如果 ArbitraryAngle 设置的角度不是 90 的倍数，则 Rotate 属性返回 Rotation.None。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setRotateAngle(double value) {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```


设置图章的旋转角度（以度为单位）。此属性允许设置任意旋转角度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 旋转角度 |

### setStampId(int value) {#setStampId-int-}
```
public void setStampId(int value)
```


设置戳记 ID。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | Stamp ID 的新值。 |

### setTopMargin(double value) {#setTopMargin-double-}
```
public void setTopMargin(double value)
```


设置图章的上边距。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public void setVerticalAlignment(int value)
```


设置页面上图章的垂直对齐方式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | VerticalAlignment 值 |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


设置页面上图章的所需宽度。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setXIndent(double value) {#setXIndent-double-}
```
public void setXIndent(double value)
```


设置水平标记坐标，从左侧开始。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setYIndent(double value) {#setYIndent-double-}
```
public void setYIndent(double value)
```


设置垂直图章坐标，从底部开始。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setZoom(double value) {#setZoom-double-}
```
public void setZoom(double value)
```


获取图章的缩放因子。允许缩放图章。请注意，一对属性 ZoomX 和 ZoomY 允许分别为每个轴设置缩放因子。此属性的设置会同时更改 ZoomX 和 ZoomY 属性。如果 ZoomX 和 ZoomY 不同，则 Zoom 属性返回 ZoomX 值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setZoomX(double value) {#setZoomX-double-}
```
public void setZoomX(double value)
```


设置图章的水平缩放系数。允许水平缩放图章。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

### setZoomY(double value) {#setZoomY-double-}
```
public void setZoomY(double value)
```


设置图章的垂直缩放系数。允许垂直缩放图章。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双倍价值 |

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
