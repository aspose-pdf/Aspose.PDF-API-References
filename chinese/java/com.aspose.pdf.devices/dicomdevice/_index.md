---
title: "DicomDevice"
linktitle: "DicomDevice"
second_title: "Aspose.PDF for Java API 参考"
description: "表示帮助将 PDF 文档页面保存为 Dicom 格式的图像设备。"
type: docs
weight: 50
url: /zh/java/com.aspose.pdf.devices/dicomdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.DicomDevice

```
public final class DicomDevice extends ImageDevice
```

表示帮助将 PDF 文档页面保存为 Dicom 格式的图像设备。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DicomDevice](#DicomDevice--) | 使用默认分辨率初始化 {@link DicomDevice} 类的新实例。 |
| [DicomDevice](#DicomDevice-int-int-) | 使用提供的图像尺寸和默认分辨率（=150）初始化 {@link DicomDevice} 类的新实例。 |
| [DicomDevice](#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-) | 使用默认分辨率初始化 {@link DicomDevice} 类的新实例。 |
| [DicomDevice](#DicomDevice-com.aspose.pdf.PageSize-) | 使用默认分辨率初始化 {@link DicomDevice} 类的新实例。 |
| [DicomDevice](#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | 使用默认分辨率初始化 {@link DicomDevice} 类的新实例。 |
| [DicomDevice](#DicomDevice-com.aspose.pdf.devices.Resolution-) | 使用默认分辨率初始化 {@link DicomDevice} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | 将页面转换为 Dicom 并保存到输出流中。 |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | 对给定页面执行某些操作，例如。 |

### DicomDevice {#DicomDevice--}
```
public DicomDevice()
```

使用默认分辨率初始化 {@link DicomDevice} 类的新实例。

### DicomDevice {#DicomDevice-int-int-}
```
public DicomDevice(int width, int height)
```

使用提供的图像尺寸和默认分辨率（=150）初始化 {@link DicomDevice} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 图像输出宽度。 |
| 高度 |  | 图像输出高度。 |

### DicomDevice {#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-}
使用默认分辨率初始化 {@link DicomDevice} 类的新实例。

### DicomDevice {#DicomDevice-com.aspose.pdf.PageSize-}
使用默认分辨率初始化 {@link DicomDevice} 类的新实例。

### DicomDevice {#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
使用默认分辨率初始化 {@link DicomDevice} 类的新实例。

### DicomDevice {#DicomDevice-com.aspose.pdf.devices.Resolution-}
使用默认分辨率初始化 {@link DicomDevice} 类的新实例。

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
将页面转换为 Dicom 并保存到输出流中。

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
对给定页面执行某些操作，例如。
