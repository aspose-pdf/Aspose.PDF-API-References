---
title: "PptxSaveOptions Class"
linktitle: "PptxSaveOptions"
articleTitle: "PptxSaveOptions"
second_title: "Aspose.PDF for .NET"
description: "Save options for export to SVG format"
type: docs
weight: 2570
url: "/net/aspose.pdf/pptxsaveoptions/"
keywords: "PptxSaveOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PptxSaveOptions class

Save options for export to SVG format

```csharp
public class PptxSaveOptions : UnifiedSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PptxSaveOptions](./pptxsaveoptions/#constructor) | Initializes a new instance of the PptxSaveOptions class. |

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. *(Inherited from SaveOptions)* |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. *(Inherited from SaveOptions)* |
| [CustomProgressHandler](./customprogresshandler/) { get; set; } | This handler can be used to handle conversion progress events. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | This atrribute turned on functionality for extracting image or text. *(Inherited from UnifiedSaveOptions)* |
| [ImageResolution](./imageresolution/) { get; set; } | Gets or sets the image resolution (dpi). Default is 192 dpi. |
| [OptimizeTextBoxes](./optimizetextboxes/) { get; set; } | Toggles text columns recognition. |
| [RecognizeUnderlineAndStrikeout](./recognizeunderlineandstrikeout/) { get; set; } | Gets or sets whether underline and strikeout lines are recognized as text formatting. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format of data save. *(Inherited from SaveOptions)* |
| [SeparateImages](./separateimages/) { get; set; } | If set to true then images are separated from all other graphics. |
| [SlidesAsImages](./slidesasimages/) { get; set; } | If set to true then all the content is recognized as images (one per page). |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. *(Inherited from SaveOptions)* |

## Fields

| Name | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Process pages in few threads. *(Inherited from UnifiedSaveOptions)* |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells). *(Inherited from UnifiedSaveOptions)* |

### See Also

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

