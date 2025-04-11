---
title: Class MhtLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.MhtLoadOptions 类。表示将 .mht 文件加载/导入到 PDF 文档的选项
type: docs
weight: 6970
url: /zh/net/aspose.pdf/mhtloadoptions/
---
## MhtLoadOptions 类

表示将 .mht 文件加载/导入到 PDF 文档的选项。

```csharp
public sealed class MhtLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MhtLoadOptions](mhtloadoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置标志，以禁用加载文件时对所有字体的任何许可证限制。当 `true` 时，允许执行许可证禁止的字体操作，例如允许将字体嵌入 PDF 文档，即使许可证规则禁止该字体的嵌入。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [PageInfo](../../aspose.pdf/mhtloadoptions/pageinfo/) { get; } | 获取或设置文档页面信息 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，加载操作继续进行，但用户也可以返回中止，在这种情况下，加载操作应停止。 |

## 示例

以下示例演示如何将 MHT 文件转换为 PDF 文件

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your MHT File.
	string mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf");

	// Initialize MhtLoadOptions	
	MhtLoadOptions mhtLoadOptions = new MhtLoadOptions();
		
	using (Document pdfDocument = new Document(mhtFile, mhtLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your MHT File.
    Dim mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf")
 
    ' Initialize MhtLoadOptions
    Dim mhtLoadOptions As MhtLoadOptions = New MhtLoadOptions()
 
    Using pdfDocument As Document = New Document(mhtFile, mhtLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```
	
### 另请参见

* 类 [LoadOptions](../loadoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)