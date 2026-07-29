---
title: "类 TxtLoadOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.TxtLoadOptions 类。TXT 转 PDF 转换的加载选项。"
type: docs
weight: 11320
url: /zh/net/aspose.pdf/txtloadoptions/
---
## TxtLoadOptions class

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
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置在加载文件时禁用所有字体的任何许可证限制的标志。当 `true` 时，允许执行该字体许可证禁止的操作，例如即使许可证规则禁止嵌入，也可以将字体嵌入 PDF 文档。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示由 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。Continue 为默认操作，加载过程将继续；但用户也可以返回 Abort，此时加载过程应停止。 |

## 示例

以下示例展示如何将 TXT 文件转换为 PDF 文件。

```csharp
[C#]
	// 文档目录的路径。
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// 您的 TXT 文件的路径。
	string txtFile = Path.Combine(dataDir, "TXT-to-PDF.txt");

	// 输出 PDF 文件的路径。
	string pdfFile = Path.Combine(dataDir, "TXT-to-PDF.pdf");

	// 初始化 TxtLoadOptions\t
	TxtLoadOptions txtLoadOptions = new TxtLoadOptions();
		
	using (Document pdfDocument = new Document(txtFile, txtLoadOptions))
	{
	 
		// 保存 PDF 文件
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

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


