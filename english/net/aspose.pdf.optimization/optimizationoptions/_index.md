---
title: "OptimizationOptions Class"
linktitle: "OptimizationOptions"
articleTitle: "OptimizationOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Optimization.OptimizationOptions class. Class which describes document optimization algorithm. Instance of this class may be used as parameter of ..."
type: docs
weight: 50
url: "/net/aspose.pdf.optimization/optimizationoptions/"
keywords: "OptimizationOptions, Aspose.Pdf.Optimization, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## OptimizationOptions class

Class which describes document optimization algorithm.
 Instance of this class may be used as parameter of OptimizeResources() method.

```csharp
public class OptimizationOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [OptimizationOptions](./optimizationoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AllowReusePageContent](./allowreusepagecontent/) { get; set; } | If true page contents will be reused when document is optimized for equal pages. |
| [CompressAllContentStreams](./compressallcontentstreams/) { get; set; } | If set to , all uncompressed page content streams will be compressed using the FlateDecode filter during `OptimizeResources`. Default is to preserve backward compatibility. |
| [CompressObjects](./compressobjects/) { get; set; } | If this flag is set to , Pdf objects will be packed into Objest Streams and compressed to reduce pdf file size. |
| [ImageCompressionOptions](./imagecompressionoptions/) { get; } | Set of options which describe will images in the document be compressed and parameters of the compression. |
| [ImageEncoding](./imageencoding/) { get; set; } | Image encodre which will be used. |
| [LinkDuplicateStreams](./linkduplicatestreams/) { get; set; } | If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then thes streams will be stored as one object. This allows to decrease document size in some cases (for example, when same document was concatenedted multiple times). |
| [MaxResoultion](./maxresoultion/) { get; set; } | Specifies maximum resolution of images. If image has higher resolition it will be scaled |
| [RemovePrivateInfo](./removeprivateinfo/) { get; set; } | Remove private information (page piece info). |
| [RemoveUnusedObjects](./removeunusedobjects/) { get; set; } | If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document. |
| [RemoveUnusedStreams](./removeunusedstreams/) { get; set; } | If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. This may decrease document size for example when pages were extracted from document. |
| [SubsetFonts](./subsetfonts/) { get; set; } | Fonts will be converted into subsets if set to true. |
| [UnembedFonts](./unembedfonts/) { get; set; } | Make fonts not embedded if set to true. |

## Methods

| Name | Description |
| --- | --- |
| static [All](./all/)() | Creates optimization strategy will all options activated. Please note that activated only options which does not change any functionality of the document. I.e. image compressing and fonts unembedding will not enabled (and can be embedded manually). |

### See Also

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)

