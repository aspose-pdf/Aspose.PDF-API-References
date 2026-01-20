---
title: Aspose::Pdf::Image class
linktitle: Image
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Image class. Represents image in C++.'
type: docs
weight: 7900
url: /cpp/aspose.pdf/image/
---
## Image class


Represents image.

```cpp
class Image : public Aspose::Pdf::BaseParagraph
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Clone the image. |
| [get_BitmapInfo](./get_bitmapinfo/)() const | Gets uncompressed image bytes. |
| [get_BitmapSize](./get_bitmapsize/)() | Gets the image bitmap size. |
| [get_File](./get_file/)() const | Gets the image file. |
| [get_FileType](./get_filetype/)() const | Gets the image file type. |
| [get_FixHeight](./get_fixheight/)() const | Gets the image height. |
| [get_FixWidth](./get_fixwidth/)() const | Gets the image width. |
| [get_ImageScale](./get_imagescale/)() const | Gets the image scale. |
| [get_ImageStream](./get_imagestream/)() const | Gets the image stream. |
| [get_IsApplyResolution](./get_isapplyresolution/)() const | Gets a bool value that indicates whether the image use resolution during generation. |
| [get_IsBlackWhite](./get_isblackwhite/)() const | Gets a bool value that indicates whether the image is forced to be black-and-white. If TIFF image of CCITT subformat is used, this property must be set to true. |
| [get_Title](./get_title/)() const | Gets a string value that indicates the title of the image. |
| static [GetMimeType](./getmimetype/)(System::SharedPtr\<System::Drawing::Image\>) | Returns mime type for image. |
| [Image](./image/)() |  |
| [set_BitmapInfo](./set_bitmapinfo/)(System::SharedPtr\<Aspose::Pdf::BitmapInfo\>) | Sets uncompressed image bytes. |
| [set_File](./set_file/)(System::String) | Sets the image file. |
| [set_FileType](./set_filetype/)(ImageFileType) | Sets the image file type. |
| [set_FixHeight](./set_fixheight/)(double) | Sets the image height. |
| [set_FixWidth](./set_fixwidth/)(double) | Sets the image width. |
| [set_ImageScale](./set_imagescale/)(double) | Sets the image scale. |
| [set_ImageStream](./set_imagestream/)(System::SharedPtr\<System::IO::Stream\>) | Sets the image stream. |
| [set_IsApplyResolution](./set_isapplyresolution/)(bool) | Sets a bool value that indicates whether the image use resolution during generation. |
| [set_IsBlackWhite](./set_isblackwhite/)(bool) | Sets a bool value that indicates whether the image is forced to be black-and-white. If TIFF image of CCITT subformat is used, this property must be set to true. |
| [set_Title](./set_title/)(System::SharedPtr\<Text::TextFragment\>) | Sets a string value that indicates the title of the image. |
## See Also

* Class [BaseParagraph](../baseparagraph/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
