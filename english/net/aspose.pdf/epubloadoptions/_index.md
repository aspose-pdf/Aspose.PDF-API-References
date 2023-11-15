---
title: Class EpubLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubLoadOptions class. Contains options for loading/importing EPUB file into pdf document
type: docs
weight: 2140
url: /net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class

Contains options for loading/importing EPUB file into pdf document.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | Creates default load options for converting EPUB file into pdf document. Default pdf page size - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | Creates load options with specified page size. |

## Properties

| Name | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Gets or sets flag to disable any license restrictions for all fonts while loading the file. When `true`, allows to execute operations with font that are prohibited by a license of this font, for example allows to embed a font into a PDF document even if license rules disable embedding for this font. By default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Represents file format which [`LoadOptions`](../loadoptions/) describes. |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | Gets reference on object that represent marging info. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | Gets or sets output page size for import. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Load operation continues, however the user may also return Abort in which case the Load operation should cease. |

## Fields

| Name | Description |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | Represents mode of usage of margins area - defines treatement of instructions (if any) of CSS of imported document related to usage of margins. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | ATTENTION! The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats (like HTML, EPUB etc), usually have float design, so, it allows to fit required pagesize. But sometimes content has specified horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case (i.e when size of content does not fit required initial page size of result PDF document). |

## Examples

The following example shows how to convert EPUB file to PDF file

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your EPUB File.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initialize EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your EPUB File.
    Dim epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf")
 
    ' Initialize EpubLoadOptions    
    Dim epubLoadOptions As EpubLoadOptions = New EpubLoadOptions()
 
    Using pdfDocument As Document = New Document(epubFile, epubLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### See Also

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


