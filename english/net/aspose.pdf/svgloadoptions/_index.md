---
title: Class SvgLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgLoadOptions class. Represents options for loading/importing SVG file into pdf document
type: docs
weight: 7820
url: /net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions class

Represents options for loading/importing SVG file into pdf document.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | Adust pdf page size to svg size |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When `true`, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../loadoptions/) describes. |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | Gets or sets page info that should be applied during loading of document. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |

## Fields

| Name | Description |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | Allows select conversion engine that will be in use during conversion. Currently new engine is in B-testing stage, so this value by default set to ConversionEngines.LegacyEngine |

## Examples

The following example shows how to convert SVG file to PDF file

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your SVG File.
	string svgFile = Path.Combine(dataDir, "SVG-to-PDF.svg");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "SVG-to-PDF.pdf");

	// Initialize SvgLoadOptions	
	SvgLoadOptions svgLoadOptions = new SvgLoadOptions();
		
	using (Document pdfDocument = new Document(svgFile, svgLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your SVG File.
    Dim svgFile = Path.Combine(dataDir, "SVG-to-PDF.svg")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "SVG-to-PDF.pdf")
 
    ' Initialize SvgLoadOptions
    Dim svgLoadOptions As SvgLoadOptions = New SvgLoadOptions()
 
    Using pdfDocument As Document = New Document(svgFile, svgLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


