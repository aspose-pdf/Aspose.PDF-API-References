---
title: "RenderingOptions"
linktitle: "RenderingOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示渲染选项"
type: docs
weight: 4150
url: /zh/java/com.aspose.pdf/renderingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.RenderingOptions

```
public final class RenderingOptions extends Object
```

表示渲染选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RenderingOptions](#RenderingOptions--) | 初始化 {@code RenderingOptions} 对象的新实例。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getAnalyzeFonts](#getAnalyzeFonts--) | 根据需要替换字体，以确保文本中的所有字符都能显示。字体替换算法遵循以下步骤：1. 如果用户显式设置了 DefaultFontName 属性，检查指定的字体是否能够显示所需字符。2. 如果未设置用户定义的字体，则通过 {@code FontRepository.Sources} 添加的字体进行搜索。3. 分析文本以识别其字母表或书写系统，并相应地建议字体名称。尝试从系统中定位并使用这些字体。4. 作为后备方案，搜索系统中任何能够显示所需字符的字体。 |
| [getBarcodeOptimization](#getBarcodeOptimization--) | 获取条形码优化模式。 |
| [getConvertFontsToUnicodeTTF](#getConvertFontsToUnicodeTTF--) | 指示所有字体将被转换为 TTF Unicode 版本。这对于兼容性和优化字体使用很有用，因为每个新的 TTF 字体将不包含源字体的所有符号，而只包含文本中使用的符号。 |
| [getDefaultFontName](#getDefaultFontName--) | 获取/设置用于替代缺失字体的默认字体名称。 |
| [getHeightExtraUnits](#getHeightExtraUnits--) | 获取或设置用于增大或减小 AppendRectangle 操作符矩形宽度的值。 |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | 获取或设置是否忽略与缺少字体相关的错误的指示。true 表示将忽略缺少字体的错误，处理时会跳过引用错误资源的文本段落。默认值为 false。 |
| [getInterpolationHighQuality](#getInterpolationHighQuality--) | 获取或设置插值的高质量模式。 |
| [getMaxFontsCacheSize](#getMaxFontsCacheSize--) | 字体缓存中的最大字体数量。默认值为 10。 |
| [getMaxSymbolsCacheSize](#getMaxSymbolsCacheSize--) | 符号缓存中的最大符号数量。默认值为 100。 |
| [getOptimizeDimensions](#getOptimizeDimensions--) | 获取或设置优化尺寸模式。 |
| [getScaleImagesToFitPageWidth](#getScaleImagesToFitPageWidth--) | 获取或设置用于将页面上所有图像缩放以适应页面宽度的值。 |
| [getSystemFontsNativeRendering](#getSystemFontsNativeRendering--) | 获取系统字体本地渲染的模式 |
| [getUseFontHinting](#getUseFontHinting--) | 使用此标志会开启字体微调机制。字体微调是使用数学指令来调整轮廓字体的显示方式。在某些情况下，开启此标志可能会解决文本可读性问题。目前，此标志的使用仅对 TTF 字体生效，前提是这些字体在源文档中被使用。 |
| [getUseNewImagingEngine](#getUseNewImagingEngine--) | 获取决定是否使用新成像引擎的标志。 |
| [getWidthExtraUnits](#getWidthExtraUnits--) | 获取或设置用于增大或减小 AppendRectangle 操作符矩形宽度的值。 |
| [isTryToSkipDocumentErrors](#isTryToSkipDocumentErrors--) | 获取在处理 PDF 文件时用于跳过错误的值 |
| [setAnalyzeFonts](#setAnalyzeFonts-boolean-) | 根据需要替换字体，以确保文本中的所有字符都能显示。字体替换算法遵循以下步骤：1. 如果用户显式设置了 DefaultFontName 属性，检查指定的字体是否能够显示所需字符。2. 如果未设置用户定义的字体，则通过 {@code FontRepository.Sources} 添加的字体进行搜索。3. 分析文本以识别其字母表或书写系统，并相应地建议字体名称。尝试从系统中定位并使用这些字体。4. 作为后备方案，搜索系统中任何能够显示所需字符的字体。 |
| [setBarcodeOptimization](#setBarcodeOptimization-boolean-) | 设置条形码优化模式。 |
| [setConvertFontsToUnicodeTTF](#setConvertFontsToUnicodeTTF-boolean-) | 指示所有字体将被转换为 TTF Unicode 版本。这对于兼容性和优化字体使用很有用，因为每个新的 TTF 字体将不包含源字体的所有符号，而只包含文本中使用的符号。 |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | 获取/设置用于替代缺失字体的默认字体名称。 |
| [setHeightExtraUnits](#setHeightExtraUnits-float-) | 获取或设置用于增大或减小 AppendRectangle 操作符矩形宽度的值。 |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | 获取或设置是否忽略与缺少字体相关的错误的指示。true 表示将忽略缺少字体的错误，处理时会跳过引用错误资源的文本段落。默认值为 false。 |
| [setInterpolationHighQuality](#setInterpolationHighQuality-boolean-) | 获取或设置插值的高质量模式。 |
| [setMaxFontsCacheSize](#setMaxFontsCacheSize-int-) | 字体缓存中的最大字体数量。默认值为 10。 |
| [setMaxSymbolsCacheSize](#setMaxSymbolsCacheSize-int-) | 符号缓存中的最大符号数量。默认值为 100。 |
| [setOptimizeDimensions](#setOptimizeDimensions-boolean-) | 获取或设置优化尺寸模式。 |
| [setScaleImagesToFitPageWidth](#setScaleImagesToFitPageWidth-boolean-) | 获取或设置用于将页面上所有图像缩放以适应页面宽度的值。 |
| [setSystemFontsNativeRendering](#setSystemFontsNativeRendering-boolean-) | 设置系统字体本地渲染的模式 |
| [setTryToSkipDocumentErrors](#setTryToSkipDocumentErrors-boolean-) | 设置在处理 PDF 文件时用于跳过错误的值 |
| [setUseFontHinting](#setUseFontHinting-boolean-) | 使用此标志会开启字体微调机制。字体微调是使用数学指令来调整轮廓字体的显示方式。在某些情况下，开启此标志可能会解决文本可读性问题。目前，此标志的使用仅对 TTF 字体生效，前提是这些字体在源文档中被使用。 |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | 设置决定是否使用新成像引擎的标志。 |
| [setWidthExtraUnits](#setWidthExtraUnits-float-) | 获取或设置用于增大或减小 AppendRectangle 操作符矩形宽度的值。 |

### RenderingOptions {#RenderingOptions--}
```
public RenderingOptions()
```

初始化 {@code RenderingOptions} 对象的新实例。

### getAnalyzeFonts {#getAnalyzeFonts--}
```
public final boolean getAnalyzeFonts()
```

根据需要替换字体，以确保文本中的所有字符都能显示。字体替换算法遵循以下步骤：1. 如果用户显式设置了 DefaultFontName 属性，检查指定的字体是否能够显示所需字符。2. 如果未设置用户定义的字体，则通过 {@code FontRepository.Sources} 添加的字体进行搜索。3. 分析文本以识别其字母表或书写系统，并相应地建议字体名称。尝试从系统中定位并使用这些字体。4. 作为后备方案，搜索系统中任何能够显示所需字符的字体。

**Returns:**
布尔值

### getBarcodeOptimization {#getBarcodeOptimization--}
```
public boolean getBarcodeOptimization()
```

获取条形码优化模式。

**Returns:**
布尔值

### getConvertFontsToUnicodeTTF {#getConvertFontsToUnicodeTTF--}
```
public boolean getConvertFontsToUnicodeTTF()
```

指示所有字体将被转换为 TTF Unicode 版本。这对于兼容性和优化字体使用很有用，因为每个新的 TTF 字体将不包含源字体的所有符号，而只包含文本中使用的符号。

**Returns:**
布尔值

### getDefaultFontName {#getDefaultFontName--}
```
public final String getDefaultFontName()
```

获取/设置用于替代缺失字体的默认字体名称。

**Returns:**
字符串值

### getHeightExtraUnits {#getHeightExtraUnits--}
```
public final float getHeightExtraUnits()
```

获取或设置用于增大或减小 AppendRectangle 操作符矩形宽度的值。

**Returns:**
float 值

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

获取或设置是否忽略与缺少字体相关的错误的指示。true 表示将忽略缺少字体的错误，处理时会跳过引用错误资源的文本段落。默认值为 false。

**Returns:**
布尔值

### getInterpolationHighQuality {#getInterpolationHighQuality--}
```
public boolean getInterpolationHighQuality()
```

获取或设置插值的高质量模式。

**Returns:**
布尔值

### getMaxFontsCacheSize {#getMaxFontsCacheSize--}
```
public int getMaxFontsCacheSize()
```

字体缓存中的最大字体数量。默认值为 10。

**Returns:**
int 值

### getMaxSymbolsCacheSize {#getMaxSymbolsCacheSize--}
```
public int getMaxSymbolsCacheSize()
```

符号缓存中的最大符号数量。默认值为 100。

**Returns:**
int 值

### getOptimizeDimensions {#getOptimizeDimensions--}
```
public final boolean getOptimizeDimensions()
```

获取或设置优化尺寸模式。

**Returns:**
布尔值

### getScaleImagesToFitPageWidth {#getScaleImagesToFitPageWidth--}
```
@Deprecated public final boolean getScaleImagesToFitPageWidth()
```

获取或设置用于将页面上所有图像缩放以适应页面宽度的值。

**Returns:**
布尔值 @deprecated ScaleImagesToFitPageWidth 已弃用。

### getSystemFontsNativeRendering {#getSystemFontsNativeRendering--}
```
public boolean getSystemFontsNativeRendering()
```

获取系统字体本地渲染的模式

**Returns:**
布尔值

### getUseFontHinting {#getUseFontHinting--}
```
public boolean getUseFontHinting()
```

使用此标志会开启字体微调机制。字体微调是使用数学指令来调整轮廓字体的显示方式。在某些情况下，开启此标志可能会解决文本可读性问题。目前，此标志的使用仅对 TTF 字体生效，前提是这些字体在源文档中被使用。

**Returns:**
布尔值

### getUseNewImagingEngine {#getUseNewImagingEngine--}
```
@Deprecated public boolean getUseNewImagingEngine()
```

获取决定是否使用新成像引擎的标志。

**Returns:**
布尔值 @deprecated UseNewImagingEngine 已弃用

### getWidthExtraUnits {#getWidthExtraUnits--}
```
public float getWidthExtraUnits()
```

获取或设置用于增大或减小 AppendRectangle 操作符矩形宽度的值。

**Returns:**
float 值

### isTryToSkipDocumentErrors {#isTryToSkipDocumentErrors--}
```
public boolean isTryToSkipDocumentErrors()
```

获取在处理 PDF 文件时用于跳过错误的值

**Returns:**
布尔值

### setAnalyzeFonts {#setAnalyzeFonts-boolean-}
```
public final void setAnalyzeFonts(boolean value)
```

根据需要替换字体，以确保文本中的所有字符都能显示。字体替换算法遵循以下步骤：1. 如果用户显式设置了 DefaultFontName 属性，检查指定的字体是否能够显示所需字符。2. 如果未设置用户定义的字体，则通过 {@code FontRepository.Sources} 添加的字体进行搜索。3. 分析文本以识别其字母表或书写系统，并相应地建议字体名称。尝试从系统中定位并使用这些字体。4. 作为后备方案，搜索系统中任何能够显示所需字符的字体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setBarcodeOptimization {#setBarcodeOptimization-boolean-}
```
public void setBarcodeOptimization(boolean value)
```

设置条形码优化模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setConvertFontsToUnicodeTTF {#setConvertFontsToUnicodeTTF-boolean-}
```
public void setConvertFontsToUnicodeTTF(boolean value)
```

指示所有字体将被转换为 TTF Unicode 版本。这对于兼容性和优化字体使用很有用，因为每个新的 TTF 字体将不包含源字体的所有符号，而只包含文本中使用的符号。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
获取/设置用于替代缺失字体的默认字体名称。

### setHeightExtraUnits {#setHeightExtraUnits-float-}
```
public final void setHeightExtraUnits(float value)
```

获取或设置用于增大或减小 AppendRectangle 操作符矩形宽度的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

获取或设置是否忽略与缺少字体相关的错误的指示。true 表示将忽略缺少字体的错误，处理时会跳过引用错误资源的文本段落。默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setInterpolationHighQuality {#setInterpolationHighQuality-boolean-}
```
public void setInterpolationHighQuality(boolean value)
```

获取或设置插值的高质量模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setMaxFontsCacheSize {#setMaxFontsCacheSize-int-}
```
public void setMaxFontsCacheSize(int value)
```

字体缓存中的最大字体数量。默认值为 10。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setMaxSymbolsCacheSize {#setMaxSymbolsCacheSize-int-}
```
public void setMaxSymbolsCacheSize(int value)
```

符号缓存中的最大符号数量。默认值为 100。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setOptimizeDimensions {#setOptimizeDimensions-boolean-}
```
public final void setOptimizeDimensions(boolean value)
```

获取或设置优化尺寸模式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setScaleImagesToFitPageWidth {#setScaleImagesToFitPageWidth-boolean-}
```
@Deprecated public final void setScaleImagesToFitPageWidth(boolean value)
```

获取或设置用于将页面上所有图像缩放以适应页面宽度的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 @deprecated ScaleImagesToFitPageWidth 已弃用。 |

### setSystemFontsNativeRendering {#setSystemFontsNativeRendering-boolean-}
```
public void setSystemFontsNativeRendering(boolean value)
```

设置系统字体本地渲染的模式

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setTryToSkipDocumentErrors {#setTryToSkipDocumentErrors-boolean-}
```
public void setTryToSkipDocumentErrors(boolean value)
```

设置在处理 PDF 文件时用于跳过错误的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUseFontHinting {#setUseFontHinting-boolean-}
```
public void setUseFontHinting(boolean value)
```

使用此标志会开启字体微调机制。字体微调是使用数学指令来调整轮廓字体的显示方式。在某些情况下，开启此标志可能会解决文本可读性问题。目前，此标志的使用仅对 TTF 字体生效，前提是这些字体在源文档中被使用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public void setUseNewImagingEngine(boolean value)
```

设置决定是否使用新成像引擎的标志。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 @deprecated UseNewImagingEngine 已弃用 |

### setWidthExtraUnits {#setWidthExtraUnits-float-}
```
public void setWidthExtraUnits(float value)
```

获取或设置用于增大或减小 AppendRectangle 操作符矩形宽度的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | float 值 |
