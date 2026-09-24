---
title: "LaTeXSaveOptions Class"
linktitle: "LaTeXSaveOptions"
articleTitle: "LaTeXSaveOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.LaTeXSaveOptions class. Save options for export to TeX format."
type: docs
weight: 1690
url: "/net/aspose.pdf/latexsaveoptions/"
keywords: "LaTeXSaveOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## LaTeXSaveOptions class

> **Deprecated.** Use TeXSaveOptions instead

Save options for export to TeX format.

```csharp
public class LaTeXSaveOptions : TeXSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [LaTeXSaveOptions](./latexsaveoptions/#constructor) | Initializes a new instance of the LaTeXSaveOptions class. |

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. *(Inherited from SaveOptions)* |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. *(Inherited from SaveOptions)* |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | This atrribute turned on functionality for extracting image or text. *(Inherited from UnifiedSaveOptions)* |
| [OutDirectoryPath](../../aspose.pdf/texsaveoptions/outdirectorypath/) { get; set; } | Property for `_outDirectoryPath` parameter. *(Inherited from TeXSaveOptions)* |
| [PagesCount](../../aspose.pdf/texsaveoptions/pagescount/) { get; } | Returns the number of pages after conversion. *(Inherited from TeXSaveOptions)* |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format of data save. *(Inherited from SaveOptions)* |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. *(Inherited from SaveOptions)* |

## Methods

| Name | Description |
| --- | --- |
| [AddFontEncs](../../aspose.pdf/texsaveoptions/addfontencs/)(*string[]*) | Adds a font ancoding to the font encoding list. *(Inherited from TeXSaveOptions)* |
| [ClearFontEncs](../../aspose.pdf/texsaveoptions/clearfontencs/) | Clears the font encoding list. *(Inherited from TeXSaveOptions)* |

## Fields

| Name | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Process pages in few threads. *(Inherited from UnifiedSaveOptions)* |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells). *(Inherited from UnifiedSaveOptions)* |

### See Also

* class [TeXSaveOptions](../texsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

