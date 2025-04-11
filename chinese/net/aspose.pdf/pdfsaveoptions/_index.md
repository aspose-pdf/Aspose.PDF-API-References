---
title: Class PdfSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfSaveOptions 类。导出到 Pdf 格式的保存选项
type: docs
weight: 8430
url: /zh/net/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions class

导出到 Pdf 格式的保存选项

```csharp
public class PdfSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置一个布尔值，指示在准备 aps 页面时是否将字体字形缓存。提高将 pdf 转换为其他格式的性能，但会增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置一个布尔值，指示在文档保存到响应后，Response 对象是否会被关闭。 |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname/) { get; set; } | 默认用于计算机上缺失字体的字体名称。当保存到 PDF 的 PDF 文档包含在文档本身和设备上不可用的字体时，API 会用默认字体替换这些字体（如果在设备上找到的字体与 [`DefaultFontName`](./defaultfontname/) 匹配） |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath/) { get; set; } | 临时文件的路径。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，保存操作将继续，但用户也可以返回中止，在这种情况下，保存操作应停止。 |

## Examples

以下示例演示如何在保存 PDF 时设置默认字体名称

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Load an existing PDF document with missing font
	string documentName = dataDir + "input.pdf";
	string fontName = "Arial";
	using (System.IO.FileStream fs = new System.IO.FileStream(documentName, System.IO.FileMode.Open))
	using (Document document = new Document(fs))
	{
		PdfSaveOptions pdfSaveOptions = new PdfSaveOptions();

		// Specify Default Font Name
		pdfSaveOptions.DefaultFontName = fontName;
		document.Save(dataDir + "output_out.pdf", pdfSaveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' Load an existing PDF document with missing font
    Dim documentName = dataDir & "input.pdf"
    Dim fontName = "Arial"
 
    Using fs As FileStream = New FileStream(documentName, FileMode.Open)
 
        Using document As Document = New Document(fs)
            Dim pdfSaveOptions As PdfSaveOptions = New PdfSaveOptions()

            ' Specify Default Font Name
            pdfSaveOptions.DefaultFontName = fontName
            document.Save(dataDir & "output_out.pdf", pdfSaveOptions)
        End Using
    End Using
```

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)