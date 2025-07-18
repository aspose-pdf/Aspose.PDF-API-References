---
title: Class XslFoLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptions class. Represents options for loading/importing XSLFO file into pdf document
type: docs
weight: 11720
url: /net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class

Represents options for loading/importing XSL-FO file into pdf document.

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | Creates `XslFoLoadOptions` object without xsl data. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | Creates `XslFoLoadOptions` object with xsl data. |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | Creates `XslFoLoadOptions` object with xsl data. |

## Properties

| Name | Description |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | The base path/url from which are searched relative paths to external resources (if any) referenced in loaded SVG file. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When `true`, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../loadoptions/) describes. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | Gets xsl data for converting xml into pdf document. |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | XsltArgumentList for inserting values into existing xls parameters  XLS file has 'animal' parameter without value: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); now the converter assumes that there is an 'animal' parameter with the value 'cat' in the XLS file. |

## Fields

| Name | Description |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | Source XSLFO document can contain formatting errors. This enum enumerates possible strategies of handking of that errors |

## Examples

The following example shows how to convert XSL-FO file to PDF file

```csharp
[C#]
// The path to the documents directory.
string dataDir = @"YOUR_DATA_DIRECTORY";

// The path to your XSL-FO File.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// The path to output PDF File.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Initialize XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Save PDF file
    pdfDocument.Save(pdfFile);
}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XSL-FO File.
    Dim xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf")
 
    ' Initialize XslFoLoadOptions  
    Dim xslFoLoadOptions As XslFoLoadOptions = New XslFoLoadOptions()
 
    Using pdfDocument As Document = New Document(xslFoFile, xslFoLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


