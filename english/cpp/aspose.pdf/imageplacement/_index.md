---
title: Aspose::Pdf::ImagePlacement class
linktitle: ImagePlacement
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::ImagePlacement class. Represents characteristics of an image placed to Pdf document page in C++.'
type: docs
weight: 8200
url: /cpp/aspose.pdf/imageplacement/
---
## ImagePlacement class


Represents characteristics of an image placed to [Pdf](../) document page.

```cpp
class ImagePlacement : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_CompositingParameters](./get_compositingparameters/)() const | Gets compositing parameters of graphics state active for the image placed to the page. |
| [get_Image](./get_image/)() const | Gets related [XImage](../ximage/) resource object. |
| [get_Matrix](./get_matrix/)() const | Current transformation matrix for this image. |
| [get_Operator](./get_operator/)() const | [Operator](../operator/) used for displaying the image. |
| [get_Page](./get_page/)() const | Gets the page containing the image. |
| [get_Rectangle](./get_rectangle/)() const | Gets rectangle of the [Image](../image/). |
| [get_Resolution](./get_resolution/)() const | Gets resolution of the [Image](../image/). |
| [get_Rotation](./get_rotation/)() const | Gets rotation angle of the [Image](../image/). |
| [Hide](./hide/)() | Delete image from the page. |
| [Replace](./replace/)(const System::SharedPtr\<System::IO::Stream\>\&) | Replace image in collection with another image. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&) | Saves image with corresponding transformations: scaling, rotation and resolution. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Saves image with corresponding transformations: scaling, rotation and resolution. |
## Remarks


When an image is placed to a page it may have dimensions other than physical dimensions defined in [Resources](../resources/). The object [ImagePlacement](./) is intended to provide such information like dimensions, resolution and so on. 
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
