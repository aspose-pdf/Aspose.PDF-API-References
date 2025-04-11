---
title: Class XmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmlSaveOptions class. 保存导出到 Xml 格式的选项
type: docs
weight: 11400
url: /zh/net/aspose.pdf/xmlsaveoptions/
---
## XmlSaveOptions class

保存导出到 Xml 格式的选项

```csharp
public class XmlSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XmlSaveOptions](xmlsaveoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置一个布尔值，指示在准备 aps 页面时是否将字体字形缓存。提高将 PDF 转换为其他格式的性能，但会增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置一个布尔值，指示在文档保存到响应后，Response 对象是否会被关闭。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 处理生成的任何警告的回调。WarningHandler 返回 ReturnAction 枚举项，指定继续或中止。继续是默认操作，保存操作将继续，但用户也可以返回中止，在这种情况下，保存操作应停止。 |

## Examples

以下示例演示如何将 PDF 文件转换为 XML 文件

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-XML.pdf");

	// The path to output XML File.
	var xmlFile= Path.Combine(dataDir, "PDF-to-XML.xml");
		
	using (Document pdfDocument = new Document(pdfFile)){
		// Initialize XmlSaveOptions	
		XmlSaveOptions saveOptions = new XmlSaveOptions();
		
		// Save XML file
		pdfDocument.Save(xmlFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-XML.pdf")

    ' The path to output XML File.
    Dim xmlFile = Path.Combine(dataDir, "PDF-to-XML.xml")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize XmlSaveOptions
        Dim saveOptions As XmlSaveOptions = New XmlSaveOptions()
 
        ' Save XML file
        pdfDocument.Save(xmlFile, saveOptions)
    End Using
```

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)