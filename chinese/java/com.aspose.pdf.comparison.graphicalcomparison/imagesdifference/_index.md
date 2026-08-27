---
title: "ImagesDifference"
linktitle: "ImagesDifference"
second_title: "Aspose.PDF for Java API 参考"
description: "表示比较两个 PDF 页面结果的类。"
type: docs
weight: 20
url: /zh/java/com.aspose.pdf.comparison.graphicalcomparison/imagesdifference/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.ImagesDifference

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class ImagesDifference extends Object implements com.aspose.ms.System.IDisposable
```

表示比较两个 PDF 页面结果的类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [differenceToImage](#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-) | 使用指定的颜色将差异数组转换为位图图像。 |
| [dispose](#dispose--) | 在对象被销毁之前执行任何必要的清理操作。 |
| [getDestinationImage](#getDestinationImage--) | 通过将差异数组应用于源图像，返回表示目标图像的新位图。 |
| [getDifference](#getDifference--) | 获取差异数组。该数组类似于通过 LockBits 方法获得的原始图像数据数组。 |
| [getHeight](#getHeight--) | 差异的高度。 |
| [getSourceImage](#getSourceImage--) | 获取第一页比较的图像。该图像的像素格式为 24bpp。 |
| [getStride](#getStride--) | 差异图像数据的跨度。 |

### differenceToImage {#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-}
使用指定的颜色将差异数组转换为位图图像。

### dispose {#dispose--}
```
public final void dispose()
```

在对象被销毁之前执行任何必要的清理操作。

### getDestinationImage {#getDestinationImage--}
```
public final BufferedImage getDestinationImage()
```

通过将差异数组应用于源图像，返回表示目标图像的新位图。

**Returns:**
目标图像。

### getDifference {#getDifference--}
```
public final int[] getDifference()
```

获取差异数组。该数组类似于通过 LockBits 方法获得的原始图像数据数组。

**Returns:**
int[] array

### getHeight {#getHeight--}
```
public final int getHeight()
```

差异的高度。

**Returns:**
int 值

### getSourceImage {#getSourceImage--}
```
public final BufferedImage getSourceImage()
```

获取第一页比较的图像。该图像的像素格式为 24bpp。

**Returns:**
BufferedImage 实例

### getStride {#getStride--}
```
public final int getStride()
```

差异图像数据的跨度。

**Returns:**
int 值
