---
title: "Document.OptimizationOptions Class"
linktitle: "Document.OptimizationOptions"
articleTitle: "Document.OptimizationOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Document.OptimizationOptions class. Class which describes document optimization algorithm. Instance of this class may be used as parameter of Opti..."
type: docs
weight: 670
url: "/net/aspose.pdf/document.optimizationoptions/"
keywords: "Document.OptimizationOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Document.OptimizationOptions class

> **Deprecated.** This class is obsolete. Please use Aspose.Pdf.Optimization.OptimizationOptions instead.

Class which describes document optimization algorithm.
 Instance of this class may be used as parameter of OptimizeResources() method.

```csharp
public class OptimizationOptions : OptimizationOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [Document.OptimizationOptions](./optimizationoptions/#constructor) | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | If true page contents will be reused when document is optimized for equal pages. *(Inherited from OptimizationOptions)* |
| [CompressAllContentStreams](../../aspose.pdf.optimization/optimizationoptions/compressallcontentstreams/) { get; set; } | If set to , all uncompressed page content streams will be. *(Inherited from OptimizationOptions)* |
| [CompressImages](../../aspose.pdf.optimization/optimizationoptions/compressimages/) { get; set; } | If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property. *(Inherited from OptimizationOptions)* |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | If this flag is set to , Pdf objects will be packed into Objest Streams. *(Inherited from OptimizationOptions)* |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Set of options which describe will images in the document be compressed and parameters of the compression. *(Inherited from OptimizationOptions)* |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Image encodre which will be used. *(Inherited from OptimizationOptions)* |
| [ImageQuality](../../aspose.pdf.optimization/optimizationoptions/imagequality/) { get; set; } | Specifies level of image compression when CompressIamges flag is used. *(Inherited from OptimizationOptions)* |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then thes streams will be stored as one object. *(Inherited from OptimizationOptions)* |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Specifies maximum resolution of images. If image has higher resolition it will be scaled. *(Inherited from OptimizationOptions)* |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Remove private information (page piece info). *(Inherited from OptimizationOptions)* |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document. *(Inherited from OptimizationOptions)* |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. *(Inherited from OptimizationOptions)* |
| [ResizeImages](../../aspose.pdf.optimization/optimizationoptions/resizeimages/) { get; set; } | If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter. *(Inherited from OptimizationOptions)* |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | Fonts will be converted into subsets if set to true. *(Inherited from OptimizationOptions)* |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Make fonts not embedded if set to true. *(Inherited from OptimizationOptions)* |

## Methods

| Name | Description |
| --- | --- |
| [All](./all/) | Creates optimization strategy will all options activated. |

### See Also

* class [Document](../document/)
* class [OptimizationOptions](../../aspose.pdf.optimization/optimizationoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

