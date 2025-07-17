---
title: Class PdfAValidateOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAValidateOptions class. Represents options for validating PDF/A compliance of PDF documents with the PdfAConverter plugin
type: docs
weight: 9180
url: /net/aspose.pdf.plugins/pdfavalidateoptions/
---
## PdfAValidateOptions class

Represents options for validating PDF/A compliance of PDF documents with the [`PdfAConverter`](../pdfaconverter/) plugin.

```csharp
public sealed class PdfAValidateOptions : PdfAOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfAValidateOptions](pdfavalidateoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | Gets or sets a value indicating whether additional means are necessary to preserve text alignment during the PDF/A conversion process. |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | Gets or sets the action to be taken for objects that cannot be converted. |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | Gets or sets the strategy for removing fonts to minimize the output file size during the PDF/A conversion process. |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | Gets the options to process fonts that cannot be embedded into the document. |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | Gets or sets the filename of the ICC (International Color Consortium) profile to be used for the PDF/A conversion in place of the default one. |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | Gets collection of data sources |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | Gets or sets a value indicating whether the low memory mode is enabled during the PDF/A conversion process. |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | Gets or sets the data source for the log output. |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | Gets the flags that control the PDF/A conversion for cases when the source PDF document doesn't correspond to the PDF specification. |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | Gets or sets a value indicating whether to try to reduce the file size during the PDF/A conversion process. |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | Gets or sets the version of the PDF/A standard to be used for validation or conversion. |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | Gets or sets the strategy for processing Private Use Area (PUA) symbols in the PDF document. |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | Gets or sets the action to be taken during the conversion of images with soft masks. |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | Gets or sets the strategy for encoding symbolic fonts when converting to PDF/A format. |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | Gets or sets the rules for processing ToUnicode CMap tables and not linked to Unicode symbols during the PDF/A conversion process. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | Adds new data source to the collection |

### See Also

* class [PdfAOptionsBase](../pdfaoptionsbase/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


