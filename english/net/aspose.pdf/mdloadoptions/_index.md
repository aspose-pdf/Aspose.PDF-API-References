---
title: Class MdLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.MdLoadOptions class. Load options for Markdown format conversion
type: docs
weight: 6930
url: /net/aspose.pdf/mdloadoptions/
---
## MdLoadOptions class

Load options for Markdown format conversion.

```csharp
public class MdLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MdLoadOptions](mdloadoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When `true`, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default `false`. |
| [IsPriorityCssPageRule](../../aspose.pdf/mdloadoptions/isprioritycsspagerule/) { get; set; } | Gets or sets the flag that specifies that @page rules defined in css will override values defined in PageInfo. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../loadoptions/) describes. |
| [PageInfo](../../aspose.pdf/mdloadoptions/pageinfo/) { get; set; } | Gets or sets document page info |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |

## Examples

The following example shows how to convert MD file to PDF file

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your MD File.
	string mdFile = Path.Combine(dataDir, "MD-to-PDF.md");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "MD-to-PDF.pdf");

	// Initialize MdLoadOptions	
	MdLoadOptions mdLoadOptions = new MdLoadOptions();
		
	using (Document pdfDocument = new Document(mdFile, mdLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your MD File.
    Dim mdFile = Path.Combine(dataDir, "MD-to-PDF.md")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "MD-to-PDF.pdf")
 
    ' Initialize MdLoadOptions  
    Dim mdLoadOptions As MdLoadOptions = New MdLoadOptions()
 
    Using pdfDocument As Document = New Document(mdFile, mdLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


