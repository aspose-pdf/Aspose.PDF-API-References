---
title: "PsSaveOptions Class"
linktitle: "PsSaveOptions"
articleTitle: "PsSaveOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.PsSaveOptions class. Save options for export to PS (PostScript) or EPS format."
type: docs
weight: 2630
url: "/net/aspose.pdf/pssaveoptions/"
keywords: "PsSaveOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PsSaveOptions class

Save options for export to PS (PostScript) or EPS format.

```csharp
public class PsSaveOptions : UnifiedSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PsSaveOptions](./pssaveoptions/#constructor) | Constructor. |
| [PsSaveOptions](./pssaveoptions/#constructor_1)(*[SaveFormat](../../aspose.pdf.lowcode/saveformat/)*) | Constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. *(Inherited from SaveOptions)* |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. *(Inherited from SaveOptions)* |
| [EmbedFont](./embedfont/) { get; set; } | Gets/sets flag that indicates if fonts must be embedded in resulting PS document. |
| [EmbedFontAs](./embedfontas/) { get; set; } | Gets/sets type in which fonts must be embedded in resulting PS document. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | This atrribute turned on functionality for extracting image or text. *(Inherited from UnifiedSaveOptions)* |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format of data save. *(Inherited from SaveOptions)* |
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

