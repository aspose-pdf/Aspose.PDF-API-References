---
title: Class PclLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PclLoadOptions class. Represents options for loadingimport PCL file into pdf document
type: docs
weight: 6490
url: /net/aspose.pdf/pclloadoptions/
---
## PclLoadOptions class

Represents options for loading(import) PCL file into pdf document.

```csharp
public sealed class PclLoadOptions : LoadOptions, IPipelineOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PclLoadOptions](pclloadoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BatchSize](../../aspose.pdf/pclloadoptions/batchsize/) { get; set; } | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When `true`, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../loadoptions/) describes. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |

## Fields

| Name | Description |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/pclloadoptions/conversionengine/) | Defines conversion engine that will be used for conversion |
| [Exceptions](../../aspose.pdf/pclloadoptions/exceptions/) | List of conversion errors. |
| [SupressErrors](../../aspose.pdf/pclloadoptions/supresserrors/) | Gets or sets boolean value which indicates will PCL conversion errors should be supressed. |

## Examples

The following example shows how to convert PCL file to PDF file

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your PCL File.
	string pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf");

	// Initialize PclLoadOptions	
	PclLoadOptions pclLoadOptions = new PclLoadOptions();
		
	using (Document pdfDocument = new Document(pclFile, pclLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PCL File.
    Dim pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf")
 
    ' Initialize PclLoadOptions
    Dim pclLoadOptions As PclLoadOptions = New PclLoadOptions()
 
    Using pdfDocument As Document = New Document(pclFile, pclLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


