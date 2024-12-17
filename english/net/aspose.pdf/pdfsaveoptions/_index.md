---
title: Class PdfSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfSaveOptions class. Save options for export to Pdf format
type: docs
weight: 8340
url: /net/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions class

Save options for export to Pdf format

```csharp
public class PdfSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname/) { get; set; } | Font name used by default for fonts which are absent on computer. When the PDF document that is saved into PDF contains fonts, that are not available in the document itself and on the device, API replaces this fonts with the default font(if font with [`DefaultFontName`](./defaultfontname/) is found on device) |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format of data save. |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath/) { get; set; } | Path for temporary files. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |

## Examples

The following example shows how to set default font name while Saving PDF

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


