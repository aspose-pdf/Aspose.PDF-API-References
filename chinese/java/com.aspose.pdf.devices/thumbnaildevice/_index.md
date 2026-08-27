---
title: "ThumbnailDevice"
linktitle: "ThumbnailDevice"
second_title: "Aspose.PDF for Java API 参考"
description: "表示将 pdf 文档页面保存为缩略图的图像设备。"
type: docs
weight: 200
url: /zh/java/com.aspose.pdf.devices/thumbnaildevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.ThumbnailDevice

```
public final class ThumbnailDevice extends ImageDevice
```

表示将 pdf 文档页面保存为缩略图的图像设备。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ThumbnailDevice](#ThumbnailDevice--) | 使用默认的缩略图尺寸（200x200 像素）初始化 {@link ThumbnailDevice} 类的新实例。 |
| [ThumbnailDevice](#ThumbnailDevice-int-int-) | 初始化 {@link ThumbnailDevice} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [processInternal](#processInternal-com.aspose.pdf.Page-java.io.OutputStream-) | 将页面转换为缩略图 PNG 并将其保存到输出流中。 |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | 对给定页面执行某些操作，例如。 |

### ThumbnailDevice {#ThumbnailDevice--}
```
public ThumbnailDevice()
```

使用默认的缩略图尺寸（200x200 像素）初始化 {@link ThumbnailDevice} 类的新实例。

### ThumbnailDevice {#ThumbnailDevice-int-int-}
```
public ThumbnailDevice(int width, int height)
```

初始化 {@link ThumbnailDevice} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 缩略图输出宽度。 |
| 高度 |  | 缩略图输出高度。 |

### processInternal {#processInternal-com.aspose.pdf.Page-java.io.OutputStream-}
将页面转换为缩略图 PNG 并将其保存到输出流中。

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
对给定页面执行某些操作，例如。
