---
title: "类 XmlLoadOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.XmlLoadOptions 类。表示将 XML 文件加载/导入到 PDF 文档的选项。"
type: docs
weight: 11580
url: /zh/net/aspose.pdf/xmlloadoptions/
---
## XmlLoadOptions class

表示加载/导入 XML 文件到 pdf 文档的选项。

```csharp
public class XmlLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | 创建不带 XSL 数据的 `XmlLoadOptions` 对象。 |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | 创建带有 XSL 数据的 `XmlLoadOptions` 对象。 |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | 创建带有 XSL 数据的 `XmlLoadOptions` 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置在加载文件时禁用所有字体的任何许可证限制的标志。当 `true` 时，允许执行该字体许可证禁止的操作，例如即使许可证规则禁止嵌入，也可以将字体嵌入 PDF 文档。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示由 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。Continue 为默认操作，加载过程将继续；但用户也可以返回 Abort，此时加载过程应停止。 |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | 获取用于将 XML 转换为 PDF 文档的 XSL 数据。 |

## 示例

以下示例展示了如何将 XML 文件转换为 PDF 文件

```csharp
[C#]
	// 文档目录的路径。
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// XML 文件的路径。
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// 输出 PDF 文件的路径。
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// 初始化 XmlLoadOptions	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// 保存 XML 文件
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

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


