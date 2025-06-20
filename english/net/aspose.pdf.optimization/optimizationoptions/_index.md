---
title: Class OptimizationOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Optimization.OptimizationOptions class. Class which describes document optimization algorithm. Instance of this class may be used as parameter of OptimizeResources method
type: docs
weight: 8120
url: /net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions class

Class which describes document optimization algorithm. Instance of this class may be used as parameter of OptimizeResources() method.

```csharp
public class OptimizationOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | If true page contents will be reused when document is optimized for equal pages. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | If this flag is set to `true`, Pdf objects will be packed into Objest Streams and compressed to reduce pdf file size. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Set of options which describe will images in the document be compressed and parameters of the compression. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Image encodre which will be used. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then thes streams will be stored as one object. This allows to decrease document size in some cases (for example, when same document was concatenedted multiple times). |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Specifies maximum resolution of images. If image has higher resolition it will be scaled |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Remove private information (page piece info). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. This may decrease document size for example when pages were extracted from document. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | Fonts will be converted into subsets if set to true. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Make fonts not embedded if set to true. |

## Methods

| Name | Description |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | Creates optimization strategy will all options activated. Please note that activated only options which does not change any functionality of the document. I.e. image compressing and fonts unembedding will not enabled (and can be embedded manually). |

### See Also

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


