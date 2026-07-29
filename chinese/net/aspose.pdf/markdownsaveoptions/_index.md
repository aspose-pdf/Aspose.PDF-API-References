---
title: "类 MarkdownSaveOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.MarkdownSaveOptions 类。表示 Document 保存选项类（markdown 格式）。"
type: docs
weight: 7050
url: /zh/net/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions class

表示 markdown 格式的文档保存选项类。

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | 获取或设置一个矩形区域，以将内容提取为 markdown。 |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置布尔值，以指示在准备 APS 页面时是否缓存字体字形。可提升 PDF 转换为其他格式的性能，但会增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置布尔值，以指示文档保存到响应后是否关闭 Response 对象。 |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | 获取或设置生成文档的强调样式。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 此属性启用了从带有 OCR 子层的 PDF 文档中提取图像或文本的功能。 |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | 获取和设置一个属性，指示是否应提取矢量图形。 |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | 定义在 FontSize 识别标题策略中使用的预期标题级别。如果设置了此属性值，则即使文档包含书签，也会在设置 !:PdfToMarkdown.HeadingRecognitionStrategy.Auto 策略时选择标题识别启发式策略。 |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | 获取或设置标题识别策略。 |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | 获取或设置生成文档的标题样式。 |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | 获取或设置生成文档的换行样式。 |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | 获取和设置用于保存文档资源（如图像）的目录名称。如果未指定该值，则图像将写入与 markdown 文件本身相同的目录。这不是路径，仅是名称！该目录将在保存 markdown 文件的目录中自动创建。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | 获取并设置是否允许转换下标和上标。默认情况下此值为 true。 |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | 获取和设置是否允许使用 img 标签在文本左侧或右侧插入图像。在这种情况下，markdown 查看器中，文本将环绕图像换行。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue（继续）或 Abort（中止）。Continue 为默认操作，保存操作将继续；但用户也可以返回 Abort，此时保存操作应停止。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 在多个线程中处理页面。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 有时 PDF 包含由多个相同的平铺背景图像拼接而成的页面或表格单元格的背景图像。在这种情况下，目标格式的渲染器（例如 MsWord 用于 DOCS 格式）有时会在背景图像的各部分之间生成可见的边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来在相同背景图像的各部分之间出现了此类可见边界，请尝试使用此设置以消除该不良效果。注意！此质量优化通常会显著降低转换速度，因此请仅在确实必要时使用此选项。 |

### 另请参见

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


