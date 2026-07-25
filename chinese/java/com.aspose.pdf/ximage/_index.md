---
title: "XImage"
linktitle: "XImage"
second_title: "Aspose.PDF for Java API 参考"
description: "表示图像 X-Object 的类。"
type: docs
weight: 5610
url: /zh/java/com.aspose.pdf/ximage/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImage

```
public final class XImage extends Object
```

表示图像 X-Object 的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XImage](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) | 仅供内部使用 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [addStencilMask](#addStencilMask-java.io.InputStream-) | 向 XImage 添加模板遮罩。 |
| [containsTransparency](#containsTransparency--) | 如果图像包含透明度，则返回 true；否则返回 false。 |
| [delete](#delete--) | 从父集合中删除图像。 |
| [detectColorType](#detectColorType-java.awt.image.BufferedImage-) | 返回图像的颜色类型。 |
| [getAlternativeText](#getAlternativeText-com.aspose.pdf.Page-) | 返回一个字符串列表，包含 XImage 的替代文本。 |
| [getColorType](#getColorType--) | 返回图像的颜色类型。 |
| [getEngineImg](#getEngineImg--) | IPPdfImage 对象描述图像。仅供内部使用 |
| [getFilterType](#getFilterType--) | 获取图像过滤器类型。 |
| [getGrayscaled](#getGrayscaled--) | 获取图像的灰度版本。 |
| [getHeight](#getHeight--) | 获取图像的高度。 |
| [getImage](#getImage--) | 仅供内部使用 |
| [getMetadata](#getMetadata--) | 图像的元数据。 |
| [getName](#getName--) | 获取图像名称。请注意，如果更改了在页面内容中有引用的图像名称，文档可能会变得不正确。在这种情况下，请使用 XImage.Rename 方法。 |
| [getNameInCollection](#getNameInCollection--) | 返回图像在其集合中的名称。 |
| [getRawBytes](#getRawBytes--) | 返回未解码的图像原始字节。 |
| [getRawImageData](#getRawImageData--) | 从源图像检索原始图像数据。 |
| [getRawParameters](#getRawParameters--) | 获取原始图像参数 |
| [getWidth](#getWidth--) | 获取图像的宽度。 |
| [isImage](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | 如果原语是图像，则返回 true。 |
| [isImageMask](#isImageMask--) | 获取一个标志，指示图像是否应被视为图像遮罩（参见 8.9.6，"Masked Images"）。如果此标志为 true，则 BitsPerComponent 的值应为 1，且不得指定 Mask 和 ColorSpace；未遮罩的区域应使用当前非描边颜色进行绘制。默认值：false。取值：True 表示图像是图像遮罩。 |
| [isTheSameObject](#isTheSameObject-com.aspose.pdf.XImage-) | 如果两个图像引用同一对象，则返回 true。 |
| [rename](#rename-java.lang.String-) | 重命名图像并将所有对该图像的引用替换为新名称 |
| [replace](#replace-java.io.InputStream-) | 将图像替换到 {@code image} 指定的流中。 * |
| [save](#save-java.io.OutputStream-) | 将图像数据以 JPEG 图像的形式保存到流中。 |
| [save](#save-java.io.OutputStream-float-float-) | 将图像保存到流中，使用请求的格式。 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | 将图像保存到流中，使用请求的格式。 |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | 将图像保存到流中，使用请求的格式。 |
| [save](#save-java.io.OutputStream-int-) | 将图像保存到流中，使用请求的格式和指定的分辨率。 |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-) | 将图像保存到流中，使用请求的格式。 |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | 将图像数据保存到流中，作为 JPEG 图像并使用指定的分辨率。 |
| [setName](#setName-java.lang.String-) | 设置图像名称。请注意，如果更改在页面内容中有引用的图像的名称，文档可能会变得不正确。在这种情况下请使用 XImage.Rename 方法。 |
| [toStream](#toStream--) | 返回原始图像流。 |
| [toString](#toString--) | 返回 XImage 对象属性的字符串表示形式。 |
| [trySetAlternativeText](#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-) | 为页面上的 XImage 设置替代文本。 |

### XImage {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
仅供内部使用

### addStencilMask {#addStencilMask-java.io.InputStream-}
向 XImage 添加模板遮罩。

### containsTransparency {#containsTransparency--}
```
public boolean containsTransparency()
```

如果图像包含透明度，则返回 true；否则返回 false。

**Returns:**
布尔值

### delete {#delete--}
```
public void delete()
```

从父集合中删除图像。

### detectColorType {#detectColorType-java.awt.image.BufferedImage-}
返回图像的颜色类型。

### getAlternativeText {#getAlternativeText-com.aspose.pdf.Page-}
返回一个字符串列表，包含 XImage 的替代文本。

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

返回图像的颜色类型。

**Returns:**
颜色类型的值。

### getEngineImg {#getEngineImg--}
```
public com.aspose.pdf.engine.data.IPdfDataStream getEngineImg()
```

IPPdfImage 对象描述图像。仅供内部使用

**Returns:**
IPdfDataStream

### getFilterType {#getFilterType--}
```
public final ImageFilterType getFilterType()
```

获取图像过滤器类型。

**Returns:**
ImageFilterType 元素

### getGrayscaled {#getGrayscaled--}
```
public BufferedImage getGrayscaled()
```

获取图像的灰度版本。

**Returns:**
BufferedImage

### getHeight {#getHeight--}
```
public int getHeight()
```

获取图像的高度。

**Returns:**
int 值

### getImage {#getImage--}
```
public com.aspose.ms.System.Drawing.Bitmap getImage()
```

仅供内部使用

**Returns:**
Image

### getMetadata {#getMetadata--}
```
public final Metadata getMetadata()
```

图像的元数据。

**Returns:**
Metadata 实例

### getName {#getName--}
```
public String getName()
```

获取图像名称。请注意，如果更改了在页面内容中有引用的图像名称，文档可能会变得不正确。在这种情况下，请使用 XImage.Rename 方法。

**Returns:**
字符串

### getNameInCollection {#getNameInCollection--}
```
public String getNameInCollection()
```

返回图像在其集合中的名称。

**Returns:**
图像键（名称）。

### getRawBytes {#getRawBytes--}
```
public byte[] getRawBytes()
```

返回未解码的图像原始字节。

**Returns:**
字节数组

### getRawImageData {#getRawImageData--}
```
public final byte[] getRawImageData()
```

从源图像检索原始图像数据。

**Returns:**
包含原始图像数据的 {@link byte[]}。

### getRawParameters {#getRawParameters--}
```
public XImage.RawParameters getRawParameters()
```

获取原始图像参数

**Returns:**
RawParameters 实例

### getWidth {#getWidth--}
```
public int getWidth()
```

获取图像的宽度。

**Returns:**
int 值

### isImage {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
如果原语是图像，则返回 true。

### isImageMask {#isImageMask--}
```
public final boolean isImageMask()
```

获取一个标志，指示图像是否应被视为图像遮罩（参见 8.9.6，"Masked Images"）。如果此标志为 true，则 BitsPerComponent 的值应为 1，且不得指定 Mask 和 ColorSpace；未遮罩的区域应使用当前非描边颜色进行绘制。默认值：false。取值：True 表示图像是图像遮罩。

**Returns:**
布尔值

### isTheSameObject {#isTheSameObject-com.aspose.pdf.XImage-}
如果两个图像引用同一对象，则返回 true。

### rename {#rename-java.lang.String-}
重命名图像并将所有对该图像的引用替换为新名称

### replace {#replace-java.io.InputStream-}
将图像替换到 {@code image} 指定的流中。 *

### save {#save-java.io.OutputStream-}
将图像数据以 JPEG 图像的形式保存到流中。

### save {#save-java.io.OutputStream-float-float-}
将图像保存到流中，使用请求的格式。

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
将图像保存到流中，使用请求的格式。

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
将图像保存到流中，使用请求的格式。

### save {#save-java.io.OutputStream-int-}
将图像保存到流中，使用请求的格式和指定的分辨率。

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-}
将图像保存到流中，使用请求的格式。

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-}


### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-int-}
将图像数据保存到流中，作为 JPEG 图像并使用指定的分辨率。

### setName {#setName-java.lang.String-}
设置图像名称。请注意，如果更改在页面内容中有引用的图像的名称，文档可能会变得不正确。在这种情况下请使用 XImage.Rename 方法。

### toStream {#toStream--}
```
public InputStream toStream()
```

返回原始图像流。

**Returns:**
原始图像流。

### toString {#toString--}
```
public String toString()
```

返回 XImage 对象属性的字符串表示形式。

**Returns:**
String 实例

### trySetAlternativeText {#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-}
为页面上的 XImage 设置替代文本。
