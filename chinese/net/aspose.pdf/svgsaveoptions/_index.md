---
title: Class SvgSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgSaveOptions 类。导出到 SVG 格式的保存选项
type: docs
weight: 10230
url: /zh/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class

导出到 SVG 格式的保存选项

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置一个布尔值，指示在准备 aps 页面时是否将字体字形缓存。提高将 PDF 转换为其他格式的性能，但会增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置一个布尔值，指示在文档保存到响应后，Response 对象是否会被关闭。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 此属性启用从具有 OCR 子层的 PDF 文档中提取图像或文本的功能。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，保存操作将继续，但用户也可以返回中止，在这种情况下，保存操作应停止。 |

## Fields

| Name | Description |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | 指定输出是否将作为一个 zip-档案创建。请参阅“TreatTargetFileNameAsDirectory”选项的注释，以查看多页源文档的 SVG 文件命名规则，这些规则也适用于压缩的输出文件集。 |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | 此字段可以包含在转换过程中必须使用的保存策略（如果存在），用于自定义处理嵌入到保存的 SVG 中的创建的引用外部图像文件（如嵌入的 BMP 或 JPEG）。该策略必须处理资源并返回表示生成的 SVG 中保存资源的期望 URI 的字符串。如果出于某种原因，必须由转换器的代码本身处理此或那种文件，而不是自定义代码，请在自定义代码中设置“imageSavingInfo”参数变量的标志“CustomProcessingCancelled”。它向转换器发出信号，指示必须在转换器本身中完成处理该资源的所有必要步骤，就好像没有任何外部自定义代码。 |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 在多个线程中处理页面。 |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | 指定是否将输出文档从排版点缩放到像素。 |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | 此选项定义是否将创建与请求的输出文件同名的目标目录（如果尚不存在），而不是请求的输出文件本身。如果是，则该目录将包含所有页面的输出 SVG 图像（如下所述）。如果不是，除第一个页面外的其他页面的输出文件将精确地在请求的目录中创建，作为主输出文件，但文件名将包含后缀 _[2...n]，由页面编号定义，例如，如果您定义输出文件为 "C:\AsposeTests\output.svg"，并且输出将包含多个页面的 svg 文件，则页面的文件也将在目录 "C:\AsposeTests\" 中创建，并具有名称 'output.svg'，'output_2.svg'，'output_3.svg' 等等。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 有时 PDF 包含由几个相同的平铺背景图像构成的背景图像（页面或表格单元格）。在这种情况下，目标格式的渲染器（例如 MsWord 的 DOCS 格式）有时会在背景图像的部分之间生成可见的边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来包含相同背景图像部分之间的可见边界，请尝试使用此设置来消除这种不必要的效果。注意！此质量优化通常会显著减慢转换速度，因此，请仅在确实必要时使用此选项。 |

## Examples

以下示例演示如何将 PDF 文件转换为 SVG 文件

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// The path to output SVG File.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Save SVG file
		pdfDocument.Save(svgFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf")

    ' The path to output SVG File.
    Dim svgFile = Path.Combine(dataDir, "PDF-to-SVG.svg")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize SvgSaveOptions
        Dim saveOptions As SvgSaveOptions = New SvgSaveOptions()
 
        ' Save SVG file
        pdfDocument.Save(svgFile, saveOptions)
    End Using
```

### See Also

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)