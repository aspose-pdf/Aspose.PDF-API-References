---
title: "类 DocSaveOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.DocSaveOptions 类。用于导出为 Doc 格式的保存选项"
type: docs
weight: 3870
url: /zh/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

导出为 Doc 格式的保存选项

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | 使用段落或换行符 |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | 如果批量转换适用于源和目标格式对，则定义批处理大小。 |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置布尔值，以指示在准备 APS 页面时是否缓存字体字形。可提升 PDF 转换为其他格式的性能，但会增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置布尔值，以指示文档保存到响应后是否关闭 Response 对象。 |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | 获取或设置 Type3 字体的转换方式。在 Type3 字体中，字形应由图形操作符流定义。这意味着在 DOC/DOCX 输出中我们会看到图像而不是文本。将此标志设为 true 可将 Type3 字体转换为 TTF，并在生成的文件中获得文本。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 此属性启用了从带有 OCR 子层的 PDF 文档中提取图像或文本的功能。 |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | 输出格式 |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | 转换后图像的 X 分辨率。 |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | 转换后图像的 Y 分辨率。 |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | 此参数用于将文本行分组为段落。确定两行相对文本行之间可以相隔多远。以文本行高度的百分之百为单位指定。 |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | 定义在内存保存模式下转换时用于保存临时数据的路径（文件名或目录名）。 |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | 识别模式。 |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | 开启项目符号的识别 |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | 在 PDF 中，单词可能通过独立打印其字母或音节的操作符内部表示。因此，要检测单词时，有时需要识别实际上构成单词的独立字符组。此设置定义文本元素（字母、音节）之间的空白宽度，在源 PDF 的单词识别过程中将其视为单词之间的距离。（如果字母之间的空白至少达到此宽度，则表示这些文本元素属于不同的单词）。该值以字体大小为基准进行归一化——1.0 表示相当于预期单词字体大小的 100%。注意！仅在源 PDF 包含特定少用字体且无法从字体本身计算出最佳值的情况下使用。因此，在绝大多数情况下，此参数对结果文档没有任何影响。 |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | 获取或设置重新保存字体的过程。如果设为 true，我们将在每页重新加载字体，以避免先前字体属性的影响，并从头加载新创建的字体。如果想提升性能，请将此选项设为 false。默认值为 true； |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue（继续）或 Abort（中止）。Continue 为默认操作，保存操作将继续；但用户也可以返回 Abort，此时保存操作应停止。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | 此处理程序可用于处理转换进度事件，例如可用于显示进度条或当前已处理页面数量的消息，以下是显示控制台进度的处理程序代码示例： |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 在多个线程中处理页面。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 有时 PDF 包含由多个相同的平铺背景图像拼接而成的页面或表格单元格的背景图像。在这种情况下，目标格式的渲染器（例如 MsWord 用于 DOCS 格式）有时会在背景图像的各部分之间生成可见的边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来在相同背景图像的各部分之间出现了此类可见边界，请尝试使用此设置以消除该不良效果。注意！此质量优化通常会显著降低转换速度，因此请仅在确实必要时使用此选项。 |

### 示例

以下示例展示了如何将 PDF 文件转换为 DOC 或 DOCX 文件

```csharp
[C#]
	// 文档目录的路径。
	string dataDir = "YOUR_DATA_DIRECTORY";

	// PDF 文件的路径。
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// 输出 DOC 或 DOCX 文件的路径。
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// 将识别模式设置为 Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// 将水平接近度设置为 2.5
			RelativeHorizontalProximity = 2.5f,
			// 启用在转换过程中识别项目符号的功能
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

### 另请参见

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


