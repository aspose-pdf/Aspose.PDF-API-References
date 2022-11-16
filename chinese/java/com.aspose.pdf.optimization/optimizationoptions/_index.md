---
title: OptimizationOptions
second_title: 用于 Java API 参考的 Aspose.PDF
description: 描述文档优化算法的类。
type: docs
weight: 13
url: /zh/java/com.aspose.pdf.optimization/optimizationoptions/
---
**遗产：**
java.lang.Object
```
public class OptimizationOptions
```

描述文档优化算法的类。此类的实例可用作 OptimizeResources() 方法的参数。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OptimizationOptions()](#OptimizationOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [all()](#all--) | 创建优化策略将激活所有选项。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowReusePageContent()](#getAllowReusePageContent--) | 当文档针对相等页面进行优化时，如果为真页面内容将被重用。 |
| [getClass()](#getClass--) |  |
| [getCompressImages()](#getCompressImages--) | 如果此标志设置为 true，图像将在文档中被压缩。压缩级别由 ImageQuality 属性指定。 |
| [getImageCompressionOptions()](#getImageCompressionOptions--) | 描述将压缩文档中的图像和压缩参数的选项集。 |
| [getImageEncoding()](#getImageEncoding--) | 将使用的图像编码器。 |
| [getImageQuality()](#getImageQuality--) | 使用 CompressIamges 标志时指定图像压缩级别。 |
| [getLinkDuplcateStreams()](#getLinkDuplcateStreams--) | 如果此标志设置为 true，将分析资源流。 |
| [getMaxResoultion()](#getMaxResoultion--) | 指定图像的最大分辨率。 |
| [getRemovePrivateInfo()](#getRemovePrivateInfo--) | 删除隐私信息（页面信息）。 |
| [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | 如果此标志设置为 true，将检查所有文档对象，并将未使用的对象（即没有任何引用的对象）从文档中删除。 |
| [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | 如果此标志设置为 true，则会检查每个资源的使用情况。 |
| [getResizeImages()](#getResizeImages--) | 如果此标志设置为 true 且 CompressImages 为 true，则在图像分辨率大于指定的 MaxResolution 参数时图像将被调整大小。 |
| [getSubsetFonts()](#getSubsetFonts--) | 如果设置为 true，字体将被转换为子集。 |
| [getUnembedFonts()](#getUnembedFonts--) | 如果设置为 true，则不嵌入字体。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowReusePageContent(boolean value)](#setAllowReusePageContent-boolean-) | 当文档针对相等页面进行优化时，如果为真页面内容将被重用。 |
| [setCompressImages(boolean value)](#setCompressImages-boolean-) | 如果此标志设置为 true，图像将在文档中被压缩。压缩级别由 ImageQuality 属性指定。 |
| [setImageEncoding(int value)](#setImageEncoding-int-) | 将使用的图像编码器。 |
| [setImageQuality(int value)](#setImageQuality-int-) | 使用 CompressIamges 标志时指定图像压缩级别。 |
| [setLinkDuplcateStreams(boolean value)](#setLinkDuplcateStreams-boolean-) | 如果此标志设置为 true，将分析资源流。 |
| [setMaxResoultion(int value)](#setMaxResoultion-int-) | 指定图像的最大分辨率。 |
| [setRemovePrivateInfo(boolean value)](#setRemovePrivateInfo-boolean-) | 删除隐私信息（页面信息）。 |
| [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | 如果此标志设置为 true，将检查所有文档对象，并将未使用的对象（即没有任何引用的对象）从文档中删除。 |
| [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | 如果此标志设置为 true，则会检查每个资源的使用情况。 |
| [setResizeImages(boolean value)](#setResizeImages-boolean-) | 如果此标志设置为 true 且 CompressImages 为 true，则在图像分辨率大于指定的 MaxResolution 参数时图像将被调整大小。 |
| [setSubsetFonts(boolean value)](#setSubsetFonts-boolean-) | 如果设置为 true，字体将被转换为子集。 |
| [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | 如果设置为 true，则不嵌入字体。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OptimizationOptions() {#OptimizationOptions--}
```
public OptimizationOptions()
```


### all() {#all--}
```
public static OptimizationOptions all()
```


创建优化策略将激活所有选项。请注意，仅激活不会更改文档任何功能的选项。即图像压缩和字体取消嵌入将不会启用（并且可以手动嵌入）。

**退货：**
[OptimizationOptions](../../com.aspose.pdf.optimization/optimizationoptions) - 优化选项对象。
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
### getAllowReusePageContent() {#getAllowReusePageContent--}
```
public final boolean getAllowReusePageContent()
```


当文档针对相等页面进行优化时，如果为真页面内容将被重用。

**退货：**
boolean - 布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


如果此标志设置为 true，图像将在文档中被压缩。压缩级别由 ImageQuality 属性指定。

**退货：**
boolean - 布尔值
### getImageCompressionOptions() {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```


描述将压缩文档中的图像和压缩参数的选项集。

**退货：**
[ImageCompressionOptions](../../com.aspose.pdf.optimization/imagecompressionoptions) - ImageCompressionOptions 实例
### getImageEncoding() {#getImageEncoding--}
```
public final int getImageEncoding()
```


将使用的图像编码器。

**退货：**
int - ImageEncoding 元素
### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


使用 CompressIamges 标志时指定图像压缩级别。

**退货：**
int - 整数值
### getLinkDuplcateStreams() {#getLinkDuplcateStreams--}
```
public final boolean getLinkDuplcateStreams()
```


如果此标志设置为 true，将分析资源流。如果发现重复的流（即如果流内容相同），那么这些流将被存储为一个对象。这允许在某些情况下减小文档大小（例如，当同一文档被多次连接时）。

**退货：**
boolean - 布尔值
### getMaxResoultion() {#getMaxResoultion--}
```
public final int getMaxResoultion()
```


指定图像的最大分辨率。如果图像具有更高的分辨率，它将被缩放

**退货：**
int - 整数值
### getRemovePrivateInfo() {#getRemovePrivateInfo--}
```
public final boolean getRemovePrivateInfo()
```


删除隐私信息（页面信息）。

**退货：**
boolean - 布尔值
### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


如果此标志设置为 true，将检查所有文档对象，并将未使用的对象（即没有任何引用的对象）从文档中删除。

**退货：**
boolean - 布尔值
### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


如果此标志设置为 true，则会检查每个资源的使用情况。如果从未使用过资源，则删除资源。例如，当从文档中提取页面时，这可能会减小文档大小。

**退货：**
boolean - 布尔值
### getResizeImages() {#getResizeImages--}
```
public final boolean getResizeImages()
```


如果此标志设置为 true 且 CompressImages 为 true，则在图像分辨率大于指定的 MaxResolution 参数时图像将被调整大小。

**退货：**
boolean - 布尔值
### getSubsetFonts() {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```


如果设置为 true，字体将被转换为子集。

**退货：**
boolean - 布尔值
### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


如果设置为 true，则不嵌入字体。

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




### setAllowReusePageContent(boolean value) {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```


当文档针对相等页面进行优化时，如果为真页面内容将被重用。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


如果此标志设置为 true，图像将在文档中被压缩。压缩级别由 ImageQuality 属性指定。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setImageEncoding(int value) {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```


将使用的图像编码器。

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

### setLinkDuplcateStreams(boolean value) {#setLinkDuplcateStreams-boolean-}
```
public final void setLinkDuplcateStreams(boolean value)
```


如果此标志设置为 true，将分析资源流。如果发现重复的流（即如果流内容相同），那么这些流将被存储为一个对象。这允许在某些情况下减小文档大小（例如，当同一文档被多次连接时）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setMaxResoultion(int value) {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```


指定图像的最大分辨率。如果图像具有更高的分辨率，它将被缩放

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setRemovePrivateInfo(boolean value) {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```


删除隐私信息（页面信息）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


如果此标志设置为 true，将检查所有文档对象，并将未使用的对象（即没有任何引用的对象）从文档中删除。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


如果此标志设置为 true，则会检查每个资源的使用情况。如果从未使用过资源，则删除资源。例如，当从文档中提取页面时，这可能会减小文档大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setResizeImages(boolean value) {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```


如果此标志设置为 true 且 CompressImages 为 true，则在图像分辨率大于指定的 MaxResolution 参数时图像将被调整大小。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSubsetFonts(boolean value) {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```


如果设置为 true，字体将被转换为子集。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


如果设置为 true，则不嵌入字体。

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
