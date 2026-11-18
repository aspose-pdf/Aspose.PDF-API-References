---
title: Class XpsSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XpsSaveOptions class. Save options for export to Xps format
type: docs
weight: 11930
url: /net/aspose.pdf/xpssaveoptions/
---
## XpsSaveOptions class

Save options for export to Xps format

```csharp
public class XpsSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpssaveoptions/batchsize/) { get; set; } | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. |
| [DefaultFont](../../aspose.pdf/xpssaveoptions/defaultfont/) { get; set; } | Gets/sets the default font name. Used if the embedded font name is not found in the system. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format of data save. |
| [SaveTransparentTexts](../../aspose.pdf/xpssaveoptions/savetransparenttexts/) { get; set; } | Indicates whether to preserve transparent (OCR'ed) text. |
| [UseEmbeddedTrueTypeFonts](../../aspose.pdf/xpssaveoptions/useembeddedtruetypefonts/) { get; set; } | Gets/sets the flag to use embedded TrueType fonts. Avoiding the use of embedded TrueType fonts can reduce conversion time. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |

## Fields

| Name | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Process pages in few threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary. |

### See Also

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


