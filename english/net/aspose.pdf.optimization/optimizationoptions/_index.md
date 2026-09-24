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
| [OptimizationOptions](./optimizationoptions/#constructor) | Initializes a new instance of the OptimizationOptions class. |

## Properties

| Name | Description |
| --- | --- |
| [AllowReusePageContent](./allowreusepagecontent/) { get; set; } | If true page contents will be reused when document is optimized for equal pages. |
| [CompressAllContentStreams](./compressallcontentstreams/) { get; set; } | If set to , all uncompressed page content streams will be. |
| [CompressImages](./compressimages/) { get; set; } | If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property. |
| [CompressObjects](./compressobjects/) { get; set; } | If this flag is set to , Pdf objects will be packed into Objest Streams. |
| [ImageCompressionOptions](./imagecompressionoptions/) { get; } | Set of options which describe will images in the document be compressed and parameters of the compression. |
| [ImageEncoding](./imageencoding/) { get; set; } | Image encodre which will be used. |
| [ImageQuality](./imagequality/) { get; set; } | Specifies level of image compression when CompressIamges flag is used. |
| [LinkDuplicateStreams](./linkduplicatestreams/) { get; set; } | If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then thes streams will be stored as one object. |
| [MaxResoultion](./maxresoultion/) { get; set; } | Specifies maximum resolution of images. If image has higher resolition it will be scaled. |
| [RemovePrivateInfo](./removeprivateinfo/) { get; set; } | Remove private information (page piece info). |
| [RemoveUnusedObjects](./removeunusedobjects/) { get; set; } | If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document. |
| [RemoveUnusedStreams](./removeunusedstreams/) { get; set; } | If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. |
| [ResizeImages](./resizeimages/) { get; set; } | If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter. |
| [SubsetFonts](./subsetfonts/) { get; set; } | Fonts will be converted into subsets if set to true. |
| [UnembedFonts](./unembedfonts/) { get; set; } | Make fonts not embedded if set to true. |

## Methods

| Name | Description |
| --- | --- |
| [All](./all/) | Creates optimization strategy will all options activated. |

### See Also

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)

