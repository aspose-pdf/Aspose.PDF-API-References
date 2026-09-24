---
title: "ImagePlacement Class"
linktitle: "ImagePlacement"
articleTitle: "ImagePlacement"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.ImagePlacement class. Represents characteristics of an image placed to Pdf document page."
type: docs
weight: 1530
url: "/net/aspose.pdf/imageplacement/"
keywords: "ImagePlacement, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ImagePlacement class

Represents characteristics of an image placed to Pdf document page.

```csharp
public sealed class ImagePlacement
```

## Properties

| Name | Description |
| --- | --- |
| [CompositingParameters](./compositingparameters/) { get; } | Gets compositing parameters of graphics state active for the image placed to the page. |
| [Image](./image/) { get; } | Gets related XImage resource object. |
| [Matrix](./matrix/) { get; } | Current transformation matrix for this image. |
| [Operator](./operator/) { get; } | Operator used for displaying the image. |
| [Page](./page/) { get; } | Gets the page containing the image. |
| [Rectangle](./rectangle/) { get; } | Gets rectangle of the Image. |
| [Resolution](./resolution/) { get; } | Gets resolution of the Image. |
| [Rotation](./rotation/) { get; } | Gets rotation angle of the Image. |

## Methods

| Name | Description |
| --- | --- |
| [Hide](./hide/) | Delete image from the page. |
| [Replace](./replace/)(*Stream*) | Replace image in collection with another image. |
| [Save](./save/)(*Stream*) | Saves image with corresponding transformations: scaling, rotation and resolution. |
| [Save](./save/)(*Stream, ImageFormat*) | Saves image with corresponding transformations: scaling, rotation and resolution. |

## Remarks

When an image is placed to a page it may have dimensions other than physical dimensions defined in [`Resources`](../../aspose.pdf/resources/).
 The object [`ImagePlacement`](../../aspose.pdf/imageplacement/) is intended to provide such information like dimensions, resolution and so on.

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

