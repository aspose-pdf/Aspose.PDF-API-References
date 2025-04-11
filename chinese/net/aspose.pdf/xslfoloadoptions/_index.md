---
title: Class XslFoLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptions class. 表示将 XSLFO 文件加载/导入到 PDF 文档的选项
type: docs
weight: 11530
url: /zh/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class

表示将 XSL-FO 文件加载/导入到 PDF 文档的选项。

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | 创建不带 XSL 数据的 `XslFoLoadOptions` 对象。 |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | 创建带有 XSL 数据的 `XslFoLoadOptions` 对象。 |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | 创建带有 XSL 数据的 `XslFoLoadOptions` 对象。 |

## Properties

| Name | Description |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | 从中搜索相对路径到加载的 SVG 文件中引用的外部资源（如果有）的基本路径/URL。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置标志，以在加载文件时禁用所有字体的许可证限制。当为 `true` 时，允许执行许可证禁止的字体操作，例如允许将字体嵌入 PDF 文档，即使许可证规则禁止该字体的嵌入。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。 WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，加载操作继续，但用户也可以返回中止，在这种情况下，加载操作应停止。 |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | 获取用于将 XML 转换为 PDF 文档的 XSL 数据。 |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | 用于将值插入现有 XLS 参数的 XsltArgumentList。XLS 文件具有没有值的 'animal' 参数：XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); 现在转换器假设 XLS 文件中有一个值为 'cat' 的 'animal' 参数。 |

## Fields

| Name | Description |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | 源 XSLFO 文档可能包含格式错误。此枚举列举了处理这些错误的可能策略。 |

## Examples

以下示例演示如何将 XSL-FO 文件转换为 PDF 文件

```csharp
[C#]
// The path to the documents directory.
string dataDir = @"YOUR_DATA_DIRECTORY";

// The path to your XSL-FO File.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// The path to output PDF File.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Initialize XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Save PDF file
    pdfDocument.Save(pdfFile);
}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XSL-FO File.
    Dim xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf")
 
    ' Initialize XslFoLoadOptions  
    Dim xslFoLoadOptions As XslFoLoadOptions = New XslFoLoadOptions()
 
    Using pdfDocument As Document = New Document(xslFoFile, xslFoLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)