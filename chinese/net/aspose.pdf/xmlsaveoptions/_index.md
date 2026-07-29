---
title: "类 XmlSaveOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.XmlSaveOptions 类。用于导出为 Xml 格式的保存选项"
type: docs
weight: 11590
url: /zh/net/aspose.pdf/xmlsaveoptions/
---
## XmlSaveOptions class

导出为 Xml 格式的保存选项。

```csharp
public class XmlSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XmlSaveOptions](xmlsaveoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 获取或设置布尔值，以指示在准备 APS 页面时是否缓存字体字形。可提升 PDF 转换为其他格式的性能，但会增加内存消耗。 |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 获取或设置布尔值，以指示文档保存到响应后是否关闭 Response 对象。 |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 数据保存的格式。 |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 回调用于处理生成的任何警告。WarningHandler 返回 ReturnAction 枚举项，指定 Continue（继续）或 Abort（中止）。Continue 为默认操作，保存操作将继续；但用户也可以返回 Abort，此时保存操作应停止。 |

## 示例

以下示例展示了如何将 PDF 文件转换为 XML 文件

```csharp
[C#]
	// 文档目录的路径。
	string dataDir = "YOUR_DATA_DIRECTORY";

	// PDF 文件的路径。
	var pdfFile = Path.Combine(dataDir, "PDF-to-XML.pdf");

	// 输出 XML 文件的路径。
	var xmlFile= Path.Combine(dataDir, "PDF-to-XML.xml");
		
	using (Document pdfDocument = new Document(pdfFile)){
		// 初始化 XmlSaveOptions	
		XmlSaveOptions saveOptions = new XmlSaveOptions();
		
		// 保存 XML 文件
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

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


