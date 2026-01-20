---
title: System::Drawing::Bitmap class
linktitle: Bitmap
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Bitmap class. Represents a GDI+ bitmap image. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.drawing/bitmap/
---
## Bitmap class


Represents a GDI+ bitmap image. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Bitmap : public System::Drawing::Image
```

## Methods

| Method | Description |
| --- | --- |
| [BeginPixelProcessing](./beginpixelprocessing/)(bool) | Enables pixel processing mode. |
| [Bitmap](./bitmap/)(const SharedPtr\<Image\>\&) | Constructs a new [Bitmap](./) object from the specified existing image. |
| [Bitmap](./bitmap/)(const SharedPtr\<System::IO::Stream\>\&, bool) | Constructs a new [Bitmap](./) object from the specified stream. |
| [Bitmap](./bitmap/)(const String\&) | Constructs a new [Bitmap](./) object from the specified file. |
| [Bitmap](./bitmap/)(const String\&, bool) | Constructs a new [Bitmap](./) object from the specified file. |
| [Bitmap](./bitmap/)(int, int, Imaging::PixelFormat) | Constructs a new [Bitmap](./) object that represents a bitmap image with the specified width, height, pixel format and pixel data. |
| [Bitmap](./bitmap/)(const SharedPtr\<Image\>\&, const Size\&) | Constructs a new [Bitmap](./) object from the specified existing image, scaled to the specified size. |
| [Bitmap](./bitmap/)(const SharedPtr\<Image\>\&, int, int) | Constructs a new [Bitmap](./) object from the specified existing image with width and height scaled to the specified values. |
| [Clone](./clone/)() override | Creates a copy of the current object. |
| [Clone](./clone/)(Rectangle, Imaging::PixelFormat) | Creates a [Bitmap](./) object that represents a copy of a region of the bitmap image represented by the current object. |
| [Clone](./clone/)(RectangleF, Imaging::PixelFormat) | Creates a [Bitmap](./) object that represents a copy of a region of the bitmap image represented by the current object. |
| [ComputeHash](./computehash/)() | Computes the SHA1 hash value. |
| static [ConvertToARGBImage](./converttoargbimage/)(const SharedPtr\<Bitmap\>\&) | Creates a copy of the specified bitmap image with pixel format changed to Format32bppArgb. |
| [EndPixelProcessing](./endpixelprocessing/)(bool) | Disables pixel processing mode. |
| [get_Height](./get_height/)() const override | Returns the height of the image in pixels. |
| [get_Palette](./get_palette/)() const override | Returns the color palette used by the image represented by the current object. |
| [get_PixelFormat](./get_pixelformat/)() const override | Returns the pixel format of the image represented by the current object. |
| [get_RawFormat](./get_rawformat/)() const override | Returns the file format of the image represented by the current object. |
| [get_Width](./get_width/)() const override | Returns the width of the image in pixels. |
| [GetHbitmap](./gethbitmap/)() | Creates a GDI bitmap object from the bitmap represented by the current object. |
| [GetPixel](./getpixel/)(int, int) | Returns the color of the specified pixel. |
| [GetSkBitmap](./getskbitmap/)() const override | Returns a raw pointer to the underlying SkBitmap object. |
| [IsMultiImage](./ismultiimage/)() const override | Returns whether the original format is a multi-image. |
| [LockBits](./lockbits/)(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) | Locks a [Bitmap](./) into system memory. |
| [LockBits](./lockbits/)(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) | Locks a [Bitmap](./) into system memory. |
| [MakeTransparent](./maketransparent/)(Color) | Changes the color of all pixels with the specified color to transparent. |
| [MEMBER_FUNCTION_MAKE_OBJECT](./member_function_make_object/)(Bitmap, CODEPORTING_ARGS(const SharedPtr\<Image\>\&original, int width, int height), CODEPORTING_ARGS(original, width, height)) |  |
| [PremultipleColors](./premultiplecolors/)() | Premultiplies the colors of the pixels of the image represented by the current object. |
| [RotateFlip](./rotateflip/)(RotateFlipType) override | Rotates image to multiple of 90 degrees and flips. |
| [set_Palette](./set_palette/)(Imaging::ColorPalettePtr) override | Sets the color palette used by the image represented by the current object. |
| [SetPixel](./setpixel/)(int, int, Color) | Sets the color of the specified pixel in the bitmap image represented by the current object. |
| [SetResolution](./setresolution/)(float, float) | Sets the resolution of the image. |
| [UnlockBits](./unlockbits/)(const Imaging::BitmapDataPtr\&) | Unlocks the specified bitmap from system memory. |
## See Also

* Class [Image](../image/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
