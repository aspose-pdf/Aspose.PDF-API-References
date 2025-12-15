---
title: Aspose::Pdf::XImage class
linktitle: XImage
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XImage class. Class representing image X-Object in C++.'
type: docs
weight: 19600
url: /cpp/aspose.pdf/ximage/
---
## XImage class


Class representing image X-Object.

```cpp
class XImage : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [AddStencilMask](./addstencilmask/)(const System::SharedPtr\<System::IO::Stream\>\&) | Adds a stencil mask to the [XImage](./). |
| static [DetectColorType](./detectcolortype/)(const System::SharedPtr\<System::Drawing::Bitmap\>\&) | Returns color type of image. |
| [get_ContainsTransparency](./get_containstransparency/)() | If the image contains transparancy than return true; otherwise, false. |
| [get_FilterType](./get_filtertype/)() | Gets image filter type. |
| [get_Grayscaled](./get_grayscaled/)() | Gets grayscaled version of image. |
| [get_Height](./get_height/)() | Gets height of the image. |
| [get_ImageMask](./get_imagemask/)() | Gets a flag indicating whether the image shall be treated as an image mask (see 8.9.6, "Masked Images"). If this flag is true, the value of BitsPerComponent shall be 1 and Mask and [ColorSpace](../colorspace/) shall not be specified; unmasked areas shall bepainted using the current nonstroking colour. Default value: false. |
| [get_Metadata](./get_metadata/)() | [Metadata](../metadata/) of the image. |
| [get_Name](./get_name/)() | Gets image name. Please note that if you change name of the image which has references in page contents, document may became incorrect. Please use [XImage.Rename](./rename/) method in this case. |
| [get_Width](./get_width/)() | Gets width of the image. |
| [GetAlternativeText](./getalternativetext/)(System::SharedPtr\<Aspose::Pdf::Page\>) | Returns a list of strings with Alternative [Text](../../aspose.pdf.text/) for an [XImage](./). |
| [GetColorType](./getcolortype/)() | Returns color type of image. |
| [GetNameInCollection](./getnameincollection/)() | Returns the name of the image in its collection. |
| [GetRawImageData](./getrawimagedata/)() | Retrieves the raw image data from the source image. |
| [IsTheSameObject](./isthesameobject/)(System::SharedPtr\<Aspose::Pdf::XImage\>) | Returns true if both images references to the same object. |
| [Rename](./rename/)(const System::String\&) | Renames image and replaces all references to the image with the new name. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&) | Saves image data into stream as JPEG image. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) | Saves image into stream with requested format. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) | Saves image data into stream as JPEG image with specified resolution. |
| [Save](./save/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&, int32_t) | Saves image into stream with requested format with specified resolution. |
| [set_Name](./set_name/)(System::String) | Sets image name. Please note that if you change name of the image which has references in page contents, document may became incorrect. Please use [XImage.Rename](./rename/) method in this case. |
| [ToStream](./tostream/)() | Returns the original image stream. |
| [TrySetAlternativeText](./trysetalternativetext/)(System::String, System::SharedPtr\<Aspose::Pdf::Page\>) | Sets alternative text for an [XImage](./) on the page. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
