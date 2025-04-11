---
title: Class XpsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XpsLoadOptions class. 表示将 xps 文件加载/导入到 pdf 文档中的选项
type: docs
weight: 11510
url: /zh/net/aspose.pdf/xpsloadoptions/
---
## XpsLoadOptions class

表示将 xps 文件加载/导入到 pdf 文档中的选项。

```csharp
public sealed class XpsLoadOptions : LoadOptions, IPipelineOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XpsLoadOptions](xpsloadoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpsloadoptions/batchsize/) { get; set; } | 定义批处理大小，如果批处理转换适用于源和目标格式对。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置标志，以在加载文件时禁用所有字体的许可证限制。当 `true` 时，允许执行被该字体许可证禁止的字体操作，例如，即使许可证规则禁止该字体的嵌入，也允许将字体嵌入到 PDF 文档中。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。 WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，加载操作将继续，但用户也可以返回中止，在这种情况下，加载操作应停止。 |

## Examples

以下示例演示如何将 XPS 文件转换为 PDF 文件

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your XPS File.
	string xpsFile = Path.Combine(dataDir, "XPS-to-PDF.xps");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "XPS-to-PDF.pdf");

	// Initialize XpsLoadOptions	
	XpsLoadOptions xpsLoadOptions = new XpsLoadOptions();
		
	using (Document pdfDocument = new Document(xpsFile, xpsLoadOptions)){
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XPS File.
    Dim xpsFile = Path.Combine(dataDir, "XPS-to-PDF.xps")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XPS-to-PDF.pdf")
 
    ' Initialize XpsLoadOptions
    Dim xpsLoadOptions As XpsLoadOptions = New XpsLoadOptions()
 
    Using pdfDocument As Document = New Document(xpsFile, xpsLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)