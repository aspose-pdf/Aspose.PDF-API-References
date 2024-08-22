---
title: Class XmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmlSaveOptions class. Save options for export to Xml format
type: docs
weight: 8510
url: /net/aspose.pdf/xmlsaveoptions/
---
## XmlSaveOptions class

Save options for export to Xml format

```csharp
public class XmlSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XmlSaveOptions](xmlsaveoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format of data save. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |

## Examples

The following example shows how to convert PDF file to XML file

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


