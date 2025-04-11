---
title: Class TxtLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TxtLoadOptions 类。TXT 转 PDF 转换的加载选项
type: docs
weight: 11130
url: /zh/net/aspose.pdf/txtloadoptions/
---
## TxtLoadOptions 类

TXT 转 PDF 转换的加载选项。

```csharp
public class TxtLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TxtLoadOptions](txtloadoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置标志，以禁用加载文件时对所有字体的任何许可证限制。当 `true` 时，允许执行许可证禁止的字体操作，例如允许将字体嵌入 PDF 文档，即使许可证规则禁止该字体的嵌入。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，加载操作将继续，但用户也可以返回中止，在这种情况下，加载操作应停止。 |

## 示例

以下示例演示如何将 TXT 文件转换为 PDF 文件

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your TXT File.
	string txtFile = Path.Combine(dataDir, "TXT-to-PDF.txt");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "TXT-to-PDF.pdf");

	// Initialize TxtLoadOptions	
	TxtLoadOptions txtLoadOptions = new TxtLoadOptions();
		
	using (Document pdfDocument = new Document(txtFile, txtLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]
    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TXT File.
    Dim txtFile = Path.Combine(dataDir, "TXT-to-PDF.txt")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "TXT-to-PDF.pdf")
 
    ' Initialize TxtLoadOptions
    Dim txtLoadOptions As TxtLoadOptions = New TxtLoadOptions()
 
    Using pdfDocument As Document = New Document(txtFile, txtLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 另请参阅

* 类 [LoadOptions](../loadoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)