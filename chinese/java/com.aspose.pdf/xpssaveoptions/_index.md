---
title: "XpsSaveOptions"
linktitle: "XpsSaveOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "导出为 Xps 格式的保存选项"
type: docs
weight: 5770
url: /zh/java/com.aspose.pdf/xpssaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.XpsSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class XpsSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

导出为 Xps 格式的保存选项

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XpsSaveOptions](#XpsSaveOptions--) | 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBatchSize](#getBatchSize--) | 如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。 |
| [getDefaultFont](#getDefaultFont--) | 获取/设置默认字体名称。如果系统中未找到嵌入的字体名称，则使用它。 |
| [getSaveTransparentTexts](#getSaveTransparentTexts--) | 指示是否保留透明（OCR）文本。 |
| [getUseEmbeddedTrueTypeFonts](#getUseEmbeddedTrueTypeFonts--) | 获取/设置使用嵌入式 TrueType 字体的标志。避免使用嵌入式 TrueType 字体可以减少转换时间。 |
| [isUseNewImagingEngine](#isUseNewImagingEngine--) | 获取或设置 UseNewImagingEngine 选项。 |
| [setBatchSize](#setBatchSize-int-) | 如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。 |
| [setDefaultFont](#setDefaultFont-java.lang.String-) | 获取/设置默认字体名称。如果系统中未找到嵌入的字体名称，则使用它。 |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | 指示是否保留透明（OCR）文本。 |
| [setUseEmbeddedTrueTypeFonts](#setUseEmbeddedTrueTypeFonts-boolean-) | 获取/设置使用嵌入式 TrueType 字体的标志。避免使用嵌入式 TrueType 字体可以减少转换时间。 |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | 获取或设置 UseNewImagingEngine 选项。 |

### XpsSaveOptions {#XpsSaveOptions--}
```
public XpsSaveOptions()
```

构造函数

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。

**Returns:**
int 值

### getDefaultFont {#getDefaultFont--}
```
public final String getDefaultFont()
```

获取/设置默认字体名称。如果系统中未找到嵌入的字体名称，则使用它。

**Returns:**
字符串值

### getSaveTransparentTexts {#getSaveTransparentTexts--}
```
public final boolean getSaveTransparentTexts()
```

指示是否保留透明（OCR）文本。

**Returns:**
布尔值

### getUseEmbeddedTrueTypeFonts {#getUseEmbeddedTrueTypeFonts--}
```
public final boolean getUseEmbeddedTrueTypeFonts()
```

获取/设置使用嵌入式 TrueType 字体的标志。避免使用嵌入式 TrueType 字体可以减少转换时间。

**Returns:**
布尔值

### isUseNewImagingEngine {#isUseNewImagingEngine--}
```
@Deprecated public final boolean isUseNewImagingEngine()
```

获取或设置 UseNewImagingEngine 选项。

**Returns:**
布尔值 @deprecated UseNewImagingEngine 已弃用

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

如果批量转换适用于源格式和目标格式的配对，则定义批处理大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setDefaultFont {#setDefaultFont-java.lang.String-}
获取/设置默认字体名称。如果系统中未找到嵌入的字体名称，则使用它。

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public final void setSaveTransparentTexts(boolean value)
```

指示是否保留透明（OCR）文本。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUseEmbeddedTrueTypeFonts {#setUseEmbeddedTrueTypeFonts-boolean-}
```
public final void setUseEmbeddedTrueTypeFonts(boolean value)
```

获取/设置使用嵌入式 TrueType 字体的标志。避免使用嵌入式 TrueType 字体可以减少转换时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public final void setUseNewImagingEngine(boolean value)
```

获取或设置 UseNewImagingEngine 选项。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 @deprecated UseNewImagingEngine 已弃用 |
