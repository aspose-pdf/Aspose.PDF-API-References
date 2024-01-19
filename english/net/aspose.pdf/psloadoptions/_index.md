---
title: Class PsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PsLoadOptions class. Represents options for loading/importing of .mhtfile into pdf document
type: docs
weight: 7350
url: /net/aspose.pdf/psloadoptions/
---
## PsLoadOptions class

Represents options for loading/importing of .mht-file into pdf document.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When `true`, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default `false`. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | Gets or sets fonts folders paths. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../loadoptions/) describes. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |

## Examples

The following example shows how to convert PS file to PDF file

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your PS File.
	string psFile = Path.Combine(dataDir, "PS-to-PDF.ps");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "PS-to-PDF.pdf");

	// Initialize PsLoadOptions	
	PsLoadOptions psLoadOptions = new PsLoadOptions();
		
	using (Document pdfDocument = new Document(psFile, psLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PS File.
    Dim psFile = Path.Combine(dataDir, "PS-to-PDF.ps")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PS-to-PDF.pdf")
 
    ' Initialize PsLoadOptions  
    Dim psLoadOptions As PsLoadOptions = New PsLoadOptions()
 
    Using pdfDocument As Document = New Document(psFile, psLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


