---
title: Class ImagePlacement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImagePlacement class. Represents characteristics of an image placed to Pdf document page
type: docs
weight: 3840
url: /net/aspose.pdf/imageplacement/
---
## ImagePlacement class

Represents characteristics of an image placed to Pdf document page.

```csharp
public sealed class ImagePlacement
```

## Properties

| Name | Description |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | Gets compositing parameters of graphics state active for the image placed to the page. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | Gets related XImage resource object. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | Current transformation matrix for this image. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | Operator used for displaying the image. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | Gets the page containing the image. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | Gets rectangle of the Image. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | Gets resolution of the Image. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | Gets rotation angle of the Image. |

## Methods

| Name | Description |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | Delete image from the page. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | Replace image in collection with another image. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | Saves image with corresponding transformations: scaling, rotation and resolution. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | Saves image with corresponding transformations: scaling, rotation and resolution. |

## Remarks

When an image is placed to a page it may have dimensions other than physical dimensions defined in [`Resources`](../resources/). The object `ImagePlacement` is intended to provide such information like dimensions, resolution and so on.

## Examples

The example demonstrates how to find images on the first PDF document page and get images as bitmaps with visible dimensions.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Retrieve images with visible dimensions
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Retrieve image from resources
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Create new bitmap with actual dimensions
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


