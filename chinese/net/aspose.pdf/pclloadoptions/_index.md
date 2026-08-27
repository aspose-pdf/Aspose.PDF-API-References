---
title: "类 PclLoadOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.PclLoadOptions 类。表示将 PCL 文件加载导入到 pdf 文档的选项"
type: docs
weight: 8440
url: /zh/net/aspose.pdf/pclloadoptions/
---
## PclLoadOptions class

表示将 PCL 文件加载（导入）到 PDF 文档的选项。

```csharp
public sealed class PclLoadOptions : LoadOptions, IPipelineOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PclLoadOptions](pclloadoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BatchSize](../../aspose.pdf/pclloadoptions/batchsize/) { get; set; } | 如果批量转换适用于源和目标格式对，则定义批处理大小。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置在加载文件时禁用所有字体的任何许可证限制的标志。当 `true` 时，允许执行该字体许可证禁止的操作，例如即使许可证规则禁止嵌入，也可以将字体嵌入 PDF 文档。默认值为 `false`。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示由 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。Continue 为默认操作，加载过程将继续；但用户也可以返回 Abort，此时加载过程应停止。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/pclloadoptions/conversionengine/) | 定义将用于转换的转换引擎 |
| [Exceptions](../../aspose.pdf/pclloadoptions/exceptions/) | 转换错误列表。 |
| [SupressErrors](../../aspose.pdf/pclloadoptions/supresserrors/) | 获取或设置布尔值，指示是否应抑制 PCL 转换错误。 |

## 示例

以下示例展示了如何将 PCL 文件转换为 PDF 文件

```csharp
[C#]
	// 文档目录的路径。
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// 您的 PCL 文件的路径。
	string pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl");

	// 输出 PDF 文件的路径。
	string pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf");

	// 初始化 PclLoadOptions	
	PclLoadOptions pclLoadOptions = new PclLoadOptions();
		
	using (Document pdfDocument = new Document(pclFile, pclLoadOptions))
	{
	 
		// 保存 PDF 文件
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PCL File.
    Dim pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf")
 
    ' Initialize PclLoadOptions
    Dim pclLoadOptions As PclLoadOptions = New PclLoadOptions()
 
    Using pdfDocument As Document = New Document(pclFile, pclLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 另请参见

* class [LoadOptions](../loadoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


