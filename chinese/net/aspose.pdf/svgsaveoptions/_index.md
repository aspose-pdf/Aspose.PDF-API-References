---
title: "类 SvgSaveOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.SvgSaveOptions 类。导出为 SVG 格式的保存选项。"
type: docs
weight: 10410
url: /zh/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class

导出为 SVG 格式的保存选项。

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置布尔值，以指示在准备 APS 页面时是否缓存字体字形。可提升 PDF 转换为其他格式的性能，但会增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置布尔值，以指示文档保存到响应后是否关闭 Response 对象。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 此属性启用了从带有 OCR 子层的 PDF 文档中提取图像或文本的功能。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue（继续）或 Abort（中止）。Continue 为默认操作，保存操作将继续；但用户也可以返回 Abort，此时保存操作应停止。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | 指定输出是否将创建为一个 zip 压缩包。请参阅 'TreatTargetFileNameAsDirectory' 选项的注释，以了解多页源文档的页面 SVG 文件命名规则，这些规则同样适用于压缩的输出文件集。 |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | 此字段可以包含在转换期间必须使用的保存策略（如果存在），用于对创建的引用外部图像文件（如嵌入的 BMP 或 JPEG）进行自定义处理，这些图像文件会嵌入保存的 SVG 中。该策略必须处理资源并返回表示生成的 SVG 中已保存资源的期望 URI 的字符串。如果出于某种原因必须由转换器的代码本身而不是自定义代码来处理此文件或该文件，请在自定义代码中设置 'CustomProcessingCancelled' 标志于 'imageSavingInfo' 参数的变量。它向转换器指示所有必要的资源处理步骤必须在转换器内部完成，就像没有任何外部自定义代码一样。 |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 在多个线程中处理页面。 |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | 指定是否将输出文档从排版点缩放到像素。 |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | 此选项定义是否在目标输出文件不存在时创建与请求的输出文件同名的目标目录，而不是直接创建输出文件本身。这样，目录将包含所有页面的输出 SVG 图像（如下所述）。如果选择否，则除第一页之外的页面输出文件将直接在请求的目录中创建，文件名会带有 _[2...n] 后缀，由页码决定。例如，如果您将输出文件定义为 "C:\\AsposeTests\\output.svg"，且输出包含多个页面的 SVG 文件，则页面文件也会在目录 "C:\\AsposeTests\\" 中创建，名称分别为 'output.svg'、'output_2.svg'、'output_3.svg' 等。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 有时 PDF 包含由多个相同的平铺背景图像拼接而成的页面或表格单元格的背景图像。在这种情况下，目标格式的渲染器（例如 MsWord 用于 DOCS 格式）有时会在背景图像的各部分之间生成可见的边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来在相同背景图像的各部分之间出现了此类可见边界，请尝试使用此设置以消除该不良效果。注意！此质量优化通常会显著降低转换速度，因此请仅在确实必要时使用此选项。 |

## 示例

以下示例展示了如何将 PDF 文件转换为 SVG 文件

```csharp
[C#]
	// 文档目录的路径。
	string dataDir = "YOUR_DATA_DIRECTORY";

	// PDF 文件的路径。
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// 输出 SVG 文件的路径。
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// 初始化 SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// 保存 SVG 文件
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

### 另请参见

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


