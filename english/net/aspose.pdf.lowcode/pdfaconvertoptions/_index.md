---
title: "PdfAConvertOptions Class"
linktitle: "PdfAConvertOptions"
articleTitle: "PdfAConvertOptions"
second_title: "Aspose.PDF for .NET"
description: "Represents options for converting PDF documents to PDF/A format with the plugin."
type: docs
weight: 580
url: "/net/aspose.pdf.lowcode/pdfaconvertoptions/"
keywords: "PdfAConvertOptions, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfAConvertOptions class

Represents options for converting PDF documents to PDF/A format with the [`PdfAConverter`](../../aspose.pdf.lowcode/pdfaconverter/) plugin.

```csharp
public sealed class PdfAConvertOptions : PdfAOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfAConvertOptions](./pdfaconvertoptions/#constructor) | Initializes a new instance of the PdfAConvertOptions class. |

## Properties

| Name | Description |
| --- | --- |
| [AlignText](../../aspose.pdf.lowcode/pdfaoptionsbase/aligntext/) { get; set; } | Gets or sets a value indicating whether additional means are necessary to preserve text alignment. *(Inherited from PdfAOptionsBase)* |
| [ErrorAction](../../aspose.pdf.lowcode/pdfaoptionsbase/erroraction/) { get; set; } | Gets or sets the action to be taken for objects that cannot be converted. *(Inherited from PdfAOptionsBase)* |
| [ExcludeFontsStrategy](../../aspose.pdf.lowcode/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | Gets or sets the strategy for removing fonts to minimize the output file size during the PDF/A conversion process. *(Inherited from PdfAOptionsBase)* |
| [FontEmbeddingOptions](../../aspose.pdf.lowcode/pdfaoptionsbase/fontembeddingoptions/) { get; } | Gets the options to process fonts that cannot be embedded into the document. *(Inherited from PdfAOptionsBase)* |
| [IccProfileFileName](../../aspose.pdf.lowcode/pdfaoptionsbase/iccprofilefilename/) { get; set; } | Gets or sets the filename of the ICC (International Color Consortium) profile to be used for the PDF/A conversion in place of. *(Inherited from PdfAOptionsBase)* |
| [Inputs](../../aspose.pdf.lowcode/pdfaoptionsbase/inputs/) { get; } | Gets collection of data sources. *(Inherited from PdfAOptionsBase)* |
| [IsLowMemoryMode](../../aspose.pdf.lowcode/pdfaoptionsbase/islowmemorymode/) { get; set; } | Gets or sets a value indicating whether the low memory mode is enabled during the PDF/A conversion process. *(Inherited from PdfAOptionsBase)* |
| [LogOutputSource](../../aspose.pdf.lowcode/pdfaoptionsbase/logoutputsource/) { get; set; } | Gets or sets the data source for the log output. *(Inherited from PdfAOptionsBase)* |
| [NonSpecificationFlags](../../aspose.pdf.lowcode/pdfaoptionsbase/nonspecificationflags/) { get; } | Gets the flags that control the PDF/A conversion for cases when the source PDF document doesn't. *(Inherited from PdfAOptionsBase)* |
| [OptimizeFileSize](../../aspose.pdf.lowcode/pdfaoptionsbase/optimizefilesize/) { get; set; } | Gets or sets a value indicating whether to try to reduce the file size during the PDF/A conversion process. *(Inherited from PdfAOptionsBase)* |
| [Outputs](./outputs/) { get; } | Gets the collection of added targets (file or stream data sources) for saving operation results. |
| [PdfAVersion](../../aspose.pdf.lowcode/pdfaoptionsbase/pdfaversion/) { get; set; } | Gets or sets the version of the PDF/A standard to be used for validation or conversion. *(Inherited from PdfAOptionsBase)* |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.lowcode/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Gets or sets the strategy for processing Private Use Area (PUA) symbols in the PDF document. *(Inherited from PdfAOptionsBase)* |
| [SoftMaskAction](../../aspose.pdf.lowcode/pdfaoptionsbase/softmaskaction/) { get; set; } | Gets or sets the action to be taken during the conversion of images with soft masks. *(Inherited from PdfAOptionsBase)* |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.lowcode/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Gets or sets the strategy for encoding symbolic fonts when converting to PDF/A format. *(Inherited from PdfAOptionsBase)* |
| [UnicodeProcessingRules](../../aspose.pdf.lowcode/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Gets or sets the rules for processing ToUnicode CMap tables and not linked to Unicode symbols during the PDF/A conversion process. *(Inherited from PdfAOptionsBase)* |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.lowcode/pdfaoptionsbase/addinput/)(*IDataSource*) | Adds new data source to the collection. *(Inherited from PdfAOptionsBase)* |
| [AddOutput](./addoutput/)(*IDataSource*) | Adds new result save target. |

### See Also

* class [PdfAOptionsBase](../pdfaoptionsbase/)
* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

