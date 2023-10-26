---
title: Class XmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmlLoadOptions class. Represents options for loading/importing XML file into pdf document
type: docs
weight: 8390
url: /net/aspose.pdf/xmlloadoptions/
---
## XmlLoadOptions class

Represents options for loading/importing XML file into pdf document.

```csharp
public class XmlLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions/#constructor)() | Creates `XmlLoadOptions` object without xsl data. |
| [XmlLoadOptions](xmlloadoptions/#constructor_1)(Stream) | Creates `XmlLoadOptions` object with xsl data. |
| [XmlLoadOptions](xmlloadoptions/#constructor_2)(string) | Creates `XmlLoadOptions` object with xsl data. |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When `true`, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../loadoptions/) describes. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Gets xsl data for converting xml into pdf document. |

## Examples

The following example shows how to convert XML file to PDF file

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your XML File.
	string xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf");

	// Initialize XmlLoadOptions	
	XmlLoadOptions xmlLoadOptions = new XmlLoadOptions();
		
	using (Document pdfDocument = new Document(xmlFile, xmlLoadOptions))
	{
	 
		// Save XML file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XML File.
    Dim xmlFile = Path.Combine(dataDir, "XML-to-PDF.xml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XML-to-PDF.pdf")
 
    ' Initialize XmlLoadOptions
    Dim xmlLoadOptions As XmlLoadOptions = New XmlLoadOptions()
 
    Using pdfDocument As Document = New Document(xmlFile, xmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


