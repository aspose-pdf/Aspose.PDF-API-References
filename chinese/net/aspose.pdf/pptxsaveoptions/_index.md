---
title: "类 PptxSaveOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.PptxSaveOptions 类。导出为 SVG 格式的保存选项"
type: docs
weight: 9630
url: /zh/net/aspose.pdf/pptxsaveoptions/
---
## PptxSaveOptions class

导出为 SVG 格式的保存选项。

```csharp
public class PptxSaveOptions : UnifiedSaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PptxSaveOptions](pptxsaveoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置布尔值，以指示在准备 APS 页面时是否缓存字体字形。可提升 PDF 转换为其他格式的性能，但会增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置布尔值，以指示文档保存到响应后是否关闭 Response 对象。 |
| [CustomProgressHandler](../../aspose.pdf/pptxsaveoptions/customprogresshandler/) { get; set; } | 此处理程序可用于处理转换进度事件，例如可用于显示进度条或当前已处理页面数量的消息，以下是显示控制台进度的处理程序代码示例： |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 此属性启用了从带有 OCR 子层的 PDF 文档中提取图像或文本的功能。 |
| [ImageResolution](../../aspose.pdf/pptxsaveoptions/imageresolution/) { get; set; } | 获取或设置图像分辨率（dpi）。默认值为 192 dpi。 |
| [OptimizeTextBoxes](../../aspose.pdf/pptxsaveoptions/optimizetextboxes/) { get; set; } | 切换文本列识别 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [SeparateImages](../../aspose.pdf/pptxsaveoptions/separateimages/) { get; set; } | 如果设置为 true，则图像会从所有其他图形中分离出来 |
| [SlidesAsImages](../../aspose.pdf/pptxsaveoptions/slidesasimages/) { get; set; } | 如果设置为 true，则所有内容都被识别为图像（每页一个） |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue（继续）或 Abort（中止）。Continue 为默认操作，保存操作将继续；但用户也可以返回 Abort，此时保存操作应停止。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 在多个线程中处理页面。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 有时 PDF 包含由多个相同的平铺背景图像拼接而成的页面或表格单元格的背景图像。在这种情况下，目标格式的渲染器（例如 MsWord 用于 DOCS 格式）有时会在背景图像的各部分之间生成可见的边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来在相同背景图像的各部分之间出现了此类可见边界，请尝试使用此设置以消除该不良效果。注意！此质量优化通常会显著降低转换速度，因此请仅在确实必要时使用此选项。 |

## 示例

以下示例展示了如何将 PDF 文件转换为 PPT 或 PPTX 文件

```csharp
[C#]
	// 文档目录的路径。
	string dataDir = "YOUR_DATA_DIRECTORY";

	// PDF 文件的路径。
	var pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf");

	// 您的 PPT 或 PPTX 文件的路径。
	var pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// 初始化 PptxSaveOptions\t
		PptxSaveOptions saveOptions = new PptxSaveOptions();
		
		// 保存 PPT 或 PPTX 文件
		pdfDocument.Save(pptxFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf")
    ' The path to your PPT or PPTX File.
    Dim pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize PptxSaveOptions    
        Dim saveOptions As PptxSaveOptions = New PptxSaveOptions()
 
        ' Save PPT or PPTX file
        pdfDocument.Save(pptxFile, saveOptions)
    End Using
```

### 另请参见

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


