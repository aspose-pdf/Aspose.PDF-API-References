---
title: Class ImagesDifference
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.GraphicalComparison.ImagesDifference class. Represents the result class of comparing two PDF pages
type: docs
weight: 1800
url: /net/aspose.pdf.comparison.graphicalcomparison/imagesdifference/
---
## ImagesDifference class

Represents the result class of comparing two PDF pages.

```csharp
public sealed class ImagesDifference : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Difference](../../aspose.pdf.comparison.graphicalcomparison/imagesdifference/difference/) { get; } | Gets the difference array. This array is similar to the original image data array obtained as a result of the LockBits method. |
| [Height](../../aspose.pdf.comparison.graphicalcomparison/imagesdifference/height/) { get; } | The height of difference. |
| [SourceImage](../../aspose.pdf.comparison.graphicalcomparison/imagesdifference/sourceimage/) { get; } | Gets the image of first compared page. The image has a pixel format is 24bpp. |
| [Stride](../../aspose.pdf.comparison.graphicalcomparison/imagesdifference/stride/) { get; } | The stride of difference image data. |

## Methods

| Name | Description |
| --- | --- |
| [DifferenceToImage](../../aspose.pdf.comparison.graphicalcomparison/imagesdifference/differencetoimage/)(Color, Color) | Converts the difference array to a bitmap image using the specified colors. |
| [Dispose](../../aspose.pdf.comparison.graphicalcomparison/imagesdifference/dispose/)() | Performs any necessary clean up operations before the object is destroyed. |
| [GetDestinationImage](../../aspose.pdf.comparison.graphicalcomparison/imagesdifference/getdestinationimage/)() | Returns a new bitmap representing the destination image by applying the difference array to the source image. |

### See Also

* namespace [Aspose.Pdf.Comparison.GraphicalComparison](../../aspose.pdf.comparison.graphicalcomparison/)
* assembly [Aspose.PDF](../../)


