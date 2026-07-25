---
title: "TiffDevice"
linktitle: "TiffDevice"
second_title: "Aspose.PDF for Java API 参考"
description: "此类帮助将 pdf 文档逐页保存为单个 tiff 图像。"
type: docs
weight: 210
url: /zh/java/com.aspose.pdf.devices/tiffdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.TiffDevice

```
public final class TiffDevice extends DocumentDevice
```

此类帮助将 pdf 文档逐页保存为单个 tiff 图像。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffDevice](#TiffDevice--) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-int-int-) | 初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 使用默认设置初始化 {@code TiffDevice} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [binarizeBradley](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | 对输入流执行 Bradley 二值化。 |
| [getCropRectangle](#getCropRectangle--) | 获取定义将被转换为图片的区域的矩形。默认值为 null，在这种情况下，整个图像将被转换为页面。 |
| [getFormPresentationMode](#getFormPresentationMode--) | 获取表单呈现模式。 |
| [getHeight](#getHeight--) | 获取图像输出高度。 |
| [getRenderingOptions](#getRenderingOptions--) | 获取渲染选项。 |
| [getResolution](#getResolution--) | 获取图像分辨率。 |
| [getSettings](#getSettings--) | 获取将 PDF 映射为 TIFF 图像的设置。 |
| [getWidth](#getWidth--) | 获取图像输出宽度。 |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | 将特定文档页面转换为 TIFF 并保存到输出流中。 |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | 将特定文档页面转换为 TIFF 并保存到输出流中。 |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | 对给定页面执行某些操作，例如。 |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | 设置定义将被转换为图片的区域的矩形。 |
| [setFormPresentationMode](#setFormPresentationMode-int-) | 获取表单呈现模式。 |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | 设置渲染选项。 |

### TiffDevice {#TiffDevice--}
```
public TiffDevice()
```

使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-int-int-}
```
public TiffDevice(int width, int height)
```

初始化 {@code TiffDevice} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 图像输出宽度。 |
| 高度 |  | 图像输出高度。 |

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
使用默认设置初始化 {@code TiffDevice} 类的新实例。

### binarizeBradley {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
对输入流执行 Bradley 二值化。

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

获取定义将被转换为图片的区域的矩形。默认值为 null，在这种情况下，整个图像将被转换为页面。

**Returns:**
Rectangle 对象

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

获取表单呈现模式。

**Returns:**
FormPresentationMode 值 @see FormPresentationMode

### getHeight {#getHeight--}
```
public int getHeight()
```

获取图像输出高度。

**Returns:**
int 值

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

获取渲染选项。

**Returns:**
渲染选项。

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

获取图像分辨率。

**Returns:**
Resolution 元素

### getSettings {#getSettings--}
```
public TiffSettings getSettings()
```

获取将 PDF 映射为 TIFF 图像的设置。

**Returns:**
TiffSettings 元素

### getWidth {#getWidth--}
```
public int getWidth()
```

获取图像输出宽度。

**Returns:**
int 值

### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
将特定文档页面转换为 TIFF 并保存到输出流中。

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
将特定文档页面转换为 TIFF 并保存到输出流中。

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
对给定页面执行某些操作，例如。

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
设置定义将被转换为图片的区域的矩形。

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

获取表单呈现模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
设置渲染选项。
