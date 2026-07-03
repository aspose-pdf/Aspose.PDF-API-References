---
title: ImagePlacementAbsorber
linktitle: ImagePlacementAbsorber
second_title: Aspose.PDF for Java API Reference
description: <p> Represents an absorber object of image placement objects. Performs search of image usages and provides access to search results via {@code.
type: docs
weight: 2340
url: /java/com.aspose.pdf/imageplacementabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacementAbsorber

```
public final class ImagePlacementAbsorber extends Object
```

<p> Represents an absorber object of image placement objects. Performs search of image usages and provides access to search results via {@code ImagePlacementAbsorber.ImagePlacements} collection. </p> <hr> <pre> The example demonstrates how to find images on the first PDF document page and get the image placement properties. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle.getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> The {@code ImagePlacementAbsorber} object is basically used in images search scenario. When the search is completed the occurrences are represented with {@code ImagePlacement} objects that the {@code ImagePlacementAbsorber.ImagePlacements} collection contains. The {@code ImagePlacement} object provides access to the image placement properties: dimensions, resolution etc. </p> Image positive rotation is counterclockwise, for the page, it is clockwise. Here, we need to represent the image rotation angle, so we deduct the page angle from the image angle.

## Constructors

| Constructor | Description |
| --- | --- |
| [ImagePlacementAbsorber](#ImagePlacementAbsorber--) | Initializes new instance of the {@code ImagePlacementAbsorber} object. |

## Methods

| Method | Description |
| --- | --- |
| [getImagePlacements](#getImagePlacements--) | Gets collection of image placement occurrences that are presented with {@code ImagePlacement} objects. |
| [isReadOnlyMode](#isReadOnlyMode--) | Gets/sets read only mode for parsing operations collection. It may help against out of memory exceptions. |
| [setReadOnlyMode](#setReadOnlyMode-boolean-) | Gets/sets read only mode for parsing operations collection. It may help against out of memory exceptions. |
| [visit](#visit-com.aspose.pdf.IDocument-) | Performs search on the specified document. |
| [visit](#visit-com.aspose.pdf.Page-) | Performs search on the specified page. |

### ImagePlacementAbsorber {#ImagePlacementAbsorber--}
```
public ImagePlacementAbsorber()
```

Initializes new instance of the {@code ImagePlacementAbsorber} object.

### getImagePlacements {#getImagePlacements--}
```
public ImagePlacementCollection getImagePlacements()
```

Gets collection of image placement occurrences that are presented with {@code ImagePlacement} objects.

**Returns:**
ImagePlacementCollection object

### isReadOnlyMode {#isReadOnlyMode--}
```
public final boolean isReadOnlyMode()
```

Gets/sets read only mode for parsing operations collection. It may help against out of memory exceptions.

**Returns:**
boolean value

### setReadOnlyMode {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```

Gets/sets read only mode for parsing operations collection. It may help against out of memory exceptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### visit {#visit-com.aspose.pdf.IDocument-}
Performs search on the specified document.

### visit {#visit-com.aspose.pdf.Page-}
Performs search on the specified page.
