---
title: "PdfFormatConversionOptions Class"
linktitle: "PdfFormatConversionOptions"
articleTitle: "PdfFormatConversionOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.PdfFormatConversionOptions class. represents set of options for convert PDF document"
type: docs
weight: 2450
url: "/net/aspose.pdf/pdfformatconversionoptions/"
keywords: "PdfFormatConversionOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfFormatConversionOptions class

represents set of options for convert PDF document

```csharp
public class PdfFormatConversionOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/#constructor)(*[PdfFormat](../../aspose.pdf/pdfformat/)*) | Constructor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/#constructor_1)(*string, [PdfFormat](../../aspose.pdf/pdfformat/)*) | Constructor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/#constructor_2)(*[PdfFormat](../../aspose.pdf/pdfformat/), [ConvertErrorAction](../../aspose.pdf/converterroraction/)*) | Constructor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/#constructor_3)(*string, [PdfFormat](../../aspose.pdf/pdfformat/), [ConvertErrorAction](../../aspose.pdf/converterroraction/)*) | Constructor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/#constructor_4)(*Stream, [PdfFormat](../../aspose.pdf/pdfformat/), [ConvertErrorAction](../../aspose.pdf/converterroraction/)*) | Constructor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/#constructor_5)(*string, [PdfFormat](../../aspose.pdf/pdfformat/), [ConvertErrorAction](../../aspose.pdf/converterroraction/), [ConvertTransparencyAction](../../aspose.pdf/converttransparencyaction/)*) | Constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AlignText](./aligntext/) { get; set; } | This flag controls text alignment in converted document. By default document conversion. |
| [AutoTaggingSettings](./autotaggingsettings/) { get; set; } | Gets or sets the settings for automatic tagging during PDF format conversion. |
| [ConvertSoftMaskAction](./convertsoftmaskaction/) { get; set; } | Action for images with soft mask. |
| [Default](./default/) { get; } | Gets PdfFormatConversionOptions object with default parameters. |
| [ErrorAction](./erroraction/) { get; set; } | Action for objects that can not be converted. |
| [ExcludeFontsStrategy](./excludefontsstrategy/) { get; set; } | Strategy(ies) to exclude superfluous fonts and reduce document file size. |
| [FontEmbeddingOptions](./fontembeddingoptions/) { get; } | Options for cases when it's not possible to embed some fonts into PDF document. |
| [Format](./format/) { get; set; } | PDF format. |
| [IccProfileFileName](./iccprofilefilename/) { get; set; } | Gets or sets the filename of icc profile name. In case of null the default icc profile used. |
| [IsAsyncImageStreamsConversionMode](./isasyncimagestreamsconversionmode/) { get; set; } | Gets/sets run of image streams in async mode. |
| [IsLowMemoryMode](./islowmemorymode/) { get; set; } | Is low memory conversion mode enabled. |
| [IsTransferInfo](./istransferinfo/) { get; set; } | Gets or sets whether to pass data from Info to Metadata when converted to PDF 2.0. True by default. |
| [LogFileName](./logfilename/) { get; set; } | Path to file where comments will be stored. |
| [LogStream](./logstream/) { get; set; } | Stream where comments will be stored. |
| [NonSpecificationCases](./nonspecificationcases/) { get; } | Holds flags to control PDF/A conversion process for cases when source document. |
| [NotAccessibleFonts](./notaccessiblefonts/) { get; } | This property is out-property. It holds all the fonts(font names) which were not found on computer. |
| [OptimizeFileSize](./optimizefilesize/) { get; set; } | Gets or sets a flag which enables/disables special conversion mode to get PDF/A document with reduced file size. |
| [OutputIntent](./outputintent/) { get; set; } | Gets or sets the [`OutputIntent`](../../aspose.pdf/outputintent/) for the PDF format conversion. |
| [PuaTextProcessingStrategy](./puatextprocessingstrategy/) { get; set; } | Strategy to process symbols from unicode Private Use Area (PUA). |
| [SymbolicFontEncodingStrategy](./symbolicfontencodingstrategy/) { get; set; } | Strategy to copy encoding data for symbolic fonts if symbolic TrueType font. |
| [TransparencyAction](./transparencyaction/) { get; set; } | Action for image masked objects. |
| [UnicodeProcessingRules](./unicodeprocessingrules/) { get; set; } | Rules to solve problems with unicode mapping. Can be null. |

## Fields

| Name | Description |
| --- | --- |
| [AlignStrategy](./alignstrategy/) | Strategy to align text. This parameter has sense only when flag `AlignText` is set to true. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

