---
title: "UnifiedSaveOptions Class"
linktitle: "UnifiedSaveOptions"
articleTitle: "UnifiedSaveOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.UnifiedSaveOptions class. This class represents saving options for saving that uses unified conversion way (with unified internal document model)"
type: docs
weight: 3050
url: "/net/aspose.pdf/unifiedsaveoptions/"
keywords: "UnifiedSaveOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## UnifiedSaveOptions class

This class represents saving options for saving that 
 uses unified conversion way (with unified internal document model)

```csharp
public class UnifiedSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [UnifiedSaveOptions](unifiedsaveoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format of data save. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |

## Fields

| Name | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Process pages in few threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary. |

## Other Members

| Name | Description |
| --- | --- |
| delegate [ConversionProgressEventHandler](../../aspose.pdf/unifiedsaveoptions.conversionprogresseventhandler) | Represents method that usually supplied by calling side and handles progress events that comes from converter. Usually such suplied customer's handler can be used to show total conversion progress on console or in progress bar. represents information about occured progress event |
| class [ProgressEventHandlerInfo](../../aspose.pdf/unifiedsaveoptions.progresseventhandlerinfo) | This class represents information about conversion progress that can be used in external applicatuion to show conversion progress to end user |

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

