---
title: "BmpDevice"
linktitle: "BmpDevice"
second_title: "Aspose.PDF for Java API 参考"
description: "表示帮助将 PDF 文档页面保存为 bmp 的图像设备。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.devices/bmpdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.BmpDevice

```
public final class BmpDevice extends ImageDevice
```

表示帮助将 PDF 文档页面保存为 bmp 的图像设备。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [BmpDevice](#BmpDevice--) | 使用默认分辨率初始化 {@code BmpDevice} 类的新实例。 |
| [BmpDevice](#BmpDevice-int-int-) | 使用提供的图像尺寸和默认分辨率（=150）初始化 {@code BmpDevice} 类的新实例。 |
| [BmpDevice](#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-) | 使用默认分辨率初始化 {@code BmpDevice} 类的新实例。 |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-) | 使用默认分辨率初始化 {@code BmpDevice} 类的新实例。 |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | 使用默认分辨率初始化 {@code BmpDevice} 类的新实例。 |
| [BmpDevice](#BmpDevice-com.aspose.pdf.devices.Resolution-) | 使用默认分辨率初始化 {@code BmpDevice} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | 在图形上渲染页面。 |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | 将页面转换为 bmp 并保存到输出流中。 |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | 仅供内部使用！ |

### BmpDevice {#BmpDevice--}
```
public BmpDevice()
```

使用默认分辨率初始化 {@code BmpDevice} 类的新实例。

### BmpDevice {#BmpDevice-int-int-}
```
public BmpDevice(int width, int height)
```

使用提供的图像尺寸和默认分辨率（=150）初始化 {@code BmpDevice} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 图像输出宽度。 |
| 高度 |  | 图像输出高度。 |

### BmpDevice {#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-}
使用默认分辨率初始化 {@code BmpDevice} 类的新实例。

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-}
使用默认分辨率初始化 {@code BmpDevice} 类的新实例。

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
使用默认分辨率初始化 {@code BmpDevice} 类的新实例。

### BmpDevice {#BmpDevice-com.aspose.pdf.devices.Resolution-}
使用默认分辨率初始化 {@code BmpDevice} 类的新实例。

### process {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
在图形上渲染页面。

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
将页面转换为 bmp 并保存到输出流中。

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
仅供内部使用！
