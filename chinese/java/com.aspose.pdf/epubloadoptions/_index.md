---
title: "EpubLoadOptions"
linktitle: "EpubLoadOptions"
second_title: "Aspose.PDF for Java API 参考"
description: "包含将 EPUB 文件加载/导入到 pdf 文档的选项。"
type: docs
weight: 1220
url: /zh/java/com.aspose.pdf/epubloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.EpubLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.EpubLoadOptions

```
public final class EpubLoadOptions extends LoadOptions
```

包含将 EPUB 文件加载/导入到 pdf 文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EpubLoadOptions](#EpubLoadOptions--) | 创建用于将 EPUB 文件转换为 PDF 文档的默认加载选项。默认 PDF 页面尺寸 - A4 300dpi 2480 × 3508。 |
| [EpubLoadOptions](#EpubLoadOptions-java.awt.geom.Dimension2D-) | 创建用于将 EPUB 文件转换为 PDF 文档的默认加载选项。默认 PDF 页面尺寸 - A4 300dpi 2480 × 3508。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCustomCss](#getCustomCss--) | 获取或设置在打开 EPUB 文档时要应用的自定义 Css。 |
| [getEngineType](#getEngineType--) | 选择 EPUB 转 PDF 的引擎类型，默认是 EngineType.NEW |
| [getMargin](#getMargin--) | 获取表示边距信息的对象引用。 |
| [getMarginsAreaUsageMode](#getMarginsAreaUsageMode--) | 表示边距区域的使用模式——定义对导入文档中与边距使用相关的 CSS 指令（如果有）的处理方式。 |
| [getPageSize](#getPageSize--) | 获取导入的输出页面尺寸。 |
| [getPageSizeAdjustmentMode](#getPageSizeAdjustmentMode--) | 注意！该功能已实现，但由于在 OSHARED 层发现阻塞问题，尚未放入公共 API，适用于示例文档。表示在转换期间使用页面大小的模式。格式（如 HTML、EPUB 等）通常采用浮动设计，因此它允许适配所需的页面大小。但有时内容指定了水平位置或尺寸，导致无法放入所需的页面大小。在这种情况下，我们可以定义应如何处理（即当内容大小不符合结果 PDF 文档的初始页面大小时）。 |
| [setCustomCss](#setCustomCss-java.lang.String-) | 获取或设置在打开 EPUB 文档时要应用的自定义 Css。 |
| [setEngineType](#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-) | 选择 EPUB 转 PDF 的引擎类型，默认是 EngineType.NEW |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | 获取表示边距信息的对象引用。 |
| [setMarginsAreaUsageMode](#setMarginsAreaUsageMode-int-) | 表示边距区域的使用模式——定义对导入文档中与边距使用相关的 CSS 指令（如果有）的处理方式。 |
| [setPageSizeAdjustmentMode](#setPageSizeAdjustmentMode-int-) | 注意！该功能已实现，但由于在 OSHARED 层发现阻塞问题，尚未放入公共 API，适用于示例文档。表示在转换期间使用页面大小的模式。格式（如 HTML、EPUB 等）通常采用浮动设计，因此它允许适配所需的页面大小。但有时内容指定了水平位置或尺寸，导致无法放入所需的页面大小。在这种情况下，我们可以定义应如何处理（即当内容大小不符合结果 PDF 文档的初始页面大小时）。 |

### EpubLoadOptions {#EpubLoadOptions--}
```
public EpubLoadOptions()
```

创建用于将 EPUB 文件转换为 PDF 文档的默认加载选项。默认 PDF 页面尺寸 - A4 300dpi 2480 × 3508。

### EpubLoadOptions {#EpubLoadOptions-java.awt.geom.Dimension2D-}
创建用于将 EPUB 文件转换为 PDF 文档的默认加载选项。默认 PDF 页面尺寸 - A4 300dpi 2480 × 3508。

### getCustomCss {#getCustomCss--}
```
public final String getCustomCss()
```

获取或设置在打开 EPUB 文档时要应用的自定义 Css。

**Returns:**
字符串值

### getEngineType {#getEngineType--}
```
public EpubLoadOptions.EngineType getEngineType()
```

选择 EPUB 转 PDF 的引擎类型，默认是 EngineType.NEW

**Returns:**
EngineType 元素

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

获取表示边距信息的对象引用。

**Returns:**
MarginInfo 对象

### getMarginsAreaUsageMode {#getMarginsAreaUsageMode--}
```
public int getMarginsAreaUsageMode()
```

表示边距区域的使用模式——定义对导入文档中与边距使用相关的 CSS 指令（如果有）的处理方式。

**Returns:**
MarginsAreaUsageModes 值 @see MarginsAreaUsageModes

### getPageSize {#getPageSize--}
```
public Dimension2D getPageSize()
```

获取导入的输出页面尺寸。

**Returns:**
Dimension2D 对象

### getPageSizeAdjustmentMode {#getPageSizeAdjustmentMode--}
```
public int getPageSizeAdjustmentMode()
```

注意！该功能已实现，但由于在 OSHARED 层发现阻塞问题，尚未放入公共 API，适用于示例文档。表示在转换期间使用页面大小的模式。格式（如 HTML、EPUB 等）通常采用浮动设计，因此它允许适配所需的页面大小。但有时内容指定了水平位置或尺寸，导致无法放入所需的页面大小。在这种情况下，我们可以定义应如何处理（即当内容大小不符合结果 PDF 文档的初始页面大小时）。

**Returns:**
PageSizeAdjustmentModes 值 @see PageSizeAdjustmentModes

### setCustomCss {#setCustomCss-java.lang.String-}
获取或设置在打开 EPUB 文档时要应用的自定义 Css。

### setEngineType {#setEngineType-com.aspose.pdf.EpubLoadOptions.EngineType-}
选择 EPUB 转 PDF 的引擎类型，默认是 EngineType.NEW

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
获取表示边距信息的对象引用。

### setMarginsAreaUsageMode {#setMarginsAreaUsageMode-int-}
```
public void setMarginsAreaUsageMode(int marginsAreaUsageMode)
```

表示边距区域的使用模式——定义对导入文档中与边距使用相关的 CSS 指令（如果有）的处理方式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| marginsAreaUsageMode |  | MarginsAreaUsageModes 值 @see MarginsAreaUsageModes |

### setPageSizeAdjustmentMode {#setPageSizeAdjustmentMode-int-}
```
public void setPageSizeAdjustmentMode(int pageSizeAdjustmentMode)
```

注意！该功能已实现，但由于在 OSHARED 层发现阻塞问题，尚未放入公共 API，适用于示例文档。表示在转换期间使用页面大小的模式。格式（如 HTML、EPUB 等）通常采用浮动设计，因此它允许适配所需的页面大小。但有时内容指定了水平位置或尺寸，导致无法放入所需的页面大小。在这种情况下，我们可以定义应如何处理（即当内容大小不符合结果 PDF 文档的初始页面大小时）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageSizeAdjustmentMode |  | PageSizeAdjustmentModes 值 @see PageSizeAdjustmentModes |
