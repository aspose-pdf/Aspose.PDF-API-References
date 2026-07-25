---
title: "JpegDevice"
linktitle: "JpegDevice"
second_title: "Aspose.PDF for Java API 参考"
description: "表示帮助将 PDF 文档页面保存为 jpeg 的图像设备。"
type: docs
weight: 130
url: /zh/java/com.aspose.pdf.devices/jpegdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.JpegDevice

```
public final class JpegDevice extends ImageDevice
```

表示帮助将 PDF 文档页面保存为 jpeg 的图像设备。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [JpegDevice](#JpegDevice--) | 使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。 |
| [JpegDevice](#JpegDevice-int-) | 初始化 {@code JpegDevice} 类的新实例。 |
| [JpegDevice](#JpegDevice-int-int-) | 使用提供的图像尺寸、默认分辨率（=150）和最高质量初始化 {@code JpegDevice} 类的新实例。 |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-) | 使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。 |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-) | 使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。 |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-) | 使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。 |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | 使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。 |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-) | 使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。 |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-) | 使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。 |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-int-) | 使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | 将页面转换为 jpeg 并保存到输出流中。 |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | 将页面转换为 jpeg 并保存到输出流中。 |

### JpegDevice {#JpegDevice--}
```
public JpegDevice()
```

使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。

### JpegDevice {#JpegDevice-int-}
```
public JpegDevice(int quality)
```

初始化 {@code JpegDevice} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 质量 |  | 指定图像的压缩级别。质量的有效取值范围为 0 到 100。指定的数值越低，压缩率越高，图像质量因此越低。0 将产生最低质量的图像，100 则为最高质量。 |

### JpegDevice {#JpegDevice-int-int-}
```
public JpegDevice(int width, int height)
```

使用提供的图像尺寸、默认分辨率（=150）和最高质量初始化 {@code JpegDevice} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 图像输出宽度。 |
| 高度 |  | 图像输出高度。 |

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-}
使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-}
使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-}
使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-}
使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-}
使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-int-}
使用默认分辨率和最高质量初始化 {@code JpegDevice} 类的新实例。

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
将页面转换为 jpeg 并保存到输出流中。

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
将页面转换为 jpeg 并保存到输出流中。
