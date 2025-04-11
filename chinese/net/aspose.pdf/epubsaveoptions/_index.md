---
title: Class EpubSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubSaveOptions class. 保存导出到EPUB格式的选项
type: docs
weight: 4060
url: /zh/net/aspose.pdf/epubsaveoptions/
---
## EpubSaveOptions class

保存导出到EPUB格式的选项

```csharp
public class EpubSaveOptions : UnifiedSaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EpubSaveOptions](epubsaveoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置一个布尔值，指示在准备aps页面时是否将字体字形缓存。提高将PDF转换为其他格式的性能，但会增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置一个布尔值，指示在文档保存到响应后，Response对象是否会被关闭。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 此属性启用从具有OCR子层的PDF文档中提取图像或文本的功能。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [Title](../../aspose.pdf/epubsaveoptions/title/) { get; set; } | 获取或设置EPUB文档标题。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler返回ReturnAction枚举项，指定继续或中止。继续是默认操作，保存操作继续进行，但用户也可以返回中止，在这种情况下，保存操作应停止。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [ContentRecognitionMode](../../aspose.pdf/epubsaveoptions/contentrecognitionmode/) | 当PDF文件（通常具有固定布局）被转换时，转换引擎尝试执行分组和多级分析，以恢复原始文档作者的意图并生成流式布局的结果。此属性调整该转换以适应所需的内容识别方法。 |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 在多个线程中处理页面。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 有时PDF包含由几个相同的平铺背景图像构成的背景图像（页面或表格单元格）。在这种情况下，目标格式的渲染器（例如MsWord用于DOCS格式）有时会在背景图像的部分之间生成可见边界，因为它们的图像边缘平滑（抗锯齿）技术与Acrobat Reader不同。如果导出的文档看起来包含这样的可见边界，请尝试使用此设置消除这种不必要的效果。注意！这种质量优化通常会显著减慢转换速度，因此，请仅在确实必要时使用此选项。 |

## 示例

以下示例演示如何将PDF文件转换为EPUB文件

```csharp
	[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-EPUB.pdf");

	// The path to output EPUB File.
	var epubFile = Path.Combine(dataDir, "PDF-to-EPUB.epub");
		
	using (Document pdfDocument = new Document(pdfFile))
	{

		// Initialize EpubSaveOptions 	
		EpubSaveOptions saveOptions = new EpubSaveOptions();
		
		// Save EPUB file
		pdfDocument.Save(epubFile, saveOptions);
	}
````

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-EPUB.pdf")

    ' The path to output EPUB File.
    Dim epubFile = Path.Combine(dataDir, "PDF-to-EPUB.epub")
 
    Using pdfDocument As Document = New Document(pdfFile)

        ' Initialize EpubSaveOptions    
        Dim saveOptions As EpubSaveOptions = New EpubSaveOptions()
 
        ' Save EPUB file
        pdfDocument.Save(epubFile, saveOptions)
    End Using
```

### 另请参阅

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)