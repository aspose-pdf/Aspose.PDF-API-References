---
title: "XpsSaveOptions Class"
linktitle: "XpsSaveOptions"
articleTitle: "XpsSaveOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.XpsSaveOptions class. Save options for export to Xps format"
type: docs
weight: 3370
url: "/net/aspose.pdf/xpssaveoptions/"
keywords: "XpsSaveOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## XpsSaveOptions class

Save options for export to Xps format

```csharp
public class XpsSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [XpsSaveOptions](./xpssaveoptions/#constructor) | Initializes a new instance of the XpsSaveOptions class. |

## Properties

| Name | Description |
| --- | --- |
| [BatchSize](./batchsize/) { get; set; } | Defines batch size if batched conversion is applicable. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. *(Inherited from SaveOptions)* |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. *(Inherited from SaveOptions)* |
| [DefaultFont](./defaultfont/) { get; set; } | Gets/sets the default font name. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | This atrribute turned on functionality for extracting image or text. *(Inherited from UnifiedSaveOptions)* |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format of data save. *(Inherited from SaveOptions)* |
| [SaveTransparentTexts](./savetransparenttexts/) { get; set; } | Indicates whether to preserve transparent (OCR'ed) text. |
| [UseEmbeddedTrueTypeFonts](./useembeddedtruetypefonts/) { get; set; } | Gets/sets the flag to use embedded TrueType fonts. |
| [UseNewImagingEngine](./usenewimagingengine/) { get; set; } | Gets or sets UseNewImagingEngine option. |
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

