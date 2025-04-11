---
title: Class XmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmlLoadOptions class. 表示将 XML 文件加载/导入到 PDF 文档中的选项
type: docs
weight: 11390
url: /zh/net/aspose.pdf/xmlloadoptions/
---
## XmlLoadOptions class

表示将 XML 文件加载/导入到 PDF 文档中的选项。

```csharp
public class XmlLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | 创建不带 xsl 数据的 `XmlLoadOptions` 对象。 |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | 创建带有 xsl 数据的 `XmlLoadOptions` 对象。 |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | 创建带有 xsl 数据的 `XmlLoadOptions` 对象。 |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置标志，以在加载文件时禁用所有字体的许可证限制。当 `true` 时，允许执行许可证禁止的字体操作，例如，即使许可证规则禁用该字体的嵌入，也允许将字体嵌入到 PDF 文档中。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，加载操作将继续，但用户也可以返回中止，在这种情况下，加载操作应停止。 |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | 获取用于将 XML 转换为 PDF 文档的 xsl 数据。 |

## Examples

以下示例演示如何将 XML 文件转换为 PDF 文件

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your XML File.
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// Initialize XmlLoadOptions	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// Save XML file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XML File.
    Dim xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf")
 
    ' Initialize XmlLoadOptions
    Dim xmlLoadOptions As XmlLoadOptions = New XmlLoadOptions()
 
    Using pdfDocument As Document = New Document(xmlFile, xmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)