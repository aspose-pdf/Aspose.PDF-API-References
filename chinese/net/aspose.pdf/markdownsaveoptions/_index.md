---
title: Class MarkdownSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.MarkdownSaveOptions 类。表示以 markdown 格式保存文档的选项类
type: docs
weight: 6910
url: /zh/net/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions class

表示以 markdown 格式保存文档的选项类。

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | 获取或设置要提取内容到 markdown 的矩形区域。 |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置一个布尔值，指示在准备 aps 页面时是否缓存字体字形。提高将 pdf 转换为其他格式的性能，但会增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置一个布尔值，指示在文档保存到响应后，Response 对象是否会被关闭。 |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | 获取或设置生成文档的强调样式。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 此属性启用从具有 OCR 子层的 PDF 文档中提取图像或文本的功能。 |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | 获取和设置一个属性，指示是否应提取矢量图形。 |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | 定义在字体大小识别标题策略中使用的预期标题级别。如果设置了此属性值，则在设置 !:PdfToMarkdown.HeadingRecognitionStrategy.Auto 策略时，即使文档包含书签，也将选择标题识别 !:PdfToMarkdown.HeadingRecognitionStrategy.Heuristic 策略。 |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | 获取或设置标题识别策略。 |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | 获取或设置生成文档的标题样式。 |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | 获取或设置生成文档的换行样式。 |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | 获取和设置保存文档资源（如图像）的目录名称。如果未指定该值，则图像将写入与 markdown 文件本身相同的目录。这不是路径，仅是名称！此目录将在保存的 markdown 文件所在的目录中自动创建。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | 获取和设置允许转换下标和上标。默认情况下该值为 true。 |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | 获取和设置使用 img 标签将图像插入文本左右的允许。在这种情况下，在 markdown 查看器中，文本将围绕图像换行。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，保存操作将继续，但用户也可以返回中止，在这种情况下，保存操作应停止。 |

## Fields

| Name | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 在多个线程中处理页面。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 有时 PDF 包含由几个相同的平铺背景图像构成的背景图像（页面或表格单元格）。在这种情况下，目标格式的渲染器（例如 MsWord 用于 DOCS 格式）有时会在背景图像的部分之间生成可见边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来包含这样的可见边界，请尝试使用此设置消除这种不必要的效果。注意！这种质量优化通常会显著减慢转换速度，因此，请仅在确实必要时使用此选项。 |

### See Also

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)