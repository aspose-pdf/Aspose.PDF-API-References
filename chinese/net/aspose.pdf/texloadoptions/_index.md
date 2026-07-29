---
title: "TeXLoadOptions 类"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.TeXLoadOptions 类。表示加载/导入 TeX 文件到 PDF 文档的选项"
type: docs
weight: 10550
url: /zh/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class

表示将 TeX 文件加载/导入到 PDF 文档的选项。

```csharp
public class TeXLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | 获取/设置日期/时间原语（如年份、月份、日期和时间）的特定值。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 获取或设置在加载文件时禁用所有字体的任何许可证限制的标志。当 `true` 时，允许执行该字体许可证禁止的操作，例如即使许可证规则禁止嵌入，也可以将字体嵌入 PDF 文档。默认值为 `false`。 |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | 获取/设置 TeX 输入目录。 |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | 获取/设置作业的名称。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | 表示由 [`LoadOptions`](../loadoptions/) 描述的文件格式。 |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | 获取/设置一个标志，以取消所有字体中的连字。 |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | 获取/设置 TeX 输出目录。 |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | 获取/设置一个标志，以允许光栅化数学公式。 |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | 获取/设置标志，指示是否需要在某些情况下（例如输入 TeX 文件中有引用）运行 TeX 作业两次。一般来说，当引擎在排版过程中收集一些数据并在第一次运行时将其存储在辅助文件中时，此行为很有用。第二次运行时，引擎会以某种方式使用这些数据。 |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | 获取/设置 TeX 所需的输入目录。所需的输入是以某种方式包含在主 .tex 文件中的文件，例如没有内置支持的包。 |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | 获取/设置标志，指示是否在控制台上显示终端输出。 |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | 获取/设置标志，指示是否在输出文件中子集化字体。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue 或 Abort。Continue 为默认操作，加载过程将继续；但用户也可以返回 Abort，此时加载过程应停止。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | 获取 TeX 加载和编译的结果——一切是否顺利完成，或是否有任何注释/错误。 |

## 示例

以下示例展示如何将 TeX 文件转换为 PDF 文件

```csharp
[C#]
	// 文档目录的路径。
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// TeX 文件的路径。
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// 输出 PDF 文件的路径。
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// 初始化 TeXLoadOptions
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// 保存 PDF 文件
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

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


