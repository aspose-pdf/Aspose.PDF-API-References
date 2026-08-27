---
title: "类 EpubLoadOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.EpubLoadOptions 类。包含将 EPUB 文件加载/导入到 PDF 文档的选项。"
type: docs
weight: 4170
url: /zh/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class

包含将 EPUB 文件加载/导入到 pdf 文档的选项。

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | 创建用于将 EPUB 文件转换为 PDF 文档的默认加载选项。默认 PDF 页面尺寸为 A4，300dpi，2480 × 3508。 |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | 使用指定页面尺寸创建加载选项。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | 获取或设置打开 Epub 文档时要应用的自定义 Css。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置在加载文件时禁用所有字体的任何许可证限制的标志。当 `true` 时，允许执行该字体许可证禁止的操作，例如即使许可证规则禁止嵌入，也可以将字体嵌入 PDF 文档。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示由 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | 获取表示边距信息的对象引用。 |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | 获取或设置导入的输出页面尺寸。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。Continue 为默认操作，加载过程将继续；但用户也可以返回 Abort，此时加载过程应停止。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | 表示页边距区域的使用模式——定义导入文档的 CSS 中（如果有）与页边距使用相关的指令的处理方式。 |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | 注意！该功能已实现，但由于在 OSHARED 层出现的阻塞问题尚未向公共 API 发布。表示转换过程中页面尺寸的使用模式。诸如 HTML、EPUB 等格式通常采用浮动布局，因此可以适配所需的页面尺寸。但有时内容具有指定的水平位置或尺寸，导致无法放入所需的页面尺寸。在这种情况下可以定义应如何处理（即当内容尺寸不符合结果 PDF 文档的初始页面尺寸时）。 |

## 示例

以下示例展示了如何将 EPUB 文件转换为 PDF 文件。

```csharp
[C#]
	// 文档目录的路径。
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// 您的 EPUB 文件的路径。
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// 输出 PDF 文件的路径。
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// 初始化 EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// 保存 PDF 文件
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

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


