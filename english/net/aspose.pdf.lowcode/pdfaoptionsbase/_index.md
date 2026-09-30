---
title: "PdfAOptionsBase Class"
linktitle: "PdfAOptionsBase"
articleTitle: "PdfAOptionsBase"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LowCode.PdfAOptionsBase class. Represents the base class for the PdfAConverter plugin options. This class provides properties and methods for conf..."
type: docs
weight: 600
url: "/net/aspose.pdf.lowcode/pdfaoptionsbase/"
keywords: "PdfAOptionsBase, Aspose.Pdf.LowCode, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfAOptionsBase class

Represents the base class for the [`PdfAConverter`](../../aspose.pdf.lowcode/pdfaconverter/) plugin options.
 This class provides properties and methods for configuring the PDF/A conversion and validation process.

```csharp
public abstract class PdfAOptionsBase : IPluginOptions
```

## Properties

| Name | Description |
| --- | --- |
| [AlignText](./aligntext/) { get; set; } | Gets or sets a value indicating whether additional means are necessary to preserve text alignment during the PDF/A conversion process. |
| [ErrorAction](./erroraction/) { get; set; } | Gets or sets the action to be taken for objects that cannot be converted. |
| [ExcludeFontsStrategy](./excludefontsstrategy/) { get; set; } | Gets or sets the strategy for removing fonts to minimize the output file size during the PDF/A conversion process. |
| [FontEmbeddingOptions](./fontembeddingoptions/) { get; } | Gets the options to process fonts that cannot be embedded into the document. |
| [IccProfileFileName](./iccprofilefilename/) { get; set; } | Gets or sets the filename of the ICC (International Color Consortium) profile to be used for the PDF/A conversion in place of the default one. |
| [Inputs](./inputs/) { get; } | Gets collection of data sources |
| [IsLowMemoryMode](./islowmemorymode/) { get; set; } | Gets or sets a value indicating whether the low memory mode is enabled during the PDF/A conversion process. |
| [LogOutputSource](./logoutputsource/) { get; set; } | Gets or sets the data source for the log output. |
| [NonSpecificationFlags](./nonspecificationflags/) { get; } | Gets the flags that control the PDF/A conversion for cases when the source PDF document doesn't correspond to the PDF specification. |
| [OptimizeFileSize](./optimizefilesize/) { get; set; } | Gets or sets a value indicating whether to try to reduce the file size during the PDF/A conversion process. |
| [PdfAVersion](./pdfaversion/) { get; set; } | Gets or sets the version of the PDF/A standard to be used for validation or conversion. |
| [PuaSymbolsProcessingStrategy](./puasymbolsprocessingstrategy/) { get; set; } | Gets or sets the strategy for processing Private Use Area (PUA) symbols in the PDF document. |
| [SoftMaskAction](./softmaskaction/) { get; set; } | Gets or sets the action to be taken during the conversion of images with soft masks. |
| [SymbolicFontEncodingStrategy](./symbolicfontencodingstrategy/) { get; set; } | Gets or sets the strategy for encoding symbolic fonts when converting to PDF/A format. |
| [UnicodeProcessingRules](./unicodeprocessingrules/) { get; set; } | Gets or sets the rules for processing ToUnicode CMap tables and not linked to Unicode symbols during the PDF/A conversion process. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](./addinput/)(IDataSource) | Adds new data source to the collection |

### See Also

* namespace [Aspose.Pdf.LowCode](../../aspose.pdf.lowcode/)
* assembly [Aspose.PDF](../../)

