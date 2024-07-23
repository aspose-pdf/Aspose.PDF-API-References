---
title: Class ImagePlacementAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImagePlacementAbsorber class. Represents an absorber object of image placement objects. Performs search of image usages and provides access to search results via ImagePlacements collection
type: docs
weight: 4250
url: /net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber class

Represents an absorber object of image placement objects. Performs search of image usages and provides access to search results via [`ImagePlacements`](./imageplacements/) collection.

```csharp
public sealed class ImagePlacementAbsorber
```

## Constructors

| Name | Description |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | Gets collection of image placement occurrences that are presented with [`ImagePlacement`](../imageplacement/) objects. |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | Gets/sets read only mode for parsing operations collection. It may help against out of memory exceptions. |

## Methods

| Name | Description |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | Performs search on the specified document. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | Performs search on the specified page. |

## Remarks

The `ImagePlacementAbsorber` object is basically used in images search scenario. When the search is completed the occurrences are represented with [`ImagePlacement`](../imageplacement/) objects that the [`ImagePlacements`](./imageplacements/) collection contains. The [`ImagePlacement`](../imageplacement/) object provides access to the image placement properties: dimensions, resolution etc. Image positive rotation is counterclockwise, for the page, it is clockwise. Here, we need to represent the image rotation angle, so we deduct the page angle from the image angle.

## Examples

The example demonstrates how to find images on the first PDF document page and get the image placement properties.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Display image placement properties for all placements
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{     
    Console.Out.WriteLine("image width:" + imagePlacement.Rectangle.Width);
    Console.Out.WriteLine("image height:" + imagePlacement.Rectangle.Height);
    Console.Out.WriteLine("image LLX:" + imagePlacement.Rectangle.LLX);
    Console.Out.WriteLine("image LLY:" + imagePlacement.Rectangle.LLY);
    Console.Out.WriteLine("image horizontal resolution:" + imagePlacement.Resolution.X);
    Console.Out.WriteLine("image vertical resolution:" + imagePlacement.Resolution.Y);
}
```

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


