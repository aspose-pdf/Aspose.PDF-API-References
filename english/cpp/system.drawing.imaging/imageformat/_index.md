---
title: System::Drawing::Imaging::ImageFormat class
linktitle: ImageFormat
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::ImageFormat class. Represents the file format of an image. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1100
url: /cpp/system.drawing.imaging/imageformat/
---
## ImageFormat class


Represents the file format of an image. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ImageFormat : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(ImageFormatPtr) const | Determines if the image formats represented by the current and specified objects are equal. |
| static [get_Bmp](./get_bmp/)() | Returns a shared pointer to an [ImageFormat](./) object that represents the bitmap image format. |
| static [get_Emf](./get_emf/)() | Returns a shared pointer to an [ImageFormat](./) object that represents the enhanced metafile format. |
| static [get_Exif](./get_exif/)() | Returns a shared pointer to an [ImageFormat](./) object that represents the Exchangeable [Image](../../system.drawing/image/) File (Exif) format. |
| static [get_Gif](./get_gif/)() | Returns a shared pointer to an [ImageFormat](./) object that represents the [Graphics](../../system.drawing/graphics/) Interchange Format (GIF) image format. |
| [get_Guid](./get_guid/)() const | Returns the GUID associated with the image format represented by the current object. |
| static [get_Icon](./get_icon/)() | Returns a shared pointer to an [ImageFormat](./) object that represents the [Windows](../../system.windows/) icon image format. |
| static [get_Jpeg](./get_jpeg/)() | Returns a shared pointer to an [ImageFormat](./) object that represents the Joint Photographic Experts Group (JPEG) image format. |
| static [get_MemoryBmp](./get_memorybmp/)() | Returns a shared pointer to an [ImageFormat](./) object that represents the format of a bitmap in memory. |
| static [get_Png](./get_png/)() | Returns a shared pointer to an [ImageFormat](./) object that represents the W3C Portable Network [Graphics](../../system.drawing/graphics/) (PNG) image format. |
| static [get_Tiff](./get_tiff/)() | Returns a shared pointer to an [ImageFormat](./) object that represents the Tagged [Image](../../system.drawing/image/) File Format (TIFF) image format. |
| static [get_Wmf](./get_wmf/)() | Returns a shared pointer to an [ImageFormat](./) object that represents the [Windows](../../system.windows/) metafile (WMF) image format. |
| [ImageFormat](./imageformat/)(const System::Guid\&) | Constructs an instance of [ImageFormat](./) class that represents an image format format associated with the specified GUID. |
| virtual [ToString](./tostring/)() const | Converts this [ImageFormat](./) object to a human-readable string. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
