---
title: "PngDevice"
linktitle: "PngDevice"
second_title: "Aspose.PDF for Java API 参考"
description: "表示帮助将 PDF 文档页面保存为 png 的图像设备。"
type: docs
weight: 160
url: /zh/java/com.aspose.pdf.devices/pngdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PngDevice

```
public final class PngDevice extends ImageDevice
```

表示帮助将 PDF 文档页面保存为 png 的图像设备。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PngDevice](#PngDevice--) | 使用默认分辨率初始化 {@code PngDevice} 类的新实例。 |
| [PngDevice](#PngDevice-int-int-) | 使用提供的图像尺寸和默认分辨率（=150）初始化 {@code PngDevice} 类的新实例。 |
| [PngDevice](#PngDevice-int-int-com.aspose.pdf.devices.Resolution-) | 使用默认分辨率初始化 {@code PngDevice} 类的新实例。 |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-) | 使用默认分辨率初始化 {@code PngDevice} 类的新实例。 |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | 使用默认分辨率初始化 {@code PngDevice} 类的新实例。 |
| [PngDevice](#PngDevice-com.aspose.pdf.devices.Resolution-) | 使用默认分辨率初始化 {@code PngDevice} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [isTransparentBackground](#isTransparentBackground--) | 获取或设置图像是否具有透明背景。 |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | 将页面转换为 PNG 并将其保存到输出流中。 |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | 将页面转换为 PNG 并将其保存到输出流中。 |
| [processToBufferedImage](#processToBufferedImage-com.aspose.pdf.Page-) | 将页面转换为 BufferedImage。 |
| [processToBufferedImageBinarized](#processToBufferedImageBinarized-com.aspose.pdf.Page-double-) | 将页面转换为带有 Bradley 二值化的 BufferedImage。 |
| [setTransparentBackground](#setTransparentBackground-boolean-) | 获取或设置图像是否具有透明背景。 |

### PngDevice {#PngDevice--}
```
public PngDevice()
```

使用默认分辨率初始化 {@code PngDevice} 类的新实例。

### PngDevice {#PngDevice-int-int-}
```
public PngDevice(int width, int height)
```

使用提供的图像尺寸和默认分辨率（=150）初始化 {@code PngDevice} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 图像输出宽度。 |
| 高度 |  | 图像输出高度。 |

### PngDevice {#PngDevice-int-int-com.aspose.pdf.devices.Resolution-}
使用默认分辨率初始化 {@code PngDevice} 类的新实例。

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-}
使用默认分辨率初始化 {@code PngDevice} 类的新实例。

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
使用默认分辨率初始化 {@code PngDevice} 类的新实例。

### PngDevice {#PngDevice-com.aspose.pdf.devices.Resolution-}
使用默认分辨率初始化 {@code PngDevice} 类的新实例。

### isTransparentBackground {#isTransparentBackground--}
```
public final boolean isTransparentBackground()
```

获取或设置图像是否具有透明背景。

**Returns:**
布尔值

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
将页面转换为 PNG 并将其保存到输出流中。

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
将页面转换为 PNG 并将其保存到输出流中。

### processToBufferedImage {#processToBufferedImage-com.aspose.pdf.Page-}
将页面转换为 BufferedImage。

### processToBufferedImageBinarized {#processToBufferedImageBinarized-com.aspose.pdf.Page-double-}
将页面转换为带有 Bradley 二值化的 BufferedImage。

### setTransparentBackground {#setTransparentBackground-boolean-}
```
public final void setTransparentBackground(boolean value)
```

获取或设置图像是否具有透明背景。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
