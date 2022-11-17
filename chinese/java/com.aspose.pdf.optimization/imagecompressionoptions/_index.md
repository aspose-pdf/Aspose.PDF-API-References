---
title: ImageCompressionOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 类包含图像压缩的设置选项。
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.optimization/imagecompressionoptions/
---
**遗产：**
java.lang.Object
```
public class ImageCompressionOptions
```

类包含图像压缩的设置选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageCompressionOptions()](#ImageCompressionOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | 获取或设置用于存储图像的编码。 |
| [getImageQuality()](#getImageQuality--) | 使用 CompressIamges 标志时指定图像压缩级别。 |
| [getMaxResolution()](#getMaxResolution--) | 指定图像的最大分辨率。 |
| [getResizeImages()](#getResizeImages--) | 如果此标志设置为 true 且 CompressImages 为 true，则在图像分辨率大于指定的 MaxResolution 参数时图像将被调整大小。 |
| [getVersion()](#getVersion--) | 压缩算法的版本。 |
| [hashCode()](#hashCode--) |  |
| [isCompressImages()](#isCompressImages--) | 如果此标志设置为 true，图像将在文档中被压缩。压缩级别由 ImageQuality 属性指定。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompressImages(boolean value)](#setCompressImages-boolean-) | 如果此标志设置为 true，图像将在文档中被压缩。压缩级别由 ImageQuality 属性指定。 |
| [setEncoding(int value)](#setEncoding-int-) | 获取或设置用于存储图像的编码。 |
| [setImageQuality(int value)](#setImageQuality-int-) | 使用 CompressIamges 标志时指定图像压缩级别。 |
| [setMaxResolution(int value)](#setMaxResolution-int-) | 指定图像的最大分辨率。 |
| [setResizeImages(boolean value)](#setResizeImages-boolean-) | 如果此标志设置为 true 且 CompressImages 为 true，则在图像分辨率大于指定的 MaxResolution 参数时图像将被调整大小。 |
| [setVersion(int value)](#setVersion-int-) | 压缩算法的版本。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageCompressionOptions() {#ImageCompressionOptions--}
```
public ImageCompressionOptions()
```


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
### getEncoding() {#getEncoding--}
```
public final int getEncoding()
```


获取或设置用于存储图像的编码。

**退货：**
int - ImageEncoding 元素
### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


使用 CompressIamges 标志时指定图像压缩级别。

**退货：**
int - 整数值
### getMaxResolution() {#getMaxResolution--}
```
public final int getMaxResolution()
```


指定图像的最大分辨率。如果图像具有更高的分辨率，它将被缩放

**退货：**
int - 整数值
### getResizeImages() {#getResizeImages--}
```
public final boolean getResizeImages()
```


如果此标志设置为 true 且 CompressImages 为 true，则在图像分辨率大于指定的 MaxResolution 参数时图像将被调整大小。

**退货：**
boolean - 布尔值
### getVersion() {#getVersion--}
```
public final int getVersion()
```


压缩算法的版本。可能的值是：1. 标准压缩，2. 快速（改进的压缩比标准更快，但可能不适用于所有图像），3. 混合（标准压缩应用于不能通过更快算法压缩的图像，这可能会提供最好的压缩，但比“快速”算法更慢。“快速”版本不适用于调整图像大小（将使用标准方法）。默认为“标准”。

**退货：**
int - 整数值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isCompressImages() {#isCompressImages--}
```
public final boolean isCompressImages()
```


如果此标志设置为 true，图像将在文档中被压缩。压缩级别由 ImageQuality 属性指定。

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




### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


如果此标志设置为 true，图像将在文档中被压缩。压缩级别由 ImageQuality 属性指定。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setEncoding(int value) {#setEncoding-int-}
```
public final void setEncoding(int value)
```


获取或设置用于存储图像的编码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 图像编码元素 |

### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


使用 CompressIamges 标志时指定图像压缩级别。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setMaxResolution(int value) {#setMaxResolution-int-}
```
public final void setMaxResolution(int value)
```


指定图像的最大分辨率。如果图像具有更高的分辨率，它将被缩放

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setResizeImages(boolean value) {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```


如果此标志设置为 true 且 CompressImages 为 true，则在图像分辨率大于指定的 MaxResolution 参数时图像将被调整大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


压缩算法的版本。可能的值是：1. 标准压缩，2. 快速（改进的压缩比标准更快，但可能不适用于所有图像），3. 混合（标准压缩应用于不能通过更快算法压缩的图像，这可能会提供最好的压缩，但比“快速”算法更慢。“快速”版本不适用于调整图像大小（将使用标准方法）。默认为“标准”。

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
