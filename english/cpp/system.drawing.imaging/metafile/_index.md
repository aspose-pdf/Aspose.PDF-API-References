---
title: System::Drawing::Imaging::Metafile class
linktitle: Metafile
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::Metafile class. Represents a graphic metafile. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1200
url: /cpp/system.drawing.imaging/metafile/
---
## Metafile class


Represents a graphic metafile. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Metafile : public System::Drawing::Image
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Returns a copy of the current object. |
| [get_Height](./get_height/)() const override | Returns the heights of the image in pixels. |
| [get_PixelFormat](./get_pixelformat/)() const override | Returns a value the indicates the pixel format. |
| [get_RawFormat](./get_rawformat/)() const override | Returns a value the indicates the image format. |
| [get_Width](./get_width/)() const override | Returns the width of the image in pixels. |
| [GetHenhmetafile](./gethenhmetafile/)() | NOT IMPLEMENTED. |
| [GetMetafileHeader](./getmetafileheader/)() | Returns a header associated with the current object. |
| [Metafile](./metafile/)(const System::String\&) | NOT IMPLEMENTED. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&) | NOT IMPLEMENTED. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr, EmfType) | NOT IMPLEMENTED. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr) | NOT IMPLEMENTED. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr, Rectangle, MetafileFrameUnit, EmfType) | NOT IMPLEMENTED. |
| [Metafile](./metafile/)(const SharedPtr\<System::IO::Stream\>\&, IntPtr, RectangleF, MetafileFrameUnit, EmfType) | NOT IMPLEMENTED. |
| [Metafile](./metafile/)(IntPtr, EmfType) | NOT IMPLEMENTED. |
| [PlayRecord](./playrecord/)(EmfPlusRecordType, int32_t, int32_t, System::ByteArrayPtr) | NOT IMPLEMENTED. |
| virtual [~Metafile](./~metafile/)() | Destructor. |
## See Also

* Class [Image](../../system.drawing/image/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
