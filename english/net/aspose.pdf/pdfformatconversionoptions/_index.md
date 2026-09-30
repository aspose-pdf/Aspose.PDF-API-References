---
title: "PdfFormatConversionOptions Class"
linktitle: "PdfFormatConversionOptions"
articleTitle: "PdfFormatConversionOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.PdfFormatConversionOptions class. represents set of options for convert PDF document"
type: docs
weight: 2410
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
| [PdfFormatConversionOptions](./pdfformatconversionoptions/#constructor)(PdfFormat) | Constructor |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | Constructor |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/#constructor_2)(string, PdfFormat) | Constructor |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/#constructor_3)(Stream, PdfFormat, ConvertErrorAction) | Constructor |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | Constructor |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Constructor |

## Properties

| Name | Description |
| --- | --- |
| [AlignText](./aligntext/) { get; set; } | This flag controls text alignment in converted document. By default document conversion doesn't affect text alignment and leave text as is. But in some cases font substitution causes text overlapping or extra spaces in converted document. When this flag is set special alignment operations will be performed. This flag should be set only for documents which have problems with overlapped text or extra text spaces cause using of this flag decrease performance and in some cases could corrupt text content. |
| [AutoTaggingSettings](./autotaggingsettings/) { get; set; } | Gets or sets the settings for automatic tagging during PDF format conversion. |
| [ConvertSoftMaskAction](./convertsoftmaskaction/) { get; set; } | Action for images with soft mask. |
| static [Default](./default/) { get; } | Gets PdfFormatConversionOptions object with default parameters |
| [ErrorAction](./erroraction/) { get; set; } | Action for objects that can not be converted |
| [ExcludeFontsStrategy](./excludefontsstrategy/) { get; set; } | Strategy(ies) to exclude superfluous fonts and reduce document file size. This parameter has sense only when flag `OptimizeFileSize` is set to true. By default combination of strategies `SubsetFonts` and `RemoveDuplicatedFonts` is used. |
| [FontEmbeddingOptions](./fontembeddingoptions/) { get; } | Options for cases when it's not possible to embed some fonts into PDF document. |
| [Format](./format/) { get; set; } | PDF format. |
| [IccProfileFileName](./iccprofilefilename/) { get; set; } | Gets or sets the filename of icc profile name. In case of null the default icc profile used. |
| [IsAsyncImageStreamsConversionMode](./isasyncimagestreamsconversionmode/) { get; set; } | Gets/sets run of image streams in async mode. |
| [IsLowMemoryMode](./islowmemorymode/) { get; set; } | Is low memory conversion mode enabled |
| [IsTransferInfo](./istransferinfo/) { get; set; } | Gets or sets whether to pass data from Info to Metadata when converted to PDF 2.0. True by default. |
| [LogFileName](./logfilename/) { get; set; } | Path to file where comments will be stored. |
| [LogStream](./logstream/) { get; set; } | Stream where comments will be stored. |
| [NonSpecificationCases](./nonspecificationcases/) { get; } | Holds flags to control PDF/A conversion process for cases when source document doesn't correspond to PDF/A specification. |
| [NotAccessibleFonts](./notaccessiblefonts/) { get; } | This property is out-property. It holds all the fonts(font names) which were not found on computer at last PDF/A conversion. |
| [OptimizeFileSize](./optimizefilesize/) { get; set; } | Gets or sets a flag which enables/disables special conversion mode to get PDF/A document with reduced file size. Now this flag impacts on optimization of fonts used in PDF document, possibly, in future, this flag also will be used to switch on optimization for another data structures, such as graphic. Set of this flag and mode could significantly reduce file size but at the same time it could significantly decrease performance of conversion. |
| [OutputIntent](./outputintent/) { get; set; } | Gets or sets the [`OutputIntent`](../../aspose.pdf/outputintent/) for the PDF format conversion. |
| [PuaTextProcessingStrategy](./puatextprocessingstrategy/) { get; set; } | Strategy to process symbols from unicode Private Use Area (PUA). |
| [SymbolicFontEncodingStrategy](./symbolicfontencodingstrategy/) { get; set; } | Strategy to copy encoding data for symbolic fonts if symbolic TrueType font has more than one encoding subtable. |
| [TransparencyAction](./transparencyaction/) { get; set; } | Action for image masked objects |
| [UnicodeProcessingRules](./unicodeprocessingrules/) { get; set; } | Rules to solve problems with unicode mapping. Can be null. |

## Fields

| Name | Description |
| --- | --- |
| [AlignStrategy](./alignstrategy/) | Strategy to align text. This parameter has sense only when flag `AlignText` is set to true. |

## Other Members

| Name | Description |
| --- | --- |
| enum [PuaProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions.puaprocessingstrategy) | Some PDF documents have special unicode symbols, which are belonged to Private Use Area (PUA), see description at https://en.wikipedia.org/wiki/Private_Use_Areas. This symbols cause an PDF/A compliant errors like "Text is mapped to Unicode Private Use Area but no ActualText entry is present". This enumeration declares a strategies which can be used to handle PUA symbols. |
| enum [RemoveFontsStrategy](../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy) | Some documens have large size after converison into PDF/A format. To reduce file size for these documents it's necessary to define a strategy of fonts removing. This enumeration declares a strategies which can be used to optimize fonts usage. Every strategy from this enumeration has sense only when flag `OptimizeFileSize` is set. |
| enum [SegmentAlignStrategy](../../aspose.pdf/pdfformatconversionoptions.segmentalignstrategy) | Describes strategies used to align document text segments. Now only strategy to restore segments to original bounds is supported. In future another strategies could be added. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

