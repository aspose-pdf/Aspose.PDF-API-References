---
title: Class PsSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PsSaveOptions 类。导出到 PS PostScript 或 EPS 格式的保存选项
type: docs
weight: 9740
url: /zh/net/aspose.pdf/pssaveoptions/
---
## PsSaveOptions 类

导出到 PS (PostScript) 或 EPS 格式的保存选项。

```csharp
public class PsSaveOptions : UnifiedSaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PsSaveOptions](pssaveoptions/#constructor)() | 构造函数。 |
| [PsSaveOptions](pssaveoptions/#constructor_1)(SaveFormat) | 构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置一个布尔值，指示在准备 aps 页面时是否将字体字形缓存。提高将 PDF 转换为其他格式的性能，但会增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置一个布尔值，指示在文档保存到响应后，Response 对象是否会被关闭。 |
| [EmbedFont](../../aspose.pdf/pssaveoptions/embedfont/) { get; set; } | 获取/设置一个标志，指示字体是否必须嵌入到生成的 PS 文档中。 |
| [EmbedFontAs](../../aspose.pdf/pssaveoptions/embedfontas/) { get; set; } | 获取/设置字体必须嵌入到生成的 PS 文档中的类型。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 此属性启用从具有 OCR 子层的 PDF 文档中提取图像或文本的功能。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，保存操作继续进行，但用户也可以返回中止，在这种情况下，保存操作应停止。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 在多个线程中处理页面。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 有时 PDF 包含由几个相同的平铺背景图像构成的背景图像（页面或表格单元格）。在这种情况下，目标格式的渲染器（例如 DOCS 格式的 MsWord）有时会在背景图像的部分之间生成可见的边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来包含这样的可见边界，请尝试使用此设置来消除这种不必要的效果。注意！这种质量优化通常会显著减慢转换速度，因此，请仅在确实必要时使用此选项。 |

### 另请参阅

* 类 [UnifiedSaveOptions](../unifiedsaveoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)