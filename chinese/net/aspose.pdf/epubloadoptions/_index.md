---
title: Class EpubLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubLoadOptions class. 包含将 EPUB 文件加载/导入到 PDF 文档中的选项
type: docs
weight: 4050
url: /zh/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class

包含将 EPUB 文件加载/导入到 PDF 文档中的选项。

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | 创建将 EPUB 文件转换为 PDF 文档的默认加载选项。默认 PDF 页面大小 - A4 300dpi 2480 X 3508。 |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | 创建具有指定页面大小的加载选项。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | 获取或设置打开 Epub 文档时应用的自定义 Css。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置标志以禁用加载文件时对所有字体的任何许可证限制。当 `true` 时，允许执行被该字体许可证禁止的字体操作，例如，即使许可证规则禁止嵌入该字体，也允许将字体嵌入 PDF 文档。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | 获取表示边距信息的对象的引用。 |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | 获取或设置导入的输出页面大小。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，加载操作继续，但用户也可以返回中止，在这种情况下，加载操作应停止。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | 表示边距区域的使用模式 - 定义与导入文档的 CSS 相关的边距使用指令（如果有的话）的处理。 |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | 注意！该功能已实现，但由于在 OSHARED 层发现的阻塞问题尚未公开 API。表示转换过程中页面大小的使用模式。格式（如 HTML、EPUB 等）通常具有浮动设计，因此，它允许适应所需的页面大小。但有时内容具有指定的水平位置或大小，不允许将内容放入所需的页面大小。在这种情况下，我们可以定义在这种情况下应该采取什么措施（即当内容的大小不符合结果 PDF 文档的初始页面大小时）。 |

## 示例

以下示例演示如何将 EPUB 文件转换为 PDF 文件

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your EPUB File.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initialize EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your EPUB File.
    Dim epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf")
 
    ' Initialize EpubLoadOptions    
    Dim epubLoadOptions As EpubLoadOptions = New EpubLoadOptions()
 
    Using pdfDocument As Document = New Document(epubFile, epubLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 另请参阅

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)