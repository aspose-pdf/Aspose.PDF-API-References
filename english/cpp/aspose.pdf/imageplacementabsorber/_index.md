---
title: Aspose::Pdf::ImagePlacementAbsorber class
linktitle: ImagePlacementAbsorber
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ImagePlacementAbsorber class. Represents an absorber object of image placement objects. Performs search of image usages and provides access to search results via ImagePlacementAbsorber::ImagePlacements collection in C++.'
type: docs
weight: 8300
url: /cpp/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber class


Represents an absorber object of image placement objects. Performs search of image usages and provides access to search results via [ImagePlacementAbsorber::ImagePlacements](../) collection.

```cpp
class ImagePlacementAbsorber : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_ImagePlacements](./get_imageplacements/)() const | Gets collection of image placement occurrences that are presented with [ImagePlacement](../imageplacement/) objects. |
| [get_IsReadOnlyMode](./get_isreadonlymode/)() const | Gets/sets read only mode for parsing operations collection. It may help against out of memory exceptions. |
| [ImagePlacementAbsorber](./imageplacementabsorber/)() | Initializes new instance of the [ImagePlacementAbsorber](./) object. |
| [set_IsReadOnlyMode](./set_isreadonlymode/)(bool) | Gets/sets read only mode for parsing operations collection. It may help against out of memory exceptions. |
| [Visit](./visit/)(const System::SharedPtr\<Page\>\&) | Performs search on the specified page. |
| [Visit](./visit/)(const System::SharedPtr\<Document\>\&) | Performs search on the specified document. |
## Remarks


The [ImagePlacementAbsorber](./) object is basically used in images search scenario. When the search is completed the occurrences are represented with [ImagePlacement](../imageplacement/) objects that the [ImagePlacementAbsorber::ImagePlacements](../) collection contains. The [ImagePlacement](../imageplacement/) object provides access to the image placement properties: dimensions, resolution etc. [Image](../image/) positive rotation is counterclockwise, for the page, it is clockwise. Here, we need to represent the image rotation angle, so we deduct the page angle from the image angle. 
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
