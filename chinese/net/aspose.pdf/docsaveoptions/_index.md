---
title: Class DocSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptions class. 保存导出到 Doc 格式的选项
type: docs
weight: 3750
url: /zh/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

保存导出到 Doc 格式的选项

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | 使用段落或换行符 |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | 定义批处理大小，如果批处理转换适用于源和目标格式对。 |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置布尔值，指示在准备 aps 页面时是否缓存字体字形。提高将 pdf 转换为其他格式的性能，但增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置布尔值，指示在文档保存到响应后是否关闭 Response 对象。 |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | 获取或设置 Type3 字体的转换。在 Type 3 字体中，字形应由图形操作符的流定义。这意味着在 DOC/DOCX 输出中，我们看到的是图像而不是文本。将此标志设置为 true 以将 Type3 字体转换为 TTF，并在生成的文件中获取文本。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 此属性启用从具有 OCR 子层的 PDF 文档中提取图像或文本的功能。 |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | 输出格式 |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | 转换图像的 X 分辨率。 |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | 转换图像的 Y 分辨率。 |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | 此参数用于将文本行分组为段落。确定两个相对文本行之间的最大距离。以文本行高度的百分之几为单位指定。 |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | 定义在内存保存模式下转换时保存临时数据的路径（文件名或目录名）。 |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | 识别模式。 |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | 开启对项目符号的识别 |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | 在 Pdf 中，单词可能通过独立打印其字母或音节的操作符内部表示。因此，要检测单词，有时我们需要检测实际上是单词的独立字符组。此设置定义在识别源 PDF 中的单词时，文本元素（字母、音节）之间必须视为单词之间距离的宽度（字母之间至少存在此宽度的空白意味着文本元素属于不同的单词）。它以字体大小为标准 - 1.0 意味着假定单词字体大小的 100%。注意！仅在源 PDF 包含特定的、很少使用的字体时使用此参数，因为无法从字体计算出最佳值。因此，在绝大多数情况下，此参数对结果文档没有任何影响。 |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | 获取或设置重新保存字体的过程。如果设置为 true，我们将在每一页上重新加载字体，以避免先前字体属性的影响，并从头加载新创建的字体。如果您想提高性能，请将此选项设置为 false。默认值为 true； |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。 WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，保存操作继续，但用户也可以返回中止，在这种情况下，保存操作应停止。 |

## Fields

| Name | Description |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | 此处理程序可用于处理转换进度事件，例如可以用于显示进度条或关于当前处理页面数量的消息，显示进度的处理程序代码示例是： |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 在多个线程中处理页面。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 有时 PDF 包含由几个相同的平铺背景图像构成的背景图像（页面或表格单元格）。在这种情况下，目标格式的渲染器（例如 DOCS 格式的 MsWord）有时会在背景图像的部分之间生成可见边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来包含这样的可见边界，请尝试使用此设置消除这种不必要的效果。注意！此质量优化通常会显著减慢转换速度，因此，请仅在确实必要时使用此选项。 |

### Examples

以下示例演示如何将 PDF 文件转换为 DOC 或 DOCX 文件

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// The path to output DOC or DOCX File.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Set the recognition mode as Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Set the Horizontal proximity as 2.5
			RelativeHorizontalProximity = 2.5f,
			// Enable the value to recognize bullets during conversion process
			RecognizeBullets = true
		};
		pdfDocument.Save(docFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf")
    
	' The path to output DOC or DOCX File.
    Dim docFile = Path.Combine(dataDir, "PDF-to-DOC.doc")
 
    Using pdfDocument As Document = New Document(pdfFile)
        Dim saveOptions As DocSaveOptions = New DocSaveOptions With {
          .Format = DocSaveOptions.DocFormat.Doc,
            ' Set the recognition mode as Flow
            .Mode = DocSaveOptions.RecognitionMode.Flow,
            ' Set the Horizontal proximity as 2.5
            .RelativeHorizontalProximity = 2.5,
            ' Enable the value to recognize bullets during conversion process
            .RecognizeBullets = True
        }
        pdfDocument.Save(docFile, saveOptions)
    End Using
```

### See Also

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)