---
title: System::Drawing::Imaging::BitmapData class
linktitle: BitmapData
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::BitmapData class. Represents a set of attributes of a bitmap image. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 100
url: /cpp/system.drawing.imaging/bitmapdata/
---
## BitmapData class


Represents a set of attributes of a bitmap image. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class BitmapData : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Height](./get_height/)() const | Returns the height of the image in pixels. |
| [get_PixelFormat](./get_pixelformat/)() const | Returns the pixel format of the bitmap image. |
| [get_Scan0](./get_scan0/)() const | Returns the address of the first pixel data in the bitmap. |
| [get_Stride](./get_stride/)() const | Returns the stride width of the image in bytes. |
| [get_Width](./get_width/)() const | Returns the width of the image in pixels. |
| [set_Height](./set_height/)(int) | Sets the height of the image in pixels. |
| [set_PixelFormat](./set_pixelformat/)(PixelFormat) | Sets the pixel format of the bitmap image. |
| [set_Scan0](./set_scan0/)(IntPtr) | Sets the address of the first pixel data in the bitmap. |
| [set_Stride](./set_stride/)(int) | Sets the stride width of the image in bytes. |
| [set_Width](./set_width/)(int) | Sets the width of the image in pixels. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
