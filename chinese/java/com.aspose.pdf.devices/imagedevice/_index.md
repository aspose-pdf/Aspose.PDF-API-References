---
title: ImageDevice
second_title: 用于 Java API 参考的 Aspose.PDF
description: 图像设备的抽象类。
type: docs
weight: 19
url: /zh/java/com.aspose.pdf.devices/imagedevice/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice)
```
public abstract class ImageDevice extends PageDevice
```

图像设备的抽象类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ImageDevice()](#ImageDevice--) | ImageDevice 后代的抽象初始化程序，将分辨率设置为 150x150。 |
| [ImageDevice(Resolution resolution)](#ImageDevice-com.aspose.pdf.devices.Resolution-) | ImageDevice 后代的抽象初始值设定项。 |
| [ImageDevice(int width, int height)](#ImageDevice-int-int-) | 使用提供的图像尺寸和默认分辨率 (=150) 初始化 JpegDevice 类的新实例。 |
| [ImageDevice(PageSize pageSize)](#ImageDevice-com.aspose.pdf.PageSize-) | 使用提供的图像尺寸和默认分辨率 (=150) 初始化 JpegDevice 类的新实例。 |
| [ImageDevice(int width, int height, Resolution resolution)](#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-) | 使用提供的图像尺寸和分辨率初始化 JpegDevice 类的新实例。 |
| [ImageDevice(PageSize pageSize, Resolution resolution)](#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | 使用提供的图像尺寸和分辨率初始化 JpegDevice 类的新实例。 |
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
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [process(Page page, System.Drawing.Graphics gr)](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | 在图形上呈现页面 |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) | 在给定页面上执行一些操作，例如将页面转换为图形图像。 |
| [process(Page page, String outputFileName)](#process-com.aspose.pdf.Page-java.lang.String-) | 在给定页面上执行一些操作并将结果保存到文件中。 |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | 在给定页面上执行一些操作，例如将页面转换为图形图像。 |
| [setCoordinateType(int value)](#setCoordinateType-int-) | 设置页面坐标类型（媒体/裁剪框）。 |
| [setCropRectangle(Rectangle cropRectangle)](#setCropRectangle-com.aspose.pdf.Rectangle-) | 设置矩形，定义将转换为图片的区域。 |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) | 设置表单呈现模式。 |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | 设置渲染选项。 |
| [setShadingPerformanceHigh(boolean value)](#setShadingPerformanceHigh-boolean-) | 设置着色过程的性能是否高。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageDevice() {#ImageDevice--}
```
public ImageDevice()
```


ImageDevice 后代的抽象初始化程序，将分辨率设置为 150x150。

### ImageDevice(Resolution resolution) {#ImageDevice-com.aspose.pdf.devices.Resolution-}
```
public ImageDevice(Resolution resolution)
```


ImageDevice 后代的抽象初始值设定项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 结果图像文件的分辨率，请参阅分辨率类。 |

### ImageDevice(int width, int height) {#ImageDevice-int-int-}
```
public ImageDevice(int width, int height)
```


使用提供的图像尺寸和默认分辨率 (=150) 初始化 JpegDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 图像输出宽度。 |
| height | int | 图像输出高度。 |

### ImageDevice(PageSize pageSize) {#ImageDevice-com.aspose.pdf.PageSize-}
```
public ImageDevice(PageSize pageSize)
```


使用提供的图像尺寸和默认分辨率 (=150) 初始化 JpegDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出图像的页面大小。 |

### ImageDevice(int width, int height, Resolution resolution) {#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-}
```
public ImageDevice(int width, int height, Resolution resolution)
```


使用提供的图像尺寸和分辨率初始化 JpegDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 图像输出宽度。 |
| height | int | 图像输出高度。 |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 结果图像文件的分辨率，请参阅分辨率类。 |

### ImageDevice(PageSize pageSize, Resolution resolution) {#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
```
public ImageDevice(PageSize pageSize, Resolution resolution)
```


使用提供的图像尺寸和分辨率初始化 JpegDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出图像的页面大小。 |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 结果图像文件的分辨率，请参阅分辨率类。 |

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


在给定页面上执行一些操作，例如将页面转换为图形图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 要处理的页面。 |
| output | java.io.OutputStream | 该流包含处理的结果。 |

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
public abstract void processInternal(Page page, System.IO.Stream output)
```


在给定页面上执行一些操作，例如将页面转换为图形图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | 要处理的页面。 |
| output | com.aspose.ms.System.IO.Stream | 该流包含处理的结果。 |

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
