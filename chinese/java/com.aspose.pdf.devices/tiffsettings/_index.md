---
title: TiffSettings
second_title: 用于 Java API 参考的 Aspose.PDF
description: 此类表示将 pdf 导入 Tiff 的设置。
type: docs
weight: 29
url: /zh/java/com.aspose.pdf.devices/tiffsettings/
---
**遗产：**
java.lang.Object
```
public final class TiffSettings
```

此类表示将 pdf 导入 Tiff 的设置。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffSettings()](#TiffSettings--) | 初始化 TiffSettings 类的新实例。 |
| [TiffSettings(int compressionType)](#TiffSettings-int-) | 初始化 TiffSettings 类的新实例。 |
| [TiffSettings(Margins margins)](#TiffSettings-com.aspose.pdf.devices.Margins-) | 初始化 TiffSettings 类的新实例。 |
| [TiffSettings(int compressionType, int colorDepth, Margins margins)](#TiffSettings-int-int-com.aspose.pdf.devices.Margins-) | 初始化 TiffSettings 类的新实例。 |
| [TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages)](#TiffSettings-int-int-com.aspose.pdf.devices.Margins-boolean-) | 初始化 TiffSettings 类的新实例。 |
| [TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages, int shapeType)](#TiffSettings-int-int-com.aspose.pdf.devices.Margins-boolean-int-) | 初始化 TiffSettings 类的新实例。 |
| [TiffSettings(boolean skipBlankPages)](#TiffSettings-boolean-) | 初始化 TiffSettings 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBrightness()](#getBrightness--) | 获取白色和黑色颜色转换的值边界。 |
| [getClass()](#getClass--) |  |
| [getCompression()](#getCompression--) | 获取压缩类型。 |
| [getCoordinateType()](#getCoordinateType--) | 获取页面坐标类型（媒体/裁剪框）。 |
| [getDepth()](#getDepth--) | 获取颜色深度。 |
| [getIndexedConversionType()](#getIndexedConversionType--) | 获取 IndexedConversionType。 |
| [getMargins()](#getMargins--) | 获取边距。 |
| [getShape()](#getShape--) | 获取形状的类型。 |
| [getSkipBlankPages()](#getSkipBlankPages--) | 获取一个值，该值指示是否跳过空白页。 |
| [hashCode()](#hashCode--) |  |
| [isUseAlternativeImageEngine()](#isUseAlternativeImageEngine--) | 获取一个标志，确定是否使用替代成像引擎。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrightness(float value)](#setBrightness-float-) | 设置白色和黑色转换颜色的值边界。 |
| [setCompression(int value)](#setCompression-int-) | 设置压缩类型。 |
| [setCoordinateType(int value)](#setCoordinateType-int-) | 设置页面坐标类型（媒体/裁剪框）。 |
| [setDepth(int value)](#setDepth-int-) | 获取颜色深度。 |
| [setIndexedConversionType(int value)](#setIndexedConversionType-int-) | 设置 IndexedConversionType。 |
| [setShape(int value)](#setShape-int-) | 设置形状的类型。 |
| [setSkipBlankPages(boolean value)](#setSkipBlankPages-boolean-) | 设置一个值，指示是否跳过空白页。 |
| [setUseAlternativeImageEngine(boolean useAlternativeImageEngine)](#setUseAlternativeImageEngine-boolean-) | 设置一个标志以确定是否使用替代成像引擎。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffSettings() {#TiffSettings--}
```
public TiffSettings()
```


初始化 TiffSettings 类的新实例。

### TiffSettings(int compressionType) {#TiffSettings-int-}
```
public TiffSettings(int compressionType)
```


初始化 TiffSettings 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| compressionType | int | 压缩类型。 |

### TiffSettings(Margins margins) {#TiffSettings-com.aspose.pdf.devices.Margins-}
```
public TiffSettings(Margins margins)
```


初始化 TiffSettings 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| margins | [Margins](../../com.aspose.pdf.devices/margins) | 边距。 |

### TiffSettings(int compressionType, int colorDepth, Margins margins) {#TiffSettings-int-int-com.aspose.pdf.devices.Margins-}
```
public TiffSettings(int compressionType, int colorDepth, Margins margins)
```


初始化 TiffSettings 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| compressionType | int | 压缩类型。 |
| colorDepth | int | 颜色深度。 |
| margins | [Margins](../../com.aspose.pdf.devices/margins) | 边距。 |

### TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages) {#TiffSettings-int-int-com.aspose.pdf.devices.Margins-boolean-}
```
public TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages)
```


初始化 TiffSettings 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| compressionType | int | 压缩类型。 |
| colorDepth | int | 颜色深度。 |
| margins | [Margins](../../com.aspose.pdf.devices/margins) | 边距。 |
| skipBlankPages | boolean | 如果设置为 true 需要跳过空白页 |

### TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages, int shapeType) {#TiffSettings-int-int-com.aspose.pdf.devices.Margins-boolean-int-}
```
public TiffSettings(int compressionType, int colorDepth, Margins margins, boolean skipBlankPages, int shapeType)
```


初始化 TiffSettings 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| compressionType | int | 压缩类型。 |
| colorDepth | int | 颜色深度。 |
| margins | [Margins](../../com.aspose.pdf.devices/margins) | 边距。 |
| skipBlankPages | boolean | 如果设置为 true 需要跳过空白页。 |
| shapeType | int | 形状的类型。 |

### TiffSettings(boolean skipBlankPages) {#TiffSettings-boolean-}
```
public TiffSettings(boolean skipBlankPages)
```


初始化 TiffSettings 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| skipBlankPages | boolean | 如果设置为真[跳过空白页]。 |

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
### getBrightness() {#getBrightness--}
```
public float getBrightness()
```


获取白色和黑色颜色转换的值边界。此参数可与 EncoderValue.CompressionCCITT4、EncoderValue.CompressionCCITT3、EncoderValue.CompressionRle 或 ColorDepth.Format1bpp == 1 一起应用

**退货：**
float - 亮度的浮点值应在 0 到 1 的范围内。默认值等于 0.33f
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCompression() {#getCompression--}
```
public int getCompression()
```


获取压缩类型。

值：压缩的类型。

--------------------

默认值为 CompressionType.LZW

**退货：**
int - CompressionType 元素
### getCoordinateType() {#getCoordinateType--}
```
public int getCoordinateType()
```


获取页面坐标类型（媒体/裁剪框）。默认使用 CropBox 值。

**退货：**
int - PageCoordinateType 值
### getDepth() {#getDepth--}
```
public int getDepth()
```


获取颜色深度。

值：颜色深度。

--------------------

默认值为 ColorDepth.Default

**退货：**
int - ColorDepth 元素
### getIndexedConversionType() {#getIndexedConversionType--}
```
public int getIndexedConversionType()
```


获取 IndexedConversionType。默认值为简单。

**退货：**
int - IndexedConversionType 元素
### getMargins() {#getMargins--}
```
public Margins getMargins()
```


获取边距。

**退货：**
[Margins](../../com.aspose.pdf.devices/margins) 边距对象
### getShape() {#getShape--}
```
public int getShape()
```


获取形状的类型。

值：形状的类型。

--------------------

默认值为 ShapeType.None

**退货：**
int - ShapeType 元素
### getSkipBlankPages() {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```


获取一个值，该值指示是否跳过空白页。

值：如果需要跳过空白页则为真；否则，假的。

--------------------

默认值为假

**退货：**
boolean - 布尔值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isUseAlternativeImageEngine() {#isUseAlternativeImageEngine--}
```
public boolean isUseAlternativeImageEngine()
```


获取一个标志，确定是否使用替代成像引擎。 Linux 操作系统默认使用真值。对于 Windows 操作系统，默认值为 false。

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




### setBrightness(float value) {#setBrightness-float-}
```
public void setBrightness(float value)
```


设置白色和黑色转换颜色的值边界。此参数可与 EncoderValue.CompressionCCITT4、EncoderValue.CompressionCCITT3、EncoderValue.CompressionRle 或 ColorDepth.Format1bpp == 1 一起应用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | float | ：亮度值应在 0 到 1 的范围内。默认值等于 0.33f |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


设置压缩类型。

值：压缩的类型。

--------------------

默认值为 CompressionType.LZW

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | CompressionType 元素 |

### setCoordinateType(int value) {#setCoordinateType-int-}
```
public void setCoordinateType(int value)
```


设置页面坐标类型（媒体/裁剪框）。默认使用 CropBox 值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 页面坐标类型 |

### setDepth(int value) {#setDepth-int-}
```
public void setDepth(int value)
```


获取颜色深度。

值：颜色深度。

--------------------

默认值为 ColorDepth.Default

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ColorDepth 元素 |

### setIndexedConversionType(int value) {#setIndexedConversionType-int-}
```
public void setIndexedConversionType(int value)
```


设置 IndexedConversionType。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | IndexedConversionType 元素 |

### setShape(int value) {#setShape-int-}
```
public void setShape(int value)
```


设置形状的类型。

值：形状的类型。

--------------------

默认值为 ShapeType.None

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | ShapeType 元素 |

### setSkipBlankPages(boolean value) {#setSkipBlankPages-boolean-}
```
public void setSkipBlankPages(boolean value)
```


设置一个值，指示是否跳过空白页。

值：如果需要跳过空白页则为真；否则，假的。

--------------------

默认值为假

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setUseAlternativeImageEngine(boolean useAlternativeImageEngine) {#setUseAlternativeImageEngine-boolean-}
```
public void setUseAlternativeImageEngine(boolean useAlternativeImageEngine)
```


设置一个标志以确定是否使用替代成像引擎。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| useAlternativeImageEngine | boolean | 布尔值 |

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
