---
title: TiffDevice
second_title: 用于 Java API 参考的 Aspose.PDF
description: 此类有助于将 pdf 文档逐页保存到一个 tiff 图像中。
type: docs
weight: 28
url: /zh/java/com.aspose.pdf.devices/tiffdevice/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.DocumentDevice](../../com.aspose.pdf.devices/documentdevice)
```
public final class TiffDevice extends DocumentDevice
```

此类有助于将 pdf 文档逐页保存到一个 tiff 图像中。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffDevice(Resolution resolution)](#TiffDevice-com.aspose.pdf.devices.Resolution-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice(Resolution resolution, TiffSettings settings)](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice(Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice(TiffSettings settings)](#TiffDevice-com.aspose.pdf.devices.TiffSettings-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice(TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice()](#TiffDevice--) | 使用默认设置初始化 TiffDevice 类的新实例。 |
| [TiffDevice(int width, int height, Resolution resolution, TiffSettings settings)](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice(int width, int height, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings)](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice(int width, int height, Resolution resolution)](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice(PageSize pageSize, Resolution resolution)](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice(int width, int height, TiffSettings settings)](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice(int width, int height, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice(PageSize pageSize, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice(PageSize pageSize, TiffSettings settings)](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice(int width, int height)](#TiffDevice-int-int-) | 初始化 TiffDevice 类的新实例。 |
| [TiffDevice(PageSize pageSize)](#TiffDevice-com.aspose.pdf.PageSize-) | 初始化 TiffDevice 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [binarizeBradley(InputStream inputImageStream, OutputStream outputImageStream, double threshold)](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | 对输入流进行 Bradley 二值化。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCropRectangle()](#getCropRectangle--) | 获取定义将转换为图片的区域的矩形。 |
| [getFormPresentationMode()](#getFormPresentationMode--) | 获取表单呈现模式。 |
| [getHeight()](#getHeight--) | 获取图像输出高度。 |
| [getRenderingOptions()](#getRenderingOptions--) | 获取渲染选项。 |
| [getResolution()](#getResolution--) | 获取图像分辨率。 |
| [getSettings()](#getSettings--) | 获取将 pdf 映射到 tiff 图像的设置。 |
| [getWidth()](#getWidth--) | 获取图像输出宽度。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [process(IDocument document, int fromPage, int toPage, OutputStream output)](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | 将某些文档页面转换为 tiff 并将其保存在输出流中。 |
| [process(IDocument document, int fromPage, int toPage, String outputFileName)](#process-com.aspose.pdf.IDocument-int-int-java.lang.String-) | 处理文档的某些页面并将结果保存到文件中。 |
| [process(IDocument document, OutputStream output)](#process-com.aspose.pdf.IDocument-java.io.OutputStream-) | 处理整个文档并将结果保存到流中。 |
| [process(IDocument document, String outputFileName)](#process-com.aspose.pdf.IDocument-java.lang.String-) | 处理整个文档并将结果保存到文件中。 |
| [processInternal(IDocument document, System.IO.Stream output)](#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | 处理整个文档并将结果保存到流中。 |
| [processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output)](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | 将某些文档页面转换为 tiff 并将其保存在输出流中。 |
| [setCropRectangle(Rectangle cropRectangle)](#setCropRectangle-com.aspose.pdf.Rectangle-) | 设置矩形，定义将转换为图片的区域。 |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) | 获取表单呈现模式。 |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | 设置渲染选项。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffDevice(Resolution resolution) {#TiffDevice-com.aspose.pdf.devices.Resolution-}
```
public TiffDevice(Resolution resolution)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 结果图像文件的分辨率。 |

### TiffDevice(Resolution resolution, TiffSettings settings) {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(Resolution resolution, TiffSettings settings)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 输出图像的分辨率。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff 设置，参见 TiffSettings 类。 |

### TiffDevice(Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 输出图像的分辨率。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff 设置，参见 TiffSettings 类。 |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | 外部转换器 |

### TiffDevice(TiffSettings settings) {#TiffDevice-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(TiffSettings settings)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff 设置，参见 TiffSettings 类。 |

### TiffDevice(TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(TiffSettings settings, IIndexBitmapConverter converter)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff 设置，参见 TiffSettings 类。 |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | 外部转换器 |

### TiffDevice() {#TiffDevice--}
```
public TiffDevice()
```


使用默认设置初始化 TiffDevice 类的新实例。

### TiffDevice(int width, int height, Resolution resolution, TiffSettings settings) {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(int width, int height, Resolution resolution, TiffSettings settings)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 图像输出宽度。 |
| height | int | 图像输出高度。 |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 输出图像的分辨率。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff 设置，参见 TiffSettings 类。 |

### TiffDevice(int width, int height, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(int width, int height, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 图像输出宽度。 |
| height | int | 图像输出高度。 |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 输出图像的分辨率。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff 设置，参见 TiffSettings 类。 |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | 外部转换器 |

### TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings) {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出图像的页面大小。 |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 输出图像的分辨率。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff 设置，参见 TiffSettings 类。 |

### TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出图像的页面大小。 |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 输出图像的分辨率。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff 设置，参见 TiffSettings 类。 |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | 外部转换器 |

### TiffDevice(int width, int height, Resolution resolution) {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-}
```
public TiffDevice(int width, int height, Resolution resolution)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 图像输出宽度。 |
| height | int | 图像输出高度。 |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 输出图像的分辨率。 |

### TiffDevice(PageSize pageSize, Resolution resolution) {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
```
public TiffDevice(PageSize pageSize, Resolution resolution)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出图像的页面大小。 |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | 输出图像的分辨率。 |

### TiffDevice(int width, int height, TiffSettings settings) {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(int width, int height, TiffSettings settings)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 图像输出宽度。 |
| height | int | 图像输出高度。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff 设置，参见 TiffSettings 类。 |

### TiffDevice(int width, int height, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(int width, int height, TiffSettings settings, IIndexBitmapConverter converter)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 图像输出宽度。 |
| height | int | 图像输出高度。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff 设置，参见 TiffSettings 类。 |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | 外部转换器 |

### TiffDevice(PageSize pageSize, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(PageSize pageSize, TiffSettings settings, IIndexBitmapConverter converter)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出图像的页面大小。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff 设置，参见 TiffSettings 类。 |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | 外部转换器 |

### TiffDevice(PageSize pageSize, TiffSettings settings) {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(PageSize pageSize, TiffSettings settings)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出图像的页面大小。 |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff 设置，参见 TiffSettings 类。 |

### TiffDevice(int width, int height) {#TiffDevice-int-int-}
```
public TiffDevice(int width, int height)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| width | int | 图像输出宽度。 |
| height | int | 图像输出高度。 |

### TiffDevice(PageSize pageSize) {#TiffDevice-com.aspose.pdf.PageSize-}
```
public TiffDevice(PageSize pageSize)
```


初始化 TiffDevice 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | 输出图像的页面大小。 |

### binarizeBradley(InputStream inputImageStream, OutputStream outputImageStream, double threshold) {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
```
public void binarizeBradley(InputStream inputImageStream, OutputStream outputImageStream, double threshold)
```


对输入流进行 Bradley 二值化。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| inputImageStream | java.io.InputStream | 输入图像流。 |
| outputImageStream | java.io.OutputStream | 输出图像流。 |
| threshold | double | 阈值介于 0.0 和 1.0 之间。 |

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
### getCropRectangle() {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```


获取定义将转换为图片的区域的矩形。默认为空，在这种情况下所有图像都转换为页面

**退货：**
[Rectangle](../../com.aspose.pdf/rectangle) - 矩形对象
### getFormPresentationMode() {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```


获取表单呈现模式。

**退货：**
int - FormPresentationMode 值
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
[RenderingOptions](../../com.aspose.pdf/renderingoptions) 渲染选项。
### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


获取图像分辨率。

**退货：**
[Resolution](../../com.aspose.pdf.devices/resolution) 分辨率元素
### getSettings() {#getSettings--}
```
public TiffSettings getSettings()
```


获取将 pdf 映射到 tiff 图像的设置。

**退货：**
[TiffSettings](../../com.aspose.pdf.devices/tiffsettings) - TiffSettings 元素
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### process(IDocument document, int fromPage, int toPage, OutputStream output) {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
```
public void process(IDocument document, int fromPage, int toPage, OutputStream output)
```


将某些文档页面转换为 tiff 并将其保存在输出流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 要转换的文档。 |
| fromPage | int | 定义开始转换的页码。 |
| toPage | int | 定义将结束转换的页码。 |
| output | java.io.OutputStream | 带有 tiff 图像的输出流。 |

### process(IDocument document, int fromPage, int toPage, String outputFileName) {#process-com.aspose.pdf.IDocument-int-int-java.lang.String-}
```
public void process(IDocument document, int fromPage, int toPage, String outputFileName)
```


处理文档的某些页面并将结果保存到文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 要处理的文档。 |
| fromPage | int | 开始处理的第一页。 |
| toPage | int | 处理的最后一页。 |
| outputFileName | java.lang.String | 定义存储处理结果的文件。 |

### process(IDocument document, OutputStream output) {#process-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public void process(IDocument document, OutputStream output)
```


处理整个文档并将结果保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 要处理的文档。 |
| output | java.io.OutputStream | 定义存储处理结果的流。 |

### process(IDocument document, String outputFileName) {#process-com.aspose.pdf.IDocument-java.lang.String-}
```
public void process(IDocument document, String outputFileName)
```


处理整个文档并将结果保存到文件中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 要处理的文档。 |
| outputFileName | java.lang.String | 定义存储处理结果的文件。 |

### processInternal(IDocument document, System.IO.Stream output) {#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(IDocument document, System.IO.Stream output)
```


处理整个文档并将结果保存到流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 要处理的文档。 |
| output | com.aspose.ms.System.IO.Stream | 定义存储处理结果的流。 |

### processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output) {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output)
```


将某些文档页面转换为 tiff 并将其保存在输出流中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 要转换的文档。 |
| fromPage | int | 定义开始转换的页码。 |
| toPage | int | 定义将结束转换的页码。 |
| output | com.aspose.ms.System.IO.Stream | 带有 tiff 图像的输出流。 |

### setCropRectangle(Rectangle cropRectangle) {#setCropRectangle-com.aspose.pdf.Rectangle-}
```
public void setCropRectangle(Rectangle cropRectangle)
```


设置矩形，定义将转换为图片的区域。默认为空，在这种情况下所有图像都转换为页面

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cropRectangle | [Rectangle](../../com.aspose.pdf/rectangle) | 矩形对象 |

### setFormPresentationMode(int value) {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```


获取表单呈现模式。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setRenderingOptions(RenderingOptions value) {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
```
public void setRenderingOptions(RenderingOptions value)
```


设置渲染选项。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [RenderingOptions](../../com.aspose.pdf/renderingoptions) | 渲染选项。 |

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
