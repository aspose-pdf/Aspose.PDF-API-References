---
title: Class TeXLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TeXLoadOptions class. 表示将 TeX 文件加载/导入到 PDF 文档的选项
type: docs
weight: 10370
url: /zh/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class

表示将 TeX 文件加载/导入到 PDF 文档的选项。

```csharp
public class TeXLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | 获取/设置日期/时间原语的某个值，如年、月、日和时间。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置标志以禁用加载文件时对所有字体的任何许可证限制。当 `true` 时，允许执行许可证禁止的字体操作，例如允许将字体嵌入 PDF 文档，即使许可证规则禁止该字体的嵌入。默认值为 `false`。 |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | 获取/设置 TeX 输入目录。 |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | 获取/设置作业名称。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | 获取/设置一个标志，取消所有字体中的连字。 |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | 获取/设置 TeX 输出目录。 |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | 获取/设置一个标志，允许栅格化数学公式。 |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | 获取/设置标志，指示是否需要在输入 TeX 文件中存在引用的情况下运行 TeX 作业两次。一般来说，当引擎在排版过程中收集一些数据并将其存储在辅助文件中时，这种行为是有用的，所有这些都在第一次运行时完成。在第二次运行时，引擎以某种方式使用这些数据。 |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | 获取/设置 TeX 所需的输入目录。所需输入是以某种方式包含在主 .tex 文件中的文件，例如，没有内置支持的包。 |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | 获取/设置标志，指示是否在控制台上显示终端输出。 |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | 获取/设置标志，指示是否在输出文件中子集化字体。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，加载操作继续，但用户也可以返回中止，在这种情况下，加载操作应停止。 |

## Methods

| Name | Description |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | 获取 TeX 加载和编译的结果 - 一切是否顺利，或者是否有任何评论/错误。 |

## Examples

以下示例演示如何将 TeX 文件转换为 PDF 文件

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your TeX File.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Initialize TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TeX File.
    Dim texFile = Path.Combine(dataDir, "TeX-to-PDF.tex")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf")
 
    ' Initialize TeXLoadOptions
    Dim texLoadOptions As TeXLoadOptions = New TeXLoadOptions()
 
    Using pdfDocument As Document = New Document(texFile, texLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)