---
title: "TiffSettings"
linktitle: "TiffSettings"
second_title: "Aspose.PDF for Java API 参考"
description: "此类表示将 pdf 导入为 Tiff 的设置。"
type: docs
weight: 220
url: /zh/java/com.aspose.pdf.devices/tiffsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.TiffSettings

```
public final class TiffSettings extends Object
```

此类表示将 pdf 导入为 Tiff 的设置。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffSettings](#TiffSettings--) | 初始化 {@code TiffSettings} 类的新实例。 |
| [TiffSettings](#TiffSettings-boolean-) | 初始化 {@code TiffSettings} 类的新实例。 |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.ColorDepth-) | 初始化 {@code TiffSettings} 类的新实例。 |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-) | 初始化 {@code TiffSettings} 类的新实例。 |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-) | 初始化 {@code TiffSettings} 类的新实例。 |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-) | 初始化 {@code TiffSettings} 类的新实例。 |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-) | 初始化 {@code TiffSettings} 类的新实例。 |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.Margins-) | 初始化 {@code TiffSettings} 类的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBrightness](#getBrightness--) | 获取白色和黑色颜色转换的阈值。此参数可与 EncoderValue.CompressionCCITT4、EncoderValue.CompressionCCITT3、EncoderValue.CompressionRle 或 ColorDepth.Format1bpp == 1 一起使用。 |
| [getCompression](#getCompression--) | <p> 获取压缩类型。 </p> Value: 压缩的类型。 <hr> <p> 默认值为 CompressionType.LZW </p> |
| [getCoordinateType](#getCoordinateType--) | 获取页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。 |
| [getDepth](#getDepth--) | <p> 获取颜色深度。 </p> 值：颜色深度。 <hr> <p> 默认值为 ColorDepth.Default </p> |
| [getIndexedConversionType](#getIndexedConversionType--) | 获取 IndexedConversionType。 默认值为 Simple。 |
| [getMargins](#getMargins--) | 获取边距。 |
| [getShape](#getShape--) | <p> 获取形状的类型。 </p> 值：形状的类型。 <hr> <p> 默认值为 ShapeType.None </p> |
| [getSkipBlankPages](#getSkipBlankPages--) | <p> 获取指示是否跳过空白页的值。 </p> 值：{@code true} 表示需要跳过空白页；否则为 {@code false}。 <hr> <p> 默认值为 false </p> |
| [isUseAlternativeImageEngine](#isUseAlternativeImageEngine--) | 获取标志以确定是否使用替代成像引擎。 对于 Linux 操作系统，默认使用 true 值。 对于 Windows 操作系统，默认值为 false。 |
| [setBrightness](#setBrightness-float-) | 设置白色和黑色颜色转换的阈值。 此参数可与 EncoderValue.CompressionCCITT4、EncoderValue.CompressionCCITT3、EncoderValue.CompressionRle 或 ColorDepth.Format1bpp == 1 一起使用。 |
| [setCompression](#setCompression-com.aspose.pdf.devices.CompressionType-) | <p> 设置压缩类型。 </p> 值：压缩的类型。 <hr> <p> 默认值为 CompressionType.LZW </p> |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | 设置页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。 |
| [setDepth](#setDepth-com.aspose.pdf.devices.ColorDepth-) | <p> 获取颜色深度。 </p> 值：颜色深度。 <hr> <p> 默认值为 ColorDepth.Default </p> |
| [setIndexedConversionType](#setIndexedConversionType-int-) | 设置 IndexedConversionType。 |
| [setShape](#setShape-com.aspose.pdf.devices.ShapeType-) | <p> 设置形状的类型。 </p> 值：形状的类型。 <hr> <p> 默认值为 ShapeType.None </p> |
| [setSkipBlankPages](#setSkipBlankPages-boolean-) | <p> 设置指示是否跳过空白页的值。 </p> 值：{@code true} 表示需要跳过空白页；否则为 {@code false}。 <hr> <p> 默认值为 false </p> |
| [setUseAlternativeImageEngine](#setUseAlternativeImageEngine-boolean-) | 设置标志以确定是否使用替代成像引擎。 |

### TiffSettings {#TiffSettings--}
```
public TiffSettings()
```

初始化 {@code TiffSettings} 类的新实例。

### TiffSettings {#TiffSettings-boolean-}
```
public TiffSettings(boolean skipBlankPages)
```

初始化 {@code TiffSettings} 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| skipBlankPages |  | 如果设置为 {@code true} [跳过空白页]。 |

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.ColorDepth-}
初始化 {@code TiffSettings} 类的新实例。

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-}
初始化 {@code TiffSettings} 类的新实例。

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-}
初始化 {@code TiffSettings} 类的新实例。

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-}
初始化 {@code TiffSettings} 类的新实例。

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-}
初始化 {@code TiffSettings} 类的新实例。

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.Margins-}
初始化 {@code TiffSettings} 类的新实例。

### getBrightness {#getBrightness--}
```
public float getBrightness()
```

获取白色和黑色颜色转换的阈值。此参数可与 EncoderValue.CompressionCCITT4、EncoderValue.CompressionCCITT3、EncoderValue.CompressionRle 或 ColorDepth.Format1bpp == 1 一起使用。

**Returns:**
亮度的浮点值应在 0 到 1 的范围内。 默认值等于 0.33f。

### getCompression {#getCompression--}
```
public CompressionType getCompression()
```

<p> 获取压缩类型。 </p> Value: 压缩的类型。 <hr> <p> 默认值为 CompressionType.LZW </p>

**Returns:**
CompressionType 元素 @see CompressionType

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

获取页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。

**Returns:**
PageCoordinateType 值 @see PageCoordinateType

### getDepth {#getDepth--}
```
public ColorDepth getDepth()
```

<p> 获取颜色深度。 </p> 值：颜色深度。 <hr> <p> 默认值为 ColorDepth.Default </p>

**Returns:**
ColorDepth 元素 @see ColorDepth

### getIndexedConversionType {#getIndexedConversionType--}
```
public int getIndexedConversionType()
```

获取 IndexedConversionType。 默认值为 Simple。

**Returns:**
IndexedConversionType 元素 @see IndexedConversionType

### getMargins {#getMargins--}
```
public Margins getMargins()
```

获取边距。

**Returns:**
Margins 对象

### getShape {#getShape--}
```
public ShapeType getShape()
```

<p> 获取形状的类型。 </p> 值：形状的类型。 <hr> <p> 默认值为 ShapeType.None </p>

**Returns:**
ShapeType 元素 @see ShapeType

### getSkipBlankPages {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```

<p> 获取指示是否跳过空白页的值。 </p> 值：{@code true} 表示需要跳过空白页；否则为 {@code false}。 <hr> <p> 默认值为 false </p>

**Returns:**
布尔值

### isUseAlternativeImageEngine {#isUseAlternativeImageEngine--}
```
public boolean isUseAlternativeImageEngine()
```

获取标志以确定是否使用替代成像引擎。 对于 Linux 操作系统，默认使用 true 值。 对于 Windows 操作系统，默认值为 false。

**Returns:**
布尔值

### setBrightness {#setBrightness-float-}
```
public void setBrightness(float value)
```

设置白色和黑色颜色转换的阈值。 此参数可与 EncoderValue.CompressionCCITT4、EncoderValue.CompressionCCITT3、EncoderValue.CompressionRle 或 ColorDepth.Format1bpp == 1 一起使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | : 亮度的值应在 0 到 1 的范围内。 默认值等于 0.33f |

### setCompression {#setCompression-com.aspose.pdf.devices.CompressionType-}
<p> 设置压缩类型。 </p> 值：压缩的类型。 <hr> <p> 默认值为 CompressionType.LZW </p>

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
设置页面坐标类型（Media/Crop 框）。默认使用 CropBox 值。

### setDepth {#setDepth-com.aspose.pdf.devices.ColorDepth-}
<p> 获取颜色深度。 </p> 值：颜色深度。 <hr> <p> 默认值为 ColorDepth.Default </p>

### setIndexedConversionType {#setIndexedConversionType-int-}
```
public void setIndexedConversionType(int value)
```

设置 IndexedConversionType。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | IndexedConversionType 元素 @see IndexedConversionType |

### setShape {#setShape-com.aspose.pdf.devices.ShapeType-}
<p> 设置形状的类型。 </p> 值：形状的类型。 <hr> <p> 默认值为 ShapeType.None </p>

### setSkipBlankPages {#setSkipBlankPages-boolean-}
```
public void setSkipBlankPages(boolean value)
```

<p> 设置指示是否跳过空白页的值。 </p> 值：{@code true} 表示需要跳过空白页；否则为 {@code false}。 <hr> <p> 默认值为 false </p>

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUseAlternativeImageEngine {#setUseAlternativeImageEngine-boolean-}
```
public void setUseAlternativeImageEngine(boolean useAlternativeImageEngine)
```

设置标志以确定是否使用替代成像引擎。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| useAlternativeImageEngine |  | 布尔值 |
