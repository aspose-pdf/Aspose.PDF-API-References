---
title: "类 XslFoLoadOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.XslFoLoadOptions 类。表示加载/导入 XSLFO 文件到 pdf 文档的选项。"
type: docs
weight: 11720
url: /zh/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class

表示加载/导入 XSL-FO 文件到 pdf 文档的选项。

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | 创建不含 xsl 数据的 `XslFoLoadOptions` 对象。 |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | 创建包含 xsl 数据的 `XslFoLoadOptions` 对象。 |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | 创建包含 xsl 数据的 `XslFoLoadOptions` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | 基路径/URL，用于搜索加载的 SVG 文件中引用的外部资源（如果有）的相对路径。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置在加载文件时禁用所有字体的任何许可证限制的标志。当 `true` 时，允许执行该字体许可证禁止的操作，例如即使许可证规则禁止嵌入，也可以将字体嵌入 PDF 文档。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示由 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。Continue 为默认操作，加载过程将继续；但用户也可以返回 Abort，此时加载过程应停止。 |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | 获取用于将 XML 转换为 PDF 文档的 XSL 数据。 |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList 用于向现有的 xls 参数插入值。XLS 文件有一个没有值的 'animal' 参数：XsltArgumentList args = new XsltArgumentList(); args.AddParam(\"animal\", \"\", \"cat\"); 现在转换器假设 XLS 文件中存在值为 'cat' 的 'animal' 参数。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | 源 XSLFO 文档可能包含格式错误。此枚举列举了处理这些错误的可能策略。 |

## 示例

以下示例展示了如何将 XSL-FO 文件转换为 PDF 文件。

```csharp
[C#]
// 文档目录的路径。
string dataDir = @"YOUR_DATA_DIRECTORY";

// XSL-FO 文件的路径。
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// 输出 PDF 文件的路径。
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// 初始化 XslFoLoadOptions
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // 保存 PDF 文件
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

### 另请参见

* class [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


