---
title: PngDevice
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示有助于将 pdf 文档页面保存为 png 的图像设备。
type: docs
weight: 23
url: /zh/java/com.aspose.pdf.devices/pngdevice/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice), [com.aspose.pdf.devices.ImageDevice](../../com.aspose.pdf.devices/imagedevice)
```
public final class PngDevice extends ImageDevice
```

表示有助于将 pdf 文档页面保存为 png 的图像设备。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PngDevice()](#PngDevice--) | 使用默认分辨率初始化 PngDevice 类的新实例。 |
| [PngDevice(Resolution resolution)](#PngDevice-com.aspose.pdf.devices.Resolution-) | 初始化 PngDevice 类的新实例。 |
| [PngDevice(int width, int height, Resolution resolution)](#PngDevice-int-int-com.aspose.pdf.devices.Resolution-) | 使用提供的图像尺寸和分辨率初始化 PngDevice 类的新实例。 |
| [PngDevice(PageSize pageSize, Resolution resolution)](#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | 使用提供的页面大小和分辨率初始化 PngDevice 类的新实例。 |
| [PngDevice(int width, int height)](#PngDevice-int-int-) | 使用提供的图像尺寸、默认分辨率 (=150) 初始化 PngDevice 类的新实例。 |
| [PngDevice(PageSize pageSize)](#PngDevice-com.aspose.pdf.PageSize-) | 使用提供的页面大小、默认分辨率 (=150) 初始化 PngDevice 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCoordinateType()](#getCoordinateType--) | 获取页面坐标类型（媒体/裁剪框）。 |
| [getCropRectangle()](#getCropRectangle--) | 获取定义将转换为图片的区域的矩形。 |
| [getFormPresentationMode()](#getFormPresentationMode--) | 获取表单呈现模式。 |
| [getHeight()](#getHeight--) | 获取图像输出高度。 |
| [getRenderingOptions()](#getRenderingOptions--) | 获取渲染选项。 |
| [getResolution()](#getResolution--) | 获取图像分辨率。 |
| [getWidth()](#getWidth--) | 获取图像输出宽度。 |
| [hashCode()](#hashCode--) |  |
| [isShadingPerformanceHigh()](#isShadingPerformanceHigh--) | 着色过程的性能是否高。 |
| [isTransparentBackground()](#isTransparentBackground--) | 获取或设置图像是否具有透明背景。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [process(Page page, System.Drawing.Graphics gr)](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | 在图形上呈现页面 |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) | 将页面转换为 png 并将其保存在输出流中。 |
| [process(Page page, String outputFileName)](#process-com.aspose.pdf.Page-java.lang.String-) | 在给定页面上执行一些操作并将结果保存到文件中。 |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | 将页面转换为 png 并将其保存在输出流中。 |
| [processToBufferedImage(Page page)](#processToBufferedImage-com.aspose.pdf.Page-) | 将页面转换为 BufferedImage。 |
| [processToBufferedImageBinarized(Page page, double threshold)](#processToBufferedImageBinarized-com.aspose.pdf.Page-double-) | 使用 Bradley 二值化将页面转换为 BufferedImage。 |
| [setCoordinateType(int value)](#setCoordinateType-int-) | 设置页面坐标类型（媒体/裁剪框）。 |
| [setCropRectangle(Rectangle cropRectangle)](#setCropRectangle-com.aspose.pdf.Rectangle-) | 设置矩形，定义将转换为图片的区域。 |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) | 设置表单呈现模式。 |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | 设置渲染选项。 |
| [setShadingPerformanceHigh(boolean value)](#setShadingPerformanceHigh-boolean-) | 设置着色过程的性能是否高。 |
| [setTransparentBackground(boolean value)](#setTransparentBackground-boolean-) | 获取或设置图像是否具有透明背景。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PngDevice() {#PngDevice--}
```
public PngDevice()
```


使用默认分辨率初始化 PngDevice 类的新实例。

### PngDevice(Resolution resolution) {#PngDevice-com.aspose.pdf.devices.Resolution-}
```
public PngDevice(Resolution resolution)
```


初始化 PngDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 结果图像文件的分辨率，请参阅分辨率类。 |

### PngDevice(int width, int height, Resolution resolution) {#PngDevice-int-int-com.aspose.pdf.devices.Resolution-}
```
public PngDevice(int width, int height, Resolution resolution)
```


使用提供的图像尺寸和分辨率初始化 PngDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 图像输出宽度。 |
| height | int | 图像输出高度。 |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 结果图像文件的分辨率，请参阅分辨率类。 |

### PngDevice(PageSize pageSize, Resolution resolution) {#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
```
public PngDevice(PageSize pageSize, Resolution resolution)
```


使用提供的页面大小和分辨率初始化 PngDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出图像的页面大小。 |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 结果图像文件的分辨率，请参阅分辨率类。 |

### PngDevice(int width, int height) {#PngDevice-int-int-}
```
public PngDevice(int width, int height)
```


使用提供的图像尺寸、默认分辨率 (=150) 初始化 PngDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 图像输出宽度。 |
| height | int | 图像输出高度。 |

### PngDevice(PageSize pageSize) {#PngDevice-com.aspose.pdf.PageSize-}
```
public PngDevice(PageSize pageSize)
```


使用提供的页面大小、默认分辨率 (=150) 初始化 PngDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出图像的页面大小。 |

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
### getCoordinateType() {#getCoordinateType--}
```
public int getCoordinateType()
```


获取页面坐标类型（媒体/裁剪框）。默认使用 CropBox 值。

**退货：**
int - PageCoordinateType 元素
### getCropRectangle() {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```


获取定义将转换为图片的区域的矩形。默认值为 null，在这种情况下，整个页面都将转换为图像。

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 矩形对象
### getFormPresentationMode() {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```


获取表单呈现模式。

**退货：**
int - FormPresentationMode 元素
### getHeight() {#getHeight--}
```
public int getHeight()
```


获取图像输出高度。

**退货：**
int - 整数值
### getRenderingOptions() {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```


获取渲染选项。

**退货：**
[RenderingOptions](../../com.aspose.pdf/renderingoptions) 渲染选项元素
### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


获取图像分辨率。

**退货：**
[Resolution](../../com.aspose.pdf.devices/resolution) 分辨率元素
### getWidth() {#getWidth--}
```
public int getWidth()
```


获取图像输出宽度。

**退货：**
int - 整数值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isShadingPerformanceHigh() {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```


着色过程的性能是否高。
默认为真。

**退货：**
boolean - 布尔值
### isTransparentBackground() {#isTransparentBackground--}
```
public final boolean isTransparentBackground()
```


获取或设置图像是否具有透明背景。

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




### process(Page page, System.Drawing.Graphics gr) {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
```
public void process(Page page, System.Drawing.Graphics gr)
```


在图形上呈现页面

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 页面对象 |
| gr | com.aspose.ms.System.Drawing.Graphics | 内部对象 |

### process(Page page, OutputStream output) {#process-com.aspose.pdf.Page-java.io.OutputStream-}
```
public void process(Page page, OutputStream output)
```


将页面转换为 png 并将其保存在输出流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 要转换的页面。 |
| output | java.io.OutputStream | 带有 png 图像的输出流。 |

### process(Page page, String outputFileName) {#process-com.aspose.pdf.Page-java.lang.String-}
```
public void process(Page page, String outputFileName)
```


在给定页面上执行一些操作并将结果保存到文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 要处理的页面。 |
| outputFileName | java.lang.String | 该文件包含处理结果。 |

### processInternal(Page page, System.IO.Stream output) {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(Page page, System.IO.Stream output)
```


将页面转换为 png 并将其保存在输出流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 要转换的页面。 |
| output | com.aspose.ms.System.IO.Stream | 带有 png 图像的输出流。 |

### processToBufferedImage(Page page) {#processToBufferedImage-com.aspose.pdf.Page-}
```
public BufferedImage processToBufferedImage(Page page)
```


将页面转换为 BufferedImage。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 要转换的页面。 |

**退货：**
java.awt.image.BufferedImage - BufferedImage 输出 BufferedImage 图像。
### processToBufferedImageBinarized(Page page, double threshold) {#processToBufferedImageBinarized-com.aspose.pdf.Page-double-}
```
public BufferedImage processToBufferedImageBinarized(Page page, double threshold)
```


使用 Bradley 二值化将页面转换为 BufferedImage。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 要转换的页面。 |
| threshold | double | 阈值介于 0.0 和 1.0 之间。 |

**退货：**
java.awt.image.BufferedImage - BufferedImage 输出 BufferedImage 图像。
### setCoordinateType(int value) {#setCoordinateType-int-}
```
public void setCoordinateType(int value)
```


设置页面坐标类型（媒体/裁剪框）。默认使用 CropBox 值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | PageCoordinateType 元素 |

### setCropRectangle(Rectangle cropRectangle) {#setCropRectangle-com.aspose.pdf.Rectangle-}
```
public void setCropRectangle(Rectangle cropRectangle)
```


设置矩形，定义将转换为图片的区域。默认值为 null，在这种情况下，整个页面都将转换为图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cropRectangle | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |

### setFormPresentationMode(int value) {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```


设置表单呈现模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | FormPresentationMode 元素 |

### setRenderingOptions(RenderingOptions value) {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
```
public void setRenderingOptions(RenderingOptions value)
```


设置渲染选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [RenderingOptions](../../com.aspose.pdf/renderingoptions) | RenderingOptions 元素 |

### setShadingPerformanceHigh(boolean value) {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```


设置着色过程的性能是否高。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setTransparentBackground(boolean value) {#setTransparentBackground-boolean-}
```
public final void setTransparentBackground(boolean value)
```


获取或设置图像是否具有透明背景。

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
