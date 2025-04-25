---
title: Class ImageCompressionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Optimization.ImageCompressionOptions class. Class contains set options for image compression
type: docs
weight: 8070
url: /net/aspose.pdf.optimization/imagecompressionoptions/
---
## ImageCompressionOptions class

Class contains set options for image compression.

```csharp
public class ImageCompressionOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageCompressionOptions](imagecompressionoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [CompressImages](../../aspose.pdf.optimization/imagecompressionoptions/compressimages/) { get; set; } | If this flag is set to true images will be compressed in the document. Compression level is specified with ImageQuality property. |
| [Encoding](../../aspose.pdf.optimization/imagecompressionoptions/encoding/) { get; set; } | Gets or sets encoding used to store images. |
| [ImageQuality](../../aspose.pdf.optimization/imagecompressionoptions/imagequality/) { get; set; } | Specifies level of image compression when CompressImages flag is used. |
| [MaxResolution](../../aspose.pdf.optimization/imagecompressionoptions/maxresolution/) { get; set; } | Specifies maximum resolution of images. If image has higher resolution it will be scaled |
| [ResizeImages](../../aspose.pdf.optimization/imagecompressionoptions/resizeimages/) { get; set; } | If this flag set to true and CompressImages is true images will be resized if image resolution is greater then specified MaxResolution parameter. |
| [Version](../../aspose.pdf.optimization/imagecompressionoptions/version/) { get; set; } | Version of compression algorithm. Possible values are: 1. standard compression, 2. fast (improved compression which is faster then standard but may be applicable not for all images), 3. mixed (standard compression is applied to images which can not be compressed by faster algorithm, this may give best compression but more slow then "fast" algorithm. Version "Fast" is not applicable for resizing images (standard method will be used). Default is "Standard". |

### See Also

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


