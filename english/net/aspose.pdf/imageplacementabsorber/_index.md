---
title: "ImagePlacementAbsorber Class"
linktitle: "ImagePlacementAbsorber"
articleTitle: "ImagePlacementAbsorber"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.ImagePlacementAbsorber class. Represents an absorber object of image placement objects. Performs search of image usages and provides access to sea..."
type: docs
weight: 1540
url: "/net/aspose.pdf/imageplacementabsorber/"
keywords: "ImagePlacementAbsorber, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ImagePlacementAbsorber class

Represents an absorber object of image placement objects.
 Performs search of image usages and provides access to search results via `ImagePlacements` collection.

```csharp
public sealed class ImagePlacementAbsorber
```

## Constructors

| Name | Description |
| --- | --- |
| [ImagePlacementAbsorber](./imageplacementabsorber/#constructor) | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ImagePlacements](./imageplacements/) { get; } | Gets collection of image placement occurrences that are presented with [`ImagePlacement`](../../aspose.pdf/imageplacement/) objects. |
| [IsReadOnlyMode](./isreadonlymode/) { get; set; } | Gets/sets read only mode for parsing operations collection. It may help against out of memory. |

## Methods

| Name | Description |
| --- | --- |
| [Visit](./visit/)(*Page*) | Performs search on the specified page. |
| [Visit](./visit/)(*Document*) | Performs search on the specified document. |

## Remarks

The [`ImagePlacementAbsorber`](../../aspose.pdf/imageplacementabsorber/) object is basically used in images search scenario.
 When the search is completed the occurrences are represented with [`ImagePlacement`](../../aspose.pdf/imageplacement/) objects that the `ImagePlacements` collection contains.
 The [`ImagePlacement`](../../aspose.pdf/imageplacement/) object provides access to the image placement properties: dimensions, resolution etc.
 Image positive rotation is counterclockwise, for the page, it is clockwise.
 Here, we need to represent the image rotation angle, so we deduct the page angle from the image angle.

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

