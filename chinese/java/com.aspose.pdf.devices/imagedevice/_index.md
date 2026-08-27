---
title: "图像设备"
linktitle: "图像设备"
second_title: "Aspose.PDF for Java API 参考"
description: "图像设备的抽象类。"
type: docs
weight: 110
url: /zh/java/com.aspose.pdf.devices/imagedevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice

```
public abstract class ImageDevice extends PageDevice
```

图像设备的抽象类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageDevice](#ImageDevice--) | 抽象初始化器用于 {@code ImageDevice} 的子类，设置分辨率为 150x150。 |
| [ImageDevice](#ImageDevice-int-int-) | 使用提供的图像尺寸和默认分辨率（=150）初始化 {@code JpegDevice} 类的新实例。 |
| [ImageDevice](#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-) | 抽象初始化器用于 {@code ImageDevice} 的子类，设置分辨率为 150x150。 |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-) | 抽象初始化器用于 {@code ImageDevice} 的子类，设置分辨率为 150x150。 |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | 抽象初始化器用于 {@code ImageDevice} 的子类，设置分辨率为 150x150。 |
| [ImageDevice](#ImageDevice-com.aspose.pdf.devices.Resolution-) | 抽象初始化器用于 {@code ImageDevice} 的子类，设置分辨率为 150x150。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBitmap](#getBitmap-com.aspose.pdf.Page-) | 将页面转换为 {@link java.awt.image.BufferedImage}。 |
| [getCoordinateType](#getCoordinateType--) | 获取页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。 |
| [getCropRectangle](#getCropRectangle--) | 获取定义将被转换为图片的区域的矩形。默认值为 null，此时整个页面将被转换为图像。 |
| [getFormPresentationMode](#getFormPresentationMode--) | 获取表单呈现模式。 |
| [getHeight](#getHeight--) | 获取图像输出高度。 |
| [getRenderingOptions](#getRenderingOptions--) | 获取渲染选项。 |
| [getResolution](#getResolution--) | 获取图像分辨率。 |
| [getWidth](#getWidth--) | 获取图像输出宽度。 |
| [isShadingPerformanceHigh](#isShadingPerformanceHigh--) | 着色过程的性能是否为高。默认情况下为 true。 |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | 设置页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。 |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | 设置定义将被转换为图片的区域的矩形。 |
| [setFormPresentationMode](#setFormPresentationMode-int-) | 设置表单呈现模式。 |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | 设置渲染选项。 |
| [setShadingPerformanceHigh](#setShadingPerformanceHigh-boolean-) | 设置着色过程的性能是否为高。 |

### ImageDevice {#ImageDevice--}
```
public ImageDevice()
```

抽象初始化器用于 {@code ImageDevice} 的子类，设置分辨率为 150x150。

### ImageDevice {#ImageDevice-int-int-}
```
public ImageDevice(int width, int height)
```

使用提供的图像尺寸和默认分辨率（=150）初始化 {@code JpegDevice} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 |  | 图像输出宽度。 |
| 高度 |  | 图像输出高度。 |

### ImageDevice {#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-}
抽象初始化器用于 {@code ImageDevice} 的子类，设置分辨率为 150x150。

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-}
抽象初始化器用于 {@code ImageDevice} 的子类，设置分辨率为 150x150。

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
抽象初始化器用于 {@code ImageDevice} 的子类，设置分辨率为 150x150。

### ImageDevice {#ImageDevice-com.aspose.pdf.devices.Resolution-}
抽象初始化器用于 {@code ImageDevice} 的子类，设置分辨率为 150x150。

### getBitmap {#getBitmap-com.aspose.pdf.Page-}
将页面转换为 {@link java.awt.image.BufferedImage}。

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

获取页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。

**Returns:**
PageCoordinateType 元素 @see PageCoordinateType

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

获取定义将被转换为图片的区域的矩形。默认值为 null，此时整个页面将被转换为图像。

**Returns:**
Rectangle 对象

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

获取表单呈现模式。

**Returns:**
FormPresentationMode 元素 @see FormPresentationMode

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
RenderingOptions 元素

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

获取图像分辨率。

**Returns:**
Resolution 元素

### getWidth {#getWidth--}
```
public int getWidth()
```

获取图像输出宽度。

**Returns:**
int 值

### isShadingPerformanceHigh {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```

着色过程的性能是否为高。默认情况下为 true。

**Returns:**
布尔值

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
设置页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
设置定义将被转换为图片的区域的矩形。

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

设置表单呈现模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | FormPresentationMode 元素 @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
设置渲染选项。

### setShadingPerformanceHigh {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```

设置着色过程的性能是否为高。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |
