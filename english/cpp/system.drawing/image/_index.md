---
title: System::Drawing::Image class
linktitle: Image
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Image class. A base class for System::Drawing::Bitmap and System::Drawing::Metafile classes providing basic functionality. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1200
url: /cpp/system.drawing/image/
---
## Image class


A base class for [System::Drawing::Bitmap](../bitmap/) and System::Drawing::Metafile classes providing basic functionality. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Image : public virtual System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Clone](./clone/)() | Creates a copy of the current object. |
| [Dispose](./dispose/)() override | Releases all resources aquired by the current object. |
| static [FromFile](./fromfile/)(const String\&, bool) | Creates an [Image](./) object from the specified file. |
| static [FromHbitmap](./fromhbitmap/)(IntPtr) | Constructs a [Bitmap](../bitmap/) object from the specified GDI bitmap. |
| static [FromStream](./fromstream/)(const SharedPtr\<System::IO::Stream\>\&, bool, bool) | Creates an [Image](./) object from the specified stream. |
| virtual [get_Flags](./get_flags/)() const | Returns a bit-wise combination of ImageFlags enum values that represents the attributes of the image. |
| [get_FrameDimensionsList](./get_framedimensionslist/)() const | Returns an array of GUIDs that represent the dimensions of frames within the image represented by the current object. |
| virtual [get_Height](./get_height/)() const | Returns the height of the image in pixels. |
| [get_HorizontalResolution](./get_horizontalresolution/)() const | Returns the horizontal resolution of the image represented by the current object in pixels per inch. |
| virtual [get_Palette](./get_palette/)() const | Returns the color palette used by the image represented by the current object. |
| virtual [get_PixelFormat](./get_pixelformat/)() const | Returns the pixel format of the image represented by the current object. |
| virtual [get_PropertyIdList](./get_propertyidlist/)() const | Gets IDs of the property items stored in this image. |
| virtual [get_PropertyItems](./get_propertyitems/)() const | Gets all the property items(pieces of metadata) stored in this image. |
| virtual [get_RawFormat](./get_rawformat/)() const | Returns the file format of the image represented by the current object. |
| [get_Size](./get_size/)() const | Returns a [Size](../size/) object that represents the width and height of the image in pixels. |
| virtual [get_Tag](./get_tag/)() const | Gets an object that provides additional data about the image. |
| [get_VerticalResolution](./get_verticalresolution/)() const | Returns the vertical resolution of the image represented by the current object in pixels per inch. |
| virtual [get_Width](./get_width/)() const | Returns the width of the image in pixels. |
| [GetBounds](./getbounds/)(GraphicsUnit\&) | Returns the image bounds in the specified measurement units. |
| [GetFrameCount](./getframecount/)(const Imaging::FrameDimensionPtr\&) | Returns the number of frames of the specified frame dimension. |
| static [GetPixelFormatSize](./getpixelformatsize/)(Imaging::PixelFormat) | Returns the number of bits used to represent the color depth in the specified pixel format. |
| virtual [GetSkBitmap](./getskbitmap/)() const | Returns an underlying SkBitmap object. |
| [GetThumbnailImage](./getthumbnailimage/)(int, int, Image::GetThumbnailImageAbort, IntPtr) | Gets a thumbnail for this [System::Drawing::Image](./) object. |
| static [IsAlphaPixelFormat](./isalphapixelformat/)(Imaging::PixelFormat) | Determines if the specified pixel format contains alpha information. |
| virtual [IsMultiImage](./ismultiimage/)() const | Returns whether the original format is a multi-image. |
| virtual [RotateFlip](./rotateflip/)(RotateFlipType) | Rotate image to multiple of 90 degrees and flip. |
| [Save](./save/)(const String\&) | Saves the image represented by the current object to the specified file in PNG format. |
| [Save](./save/)(const String\&, const Imaging::ImageFormatPtr\&) | Saves the image represented by the current object to the specified file in the specified format. |
| [Save](./save/)(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) | Saves the image represented by the current object to the specified stream in the specified format. |
| [Save](./save/)(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) | Saves the image represented by the current object to the specified file using the specified encoder and encoder parameters. |
| [Save](./save/)(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) | Saves the image represented by the current object to the specified stream using the specified encoder and encoder parameters. |
| [SaveAdd](./saveadd/)(const Imaging::EncoderParametersPtr\&) | Adds a frame to the file or stream specified in a previous call to the [Save()](./save/) method. |
| [SaveAdd](./saveadd/)(const SharedPtr\<Image\>\&, const Imaging::EncoderParametersPtr\&) | Adds a frame to the file or stream specified in a previous call to the [Save()](./save/) method. |
| [SelectActiveFrame](./selectactiveframe/)(const Imaging::FrameDimensionPtr\&, int) | Selects the specified frame. |
| virtual [set_Palette](./set_palette/)(Imaging::ColorPalettePtr) | Sets the color palette used by the image represented by the current object. |
| virtual [set_Tag](./set_tag/)(const System::SharedPtr\<System::Object\>) | Sets an object that provides additional data about the image. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [GetThumbnailImageAbort](./getthumbnailimageabort/) | A callback to cancel GetThumbnailImage execution. |
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
