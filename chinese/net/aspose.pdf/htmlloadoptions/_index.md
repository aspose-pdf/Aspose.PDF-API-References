---
title: "类 HtmlLoadOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.HtmlLoadOptions 类。表示将 html 文件加载/导入到 pdf 文档的选项"
type: docs
weight: 5660
url: /zh/net/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions class

表示将 HTML 文件加载/导入到 PDF 文档的选项。

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | 创建用于将 html 转换为 pdf 文档的加载选项，基路径为空。 |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | 创建用于将 html 转换为 pdf 文档的加载选项，基路径已定义。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | HTML 文件的基础路径/URL。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置在加载文件时禁用所有字体的任何许可证限制的标志。当 `true` 时，允许执行该字体许可证禁止的操作，例如即使许可证规则禁止嵌入，也可以将字体嵌入 PDF 文档。默认值为 `false`。 |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | 获取或设置渲染期间使用的可能媒体类型。 |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | 获取或设置指定解析时此文档使用的编码的属性。如果此属性为 null，则编码将从文档字符集属性中确定。 |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | 获取或设置嵌入到结果文档的字体 |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | 获取或设置指定 css 中 @page 规则将覆盖 PageInfo 中定义的值的标志。 |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | 获取或设置将整个文档渲染为单页的选项 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示由 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | 获取或设置文档页面信息 |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | 获取或设置布局选项。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。Continue 为默认操作，加载过程将继续；但用户也可以返回 Abort，此时加载过程应停止。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | 有时需要避免使用内部加载器来加载外部资源（如图像或 CSS），并提供自定义方法以从某处获取请求的资源。例如，在云环境中使用 Aspose.PDF 时，无法直接访问引用的文件：此情况下应使用放入特定方法的自定义代码，并将指向该方法的委托分配给此属性。 |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | 如果加载 HTML 中引用的外部数据需要凭据，您可以将其放入此参数——它们将在加载外部资源时使用。 |

## 示例

以下示例展示了如何将 HTML 文件转换为 PDF 文件

```csharp
[C#]
	// 文档目录的路径。
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// HTML 文件的路径。
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// 输出 PDF 文件的路径。
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// 初始化 HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// 保存 PDF 文件
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

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


