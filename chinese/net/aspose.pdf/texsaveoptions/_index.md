---
title: "类 TeXSaveOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.TeXSaveOptions 类。导出为 TeX 格式的保存选项。"
type: docs
weight: 10580
url: /zh/net/aspose.pdf/texsaveoptions/
---
## TeXSaveOptions class

导出为 TeX 格式的保存选项。

```csharp
public class TeXSaveOptions : UnifiedSaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TeXSaveOptions](texsaveoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置布尔值，以指示在准备 APS 页面时是否缓存字体字形。可提升 PDF 转换为其他格式的性能，但会增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置布尔值，以指示文档保存到响应后是否关闭 Response 对象。 |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | 此属性启用了从带有 OCR 子层的 PDF 文档中提取图像或文本的功能。 |
| [OutDirectoryPath](../../aspose.pdf/texsaveoptions/outdirectorypath/) { get; set; } | 用于 _outDirectoryPath 参数的属性。 |
| [PagesCount](../../aspose.pdf/texsaveoptions/pagescount/) { get; } | 返回转换后的页数。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue（继续）或 Abort（中止）。Continue 为默认操作，保存操作将继续；但用户也可以返回 Abort，此时保存操作应停止。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddFontEncs](../../aspose.pdf/texsaveoptions/addfontencs/)(params string[]) | 向字体编码列表添加字体编码。 |
| [ClearFontEncs](../../aspose.pdf/texsaveoptions/clearfontencs/)() | 清除字体编码列表。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | 在多个线程中处理页面。 |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | 有时 PDF 包含由多个相同的平铺背景图像拼接而成的页面或表格单元格的背景图像。在这种情况下，目标格式的渲染器（例如 MsWord 用于 DOCS 格式）有时会在背景图像的各部分之间生成可见的边界，因为它们的图像边缘平滑（抗锯齿）技术与 Acrobat Reader 不同。如果导出的文档看起来在相同背景图像的各部分之间出现了此类可见边界，请尝试使用此设置以消除该不良效果。注意！此质量优化通常会显著降低转换速度，因此请仅在确实必要时使用此选项。 |

## 示例

以下示例展示了如何将 PDF 文件转换为 TeX 文件。

```csharp
[C#]
	// 文档目录的路径。
	string dataDir = "YOUR_DATA_DIRECTORY";

	// PDF 文件的路径。
	var pdfFile = Path.Combine(dataDir, "PDF-to-TeX.pdf");

	// 输出 TeX 文件的路径。
	var texFile= Path.Combine(dataDir, "PDF-to-TeX.tex");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// 初始化 TeXSaveOptions	
		TeXSaveOptions saveOptions = new TeXSaveOptions();
		
		// 保存 TeX 文件。
		pdfDocument.Save(texFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-TeX.pdf")

    ' The path to output TeX File.
    Dim texFile = Path.Combine(dataDir, "PDF-to-TeX.tex")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize TeXSaveOptions
        Dim saveOptions As TeXSaveOptions = New TeXSaveOptions()
 
        ' Save TeX file
        pdfDocument.Save(texFile, saveOptions)
    End Using
```

### 另请参见

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


