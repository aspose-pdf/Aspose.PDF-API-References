---
title: StampInfo
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示邮票信息的类。
type: docs
weight: 60
url: /zh/java/com.aspose.pdf.facades/stampinfo/
---
**遗产：**
java.lang.Object
```
public final class StampInfo
```

表示邮票信息的类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getForm()](#getForm--) | 获取图章的 XForm。 |
| [getImage()](#getImage--) | 获取印章图像。 |
| [getImageInternal()](#getImageInternal--) | 获取印章图像。 |
| [getIndexOnPage()](#getIndexOnPage--) | 获取页面上的标记索引。 |
| [getRectangle()](#getRectangle--) | 获取放置图章的矩形。 |
| [getStampId()](#getStampId--) | 获取戳记的标识符。 |
| [getStampType()](#getStampType--) | 获取图章类型（图像/表格）。 |
| [getText()](#getText--) | 获取图章中的文本。 |
| [getVisible()](#getVisible--) | 获得邮票的可见性。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getForm() {#getForm--}
```
public XForm getForm()
```


获取图章的 XForm。

**退货：**
[XForm](../../com.aspose.pdf/xform) 变形对象
### getImage() {#getImage--}
```
public BufferedImage getImage()
```


获取印章图像。如果戳记不包含图像（例如文本戳记），则可能为空。

**退货：**
java.awt.image.BufferedImage - BufferedImage 对象
### getImageInternal() {#getImageInternal--}
```
public System.Drawing.Image getImageInternal()
```


获取印章图像。如果戳记不包含图像（例如文本戳记），则可能为空。

**退货：**
[Image](../../com.aspose.ms.system.drawing/image) - 图像对象
### getIndexOnPage() {#getIndexOnPage--}
```
public int getIndexOnPage()
```


获取页面上的标记索引。

**退货：**
int - 整数值
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


获取放置图章的矩形。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 矩形元素
### getStampId() {#getStampId--}
```
public int getStampId()
```


获取戳记的标识符。

**退货：**
int - 整数值
### getStampType() {#getStampType--}
```
public int getStampType()
```


获取图章类型（图像/表格）。

**退货：**
int - StampType 元素
### getText() {#getText--}
```
public String getText()
```


获取图章中的文本。

**退货：**
java.lang.String - 字符串值
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


获得邮票的可见性。如果为 false，则隐藏图章（使用 HideStampById）。隐藏的图章可以通过 ShowStampById 恢复。

**退货：**
boolean - 布尔值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
