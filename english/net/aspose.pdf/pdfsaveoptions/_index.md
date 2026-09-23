---
title: Class PdfSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfSaveOptions class. Save options for export to Pdf format
type: docs
weight: 9700
url: /net/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions class

Save options for export to Pdf format

```csharp
public class PdfSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. |
| [DefaultFontName](../../aspose.pdf/pdfsaveoptions/defaultfontname/) { get; set; } | Font name used by default for fonts which are absent on computer. When the PDF document that is saved into PDF contains fonts, that are not available in the document itself and on the device, API replaces this fonts with the default font(if font with [`DefaultFontName`](./defaultfontname/) is found on device) |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format of data save. |
| [TempPath](../../aspose.pdf/pdfsaveoptions/temppath/) { get; set; } | Path for temporary files. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |

### See Also

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


