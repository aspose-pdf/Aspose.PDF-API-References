---
title: Watermark
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示页面的水印。
type: docs
weight: 401
url: /zh/java/com.aspose.pdf/watermark/
---
**遗产：**
java.lang.Object
```
public class Watermark
```

表示页面的水印。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Watermark(BufferedImage nativeImage, Rectangle rect)](#Watermark-java.awt.image.BufferedImage-com.aspose.pdf.Rectangle-) | 使用图像及其在页面上的位置初始化水印对象。 |
| [Watermark(BufferedImage nativeImage)](#Watermark-java.awt.image.BufferedImage-) | 使用图像初始化水印结构。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAvailable()](#getAvailable--) | 获取存在水印的标志。 |
| [getClass()](#getClass--) |  |
| [getImage()](#getImage--) | 获取水印图像。 |
| [getPosition()](#getPosition--) | 获取页面上水印图像的位置。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Watermark(BufferedImage nativeImage, Rectangle rect) {#Watermark-java.awt.image.BufferedImage-com.aspose.pdf.Rectangle-}
```
public Watermark(BufferedImage nativeImage, Rectangle rect)
```


使用图像及其在页面上的位置初始化水印对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| nativeImage | java.awt.image.BufferedImage | 图像 水印图像。 |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 水印在页面上的位置。 |

### Watermark(BufferedImage nativeImage) {#Watermark-java.awt.image.BufferedImage-}
```
public Watermark(BufferedImage nativeImage)
```


使用图像初始化水印结构。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| nativeImage | java.awt.image.BufferedImage | 图像 水印图像。 |

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
### getAvailable() {#getAvailable--}
```
public boolean getAvailable()
```


获取存在水印的标志。

**退货：**
boolean - 布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getImage() {#getImage--}
```
public BufferedImage getImage()
```


获取水印图像。

**退货：**
java.awt.image.BufferedImage - BufferedImage 对象
### getPosition() {#getPosition--}
```
public Rectangle getPosition()
```


获取页面上水印图像的位置。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 矩形对象
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
