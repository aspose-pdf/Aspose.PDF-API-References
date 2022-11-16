---
title: XImage
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示图像 X 对象的类。
type: docs
weight: 409
url: /zh/java/com.aspose.pdf/ximage/
---
**遗产：**
java.lang.Object
```
public final class XImage
```

表示图像 X 对象的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XImage(IPdfDataStream image)](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) | 仅供内部使用 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [containsTransparency()](#containsTransparency--) | 如果图像包含透明度则返回 true；否则，假的。 |
| [delete()](#delete--) | 从父集合中删除图像。 |
| [detectColorType(BufferedImage bmp)](#detectColorType-java.awt.image.BufferedImage-) | 返回图像的颜色类型。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | 返回图像的颜色类型。 |
| [getEngineImg()](#getEngineImg--) | 描述图像的 IPDFImage 对象。 |
| [getFilterType()](#getFilterType--) | 获取图像过滤器类型。 |
| [getGrayscaled()](#getGrayscaled--) | 获取图像的灰度版本。 |
| [getHeight()](#getHeight--) | 获取图像的高度。 |
| [getImage()](#getImage--) | 仅限内部使用 |
| [getMetadata()](#getMetadata--) | 图像的元数据。 |
| [getName()](#getName--) | 获取图像名称。 |
| [getNameInCollection()](#getNameInCollection--) | 返回其集合中图像的名称。 |
| [getRawBytes()](#getRawBytes--) | 返回图像的原始字节而不进行解码。 |
| [getRawParameters()](#getRawParameters--) | 获取原始图像参数 |
| [getWidth()](#getWidth--) | 获取图像的宽度。 |
| [hashCode()](#hashCode--) |  |
| [isImage(IPdfPrimitive primitive)](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | 如果图元是图像，则返回 true。 |
| [isTheSameObject(XImage image)](#isTheSameObject-com.aspose.pdf.XImage-) | 如果两个图像都引用同一个对象，则返回 true。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rename(String name)](#rename-java.lang.String-) | 重命名图像并用新名称替换对图像的所有引用 |
| [replace(InputStream image)](#replace-java.io.InputStream-) | 将图像替换到图像中指定的流中。 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 将图像数据作为 JPEG 图像保存到流中。 |
| [save(OutputStream stream, ImageType format)](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | 以请求的格式将图像保存到流中。 |
| [save(OutputStream stream, ImageType format, int resolution)](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | 以请求的格式将图像保存到流中。 |
| [save(OutputStream stream, float xDpi, float yDpi)](#save-java.io.OutputStream-float-float-) | 以请求的格式将图像保存到流中。 |
| [save(OutputStream stream, int resolution)](#save-java.io.OutputStream-int-) | 以指定的分辨率以请求的格式将图像保存到流中。 |
| [saveInternal(System.IO.Stream stream, ImageType format, int resolution)](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [saveInternal(System.IO.Stream stream, int resolution)](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | 将图像数据以指定分辨率的 JPEG 图像保存到流中。 |
| [setName(String value)](#setName-java.lang.String-) | 设置图像名称。 |
| [toStream()](#toStream--) | 返回原始图像流。 |
| [toString()](#toString--) | 返回一个字符串表示 XImage 对象的属性。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XImage(IPdfDataStream image) {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
```
public XImage(IPdfDataStream image)
```


仅供内部使用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | [IPdfDataStream](../../com.aspose.pdf.engine.data/ipdfdatastream) | 内部实例 |

### containsTransparency() {#containsTransparency--}
```
public boolean containsTransparency()
```


如果图像包含透明度则返回 true；否则，假的。

**退货：**
boolean - 布尔值
### delete() {#delete--}
```
public void delete()
```


从父集合中删除图像。

### detectColorType(BufferedImage bmp) {#detectColorType-java.awt.image.BufferedImage-}
```
public static int detectColorType(BufferedImage bmp)
```


返回图像的颜色类型。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| bmp | java.awt.image.BufferedImage | 图片。 |

**退货：**
int - 颜色类型。
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
### getColorType() {#getColorType--}
```
public int getColorType()
```


返回图像的颜色类型。

**退货：**
int - 颜色类型值。
### getEngineImg() {#getEngineImg--}
```
public IPdfDataStream getEngineImg()
```


描述图像的 IPDFImage 对象。仅限内部

**退货：**
[IPdfDataStream](../../com.aspose.pdf.engine.data/ipdfdatastream) IPdfDataStream
### getFilterType() {#getFilterType--}
```
public final int getFilterType()
```


获取图像过滤器类型。

**退货：**
int - ImageFilterType 元素
### getGrayscaled() {#getGrayscaled--}
```
public BufferedImage getGrayscaled()
```


获取图像的灰度版本。

**退货：**
java.awt.image.BufferedImage - 缓冲图像
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取图像的高度。

**退货：**
int - 整数值
### getImage() {#getImage--}
```
public System.Drawing.Bitmap getImage()
```


仅限内部使用

**退货：**
com.aspose.ms.System.Drawing.Bitmap - 图片
### getMetadata() {#getMetadata--}
```
public final Metadata getMetadata()
```


图像的元数据。

**退货：**
[Metadata](../../com.aspose.pdf/metadata) 元数据实例
### getName() {#getName--}
```
public String getName()
```


获取图像名称。请注意，如果您更改页面内容中引用的图像的名称，文档可能会变得不正确。请在这种情况下使用 XImage.Rename 方法。

**退货：**
java.lang.String - 字符串
### getNameInCollection() {#getNameInCollection--}
```
public String getNameInCollection()
```


返回其集合中图像的名称。

**退货：**
java.lang.String - 图像键（名称）。
### getRawBytes() {#getRawBytes--}
```
public byte[] getRawBytes()
```


返回图像的原始字节而不进行解码。

**退货：**
字节[] - 字节数组
### getRawParameters() {#getRawParameters--}
```
public XImage.RawParameters getRawParameters()
```


获取原始图像参数

**退货：**
[RawParameters](../../com.aspose.pdf/rawparameters) 原始参数实例
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取图像的宽度。

**退货：**
int - 整数值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isImage(IPdfPrimitive primitive) {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public static boolean isImage(IPdfPrimitive primitive)
```


如果图元是图像，则返回 true。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| primitive | [IPdf原语](../../com.aspose.pdf.engine.data/ipdfprimitive) | IPdfPrimitive |

**退货：**
布尔值 - 布尔值
### isTheSameObject(XImage image) {#isTheSameObject-com.aspose.pdf.XImage-}
```
public boolean isTheSameObject(XImage image)
```


如果两个图像都引用同一个对象，则返回 true。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | [XImage](../../com.aspose.pdf/ximage) | 要与“此”图像进行比较的图像。 |

**退货：**
boolean - 布尔值，如果图像引用同一对象则为真。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### rename(String name) {#rename-java.lang.String-}
```
public final void rename(String name)
```


重命名图像并用新名称替换对图像的所有引用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 新图像名称。 |

### replace(InputStream image) {#replace-java.io.InputStream-}
```
public void replace(InputStream image)
```


将图像替换到图像中指定的流中。

\*

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | java.io.InputStream | 流式传输图像数据。 |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


将图像数据作为 JPEG 图像保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 将保存图像数据的流。 |

### save(OutputStream stream, ImageType format) {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
```
public void save(OutputStream stream, ImageType format)
```


以请求的格式将图像保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 将保存图像的流 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 将用于图像编码的格式。 |

### save(OutputStream stream, ImageType format, int resolution) {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
```
public void save(OutputStream stream, ImageType format, int resolution)
```


以请求的格式将图像保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 将保存图像的流 |
| format | [ImageType](../../com.aspose.pdf/imagetype) | 将用于图像编码的格式。 |
| resolution | int | 图像分辨率 |

### save(OutputStream stream, float xDpi, float yDpi) {#save-java.io.OutputStream-float-float-}
```
public void save(OutputStream stream, float xDpi, float yDpi)
```


以请求的格式将图像保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 将保存图像的 OutputStream |
| xDpi | float | 图像水平分辨率 |
| yDpi | float | 图像垂直分辨率 |

### save(OutputStream stream, int resolution) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int resolution)
```


以指定的分辨率以请求的格式将图像保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.OutputStream | 将保存图像的流 |
| resolution | int | 图像分辨率 |

### saveInternal(System.IO.Stream stream, ImageType format, int resolution) {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-}
```
public void saveInternal(System.IO.Stream stream, ImageType format, int resolution)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| format | [ImageType](../../com.aspose.pdf/imagetype) |  |
| resolution | int |  |

### saveInternal(System.IO.Stream stream, int resolution) {#saveInternal-com.aspose.ms.System.IO.Stream-int-}
```
public void saveInternal(System.IO.Stream stream, int resolution)
```


将图像数据以指定分辨率的 JPEG 图像保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | 将保存图像数据的流。 |
| resolution | int | 图像分辨率 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置图像名称。请注意，如果您更改页面内容中引用的图像的名称，文档可能会变得不正确。请在这种情况下使用 XImage.Rename 方法。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值 |

### toStream() {#toStream--}
```
public InputStream toStream()
```


返回原始图像流。

**退货：**
java.io.InputStream - 原始图像流。
### toString() {#toString--}
```
public String toString()
```


返回一个字符串表示 XImage 对象的属性。

**退货：**
java.lang.String - 字符串实例
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
