---
title: Class HtmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlLoadOptions class. 表示将 HTML 文件加载/导入到 PDF 文档的选项
type: docs
weight: 5530
url: /zh/net/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions class

表示将 HTML 文件加载/导入到 PDF 文档的选项。

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | 创建用于将 HTML 转换为 PDF 文档的加载选项，基础路径为空。 |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | 创建用于将 HTML 转换为 PDF 文档的加载选项，基础路径已定义。 |

## Properties

| Name | Description |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | HTML 文件的基础路径/URL。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置标志，以禁用加载文件时对所有字体的许可证限制。当 `true` 时，允许执行许可证禁止的字体操作，例如允许将字体嵌入 PDF 文档，即使许可证规则禁止该字体的嵌入。默认值为 `false`。 |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | 获取或设置在渲染过程中使用的可能媒体类型。 |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | 获取或设置指定解析时用于该文档的编码的属性。如果该属性为 null，则编码将根据文档字符集属性确定。 |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | 获取或设置结果文档的字体嵌入 |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | 获取或设置标志，指定 CSS 中定义的 @page 规则将覆盖 PageInfo 中定义的值。 |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | 获取或设置将所有文档渲染为单页 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | 获取或设置文档页面信息 |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | 获取或设置布局选项。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，加载操作继续，但用户也可以返回中止，在这种情况下，加载操作应停止。 |

## Fields

| Name | Description |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | 有时需要避免使用内部加载器加载外部资源（如图像或 CSS），并提供自定义方法从某处获取请求的资源。例如，在云中使用 Aspose.PDF 时，无法直接访问引用的文件：在这种情况下，应该使用放入特殊方法中的一些自定义代码，并将引用该方法的委托分配给此属性。 |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | 如果加载 HTML 中引用的外部数据需要凭据，您可以将其放入此参数中 - 它们将在加载外部资源时使用 |

## Examples

以下示例演示如何将 HTML 文件转换为 PDF 文件

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your HTML File.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Initialize HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your HTML File.
    Dim htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf")
 
    ' Initialize HtmlLoadOptions    
    Dim htmlLoadOptions As HtmlLoadOptions = New HtmlLoadOptions()
 
    Using pdfDocument As Document = New Document(htmlFile, htmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)