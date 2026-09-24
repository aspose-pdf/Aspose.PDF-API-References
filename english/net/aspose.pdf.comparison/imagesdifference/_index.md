---
title: "ImagesDifference Class"
linktitle: "ImagesDifference"
articleTitle: "ImagesDifference"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Comparison.ImagesDifference class. Represents the result class of comparing two PDF pages."
type: docs
weight: 120
url: "/net/aspose.pdf.comparison/imagesdifference/"
keywords: "ImagesDifference, Aspose.Pdf.Comparison, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ImagesDifference class

Represents the result class of comparing two PDF pages.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Difference](./difference/) { get; } | Gets the difference array. |
| [Height](./height/) { get; } | The height of difference. |
| [SourceImage](./sourceimage/) { get; } | Gets the image of first compared page. The image has a pixel format is 24bpp. |
| [Stride](./stride/) { get; } | The stride of difference image data. |

## Methods

| Name | Description |
| --- | --- |
| [DifferenceToImage](./differencetoimage/)(*Color, Color*) | Converts the difference array to a bitmap image using the specified colors. |
| [Dispose](./dispose/) | Performs any necessary clean up operations before the object is destroyed. |
| [GetDestinationImage](./getdestinationimage/) | Returns a new bitmap representing the destination image by applying the difference array to the source image. |

### See Also

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)

