---
title: "DocSaveOptions Class"
linktitle: "DocSaveOptions"
articleTitle: "DocSaveOptions"
second_title: "Aspose.PDF for .NET"
description: "Save options for export to Doc format"
type: docs
weight: 580
url: "/net/aspose.pdf/docsaveoptions/"
keywords: "DocSaveOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## DocSaveOptions class

Save options for export to Doc format

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [DocSaveOptions](./docsaveoptions/#constructor) | Initializes a new instance of the DocSaveOptions class. |

## Properties

| Name | Description |
| --- | --- |
| [AddReturnToLineEnd](./addreturntolineend/) { get; set; } | Use paragraph or line breaks. |
| [BatchSize](./batchsize/) { get; set; } | Defines batch size if batched conversion is applicable. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. *(Inherited from SaveOptions)* |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. *(Inherited from SaveOptions)* |
| [ConvertType3Fonts](./converttype3fonts/) { get; set; } | Gets or sets conversion for Type3 fonts. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | This atrribute turned on functionality for extracting image or text. *(Inherited from UnifiedSaveOptions)* |
| [Format](./format/) { get; set; } | Output format. |
| [ImageResolutionX](./imageresolutionx/) { get; set; } | Converted images X resolution. |
| [ImageResolutionY](./imageresolutiony/) { get; set; } | Converted images Y resolution. |
| [MaxDistanceBetweenTextLines](./maxdistancebetweentextlines/) { get; set; } | This parameter is used for grouping text lines into paragraphs. |
| [MemorySaveModePath](./memorysavemodepath/) { get; set; } | Defines the path (file name or directory name) to hold. |
| [Mode](./mode/) { get; set; } | Recognition mode. |
| [ReSaveFonts](./resavefonts/) { get; set; } | Gets or sets the procedure for resaving fonts. |
| [RecognizeBullets](./recognizebullets/) { get; set; } | Switch on the recognition of bullets. |
| [RelativeHorizontalProximity](./relativehorizontalproximity/) { get; set; } | In Pdf words may be innerly represented with operators that prints words. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format of data save. *(Inherited from SaveOptions)* |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. *(Inherited from SaveOptions)* |

## Fields

| Name | Description |
| --- | --- |
| [CustomProgressHandler](./customprogresshandler/) | This handler can be used to handle conversion progress events. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Process pages in few threads. *(Inherited from UnifiedSaveOptions)* |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells). *(Inherited from UnifiedSaveOptions)* |

### See Also

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

