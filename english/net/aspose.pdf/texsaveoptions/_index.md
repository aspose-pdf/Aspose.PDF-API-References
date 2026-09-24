---
title: "TeXSaveOptions Class"
linktitle: "TeXSaveOptions"
articleTitle: "TeXSaveOptions"
second_title: "Aspose.PDF for .NET"
description: "Save options for export to TeX format"
type: docs
weight: 3020
url: "/net/aspose.pdf/texsaveoptions/"
keywords: "TeXSaveOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TeXSaveOptions class

Save options for export to TeX format

```csharp
public class TeXSaveOptions : UnifiedSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TeXSaveOptions](./texsaveoptions/#constructor) | Initializes a new instance of the TeXSaveOptions class. |

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. *(Inherited from SaveOptions)* |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. *(Inherited from SaveOptions)* |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | This atrribute turned on functionality for extracting image or text. *(Inherited from UnifiedSaveOptions)* |
| [OutDirectoryPath](./outdirectorypath/) { get; set; } | Property for `_outDirectoryPath` parameter. |
| [PagesCount](./pagescount/) { get; } | Returns the number of pages after conversion. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format of data save. *(Inherited from SaveOptions)* |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. *(Inherited from SaveOptions)* |

## Methods

| Name | Description |
| --- | --- |
| [AddFontEncs](./addfontencs/)(*string[]*) | Adds a font ancoding to the font encoding list. |
| [ClearFontEncs](./clearfontencs/) | Clears the font encoding list. |

## Fields

| Name | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Process pages in few threads. *(Inherited from UnifiedSaveOptions)* |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells). *(Inherited from UnifiedSaveOptions)* |

### See Also

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

