---
title: "SvgLoadOptions"
linktitle: "SvgLoadOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "表示将 SVG 文件加载/导入到 PDF 文档的选项。"
type: docs
weight: 4700
url: /zh/java/com.aspose.pdf/svgloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.SvgLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.SvgLoadOptions

```
public final class SvgLoadOptions extends LoadOptions
```

表示将 SVG 文件加载/导入到 PDF 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SvgLoadOptions](#SvgLoadOptions--) | 创建 {@code SvgLoadOptions} 对象。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getConversionEngine](#getConversionEngine--) | 允许选择在转换期间使用的转换引擎。目前新引擎处于 B 测试阶段，因此此值默认设置为 ConversionEngines.LegacyEngine。 |
| [getPageInfo](#getPageInfo--) | 获取在加载文档时应应用的页面信息。 |
| [isAdjustPageSize](#isAdjustPageSize--) | 将 PDF 页面大小调整为 SVG 大小。 |
| [setAdjustPageSize](#setAdjustPageSize-boolean-) | 将 PDF 页面大小调整为 SVG 大小。 |
| [setConversionEngine](#setConversionEngine-int-) | 允许选择在转换期间使用的转换引擎。目前新引擎处于 B 测试阶段，因此此值默认设置为 ConversionEngines.LegacyEngine。 |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | 设置在加载文档时应应用的页面信息。 |

### SvgLoadOptions {#SvgLoadOptions--}
```
public SvgLoadOptions()
```

创建 {@code SvgLoadOptions} 对象。

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

允许选择在转换期间使用的转换引擎。目前新引擎处于 B 测试阶段，因此此值默认设置为 ConversionEngines.LegacyEngine。

**Returns:**
ConversionEngines 元素 @see ConversionEngines

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

获取在加载文档时应应用的页面信息。

**Returns:**
PageInfo 对象

### isAdjustPageSize {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```

将 PDF 页面大小调整为 SVG 大小。

**Returns:**
布尔值

### setAdjustPageSize {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```

将 PDF 页面大小调整为 SVG 大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

允许选择在转换期间使用的转换引擎。目前新引擎处于 B 测试阶段，因此此值默认设置为 ConversionEngines.LegacyEngine。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| conversionEngine |  | ConversionEngines 元素 @see ConversionEngines |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
设置在加载文档时应应用的页面信息。
