---
title: Class ApsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ApsLoadOptions class. 类描述 aps 加载选项
type: docs
weight: 2750
url: /zh/net/aspose.pdf/apsloadoptions/
---
## ApsLoadOptions class

类描述 aps 加载选项。

```csharp
public class ApsLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ApsLoadOptions](apsloadoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置标志，以禁用加载文件时对所有字体的任何许可证限制。当 `true` 时，允许执行许可证禁止的字体操作，例如允许将字体嵌入 PDF 文档，即使许可证规则禁止该字体的嵌入。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。 WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，加载操作将继续，但用户也可以返回中止，在这种情况下，加载操作应停止。 |

## Examples

以下示例演示如何将 APS 文件转换为 PDF 文件

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your APS File.
	string apsFile = Path.Combine(dataDir, "APS-to-PDF.aps");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf");

	// Initialize ApsLoadOptions  	
	ApsLoadOptions apsLoadOptions = new ApsLoadOptions();

	// Initialize Document wiht ApsLoadOptions     
	using (Document pdfDocument = new Document(apsFile, apsLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your APS File.
    Dim apsFile = Path.Combine(dataDir, "APS-to-PDF.aps")
	
    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "APS-to-PDF.pdf")
 
    ' Initialize ApsLoadOptions    
    Dim apsLoadOptions As ApsLoadOptions = New ApsLoadOptions()
 
	' Initialize Document wiht ApsLoadOptions
    Using pdfDocument As Document = New Document(apsFile, apsLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)