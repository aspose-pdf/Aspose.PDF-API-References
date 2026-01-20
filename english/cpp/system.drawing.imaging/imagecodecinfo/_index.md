---
title: System::Drawing::Imaging::ImageCodecInfo class
linktitle: ImageCodecInfo
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::ImageCodecInfo class. Provides information about an image codec. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1000
url: /cpp/system.drawing.imaging/imagecodecinfo/
---
## ImageCodecInfo class


Provides information about an image codec. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ImageCodecInfo : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_FormatID](./get_formatid/)() const | Returns a GUID associated with the format of the codec represented by the current object. |
| [get_MimeType](./get_mimetype/)() | Returns the Multipurpose Internet Mail Extensions (MIME) type of the codec represented by the current object. |
| static [GetImageDecoders](./getimagedecoders/)() | Returns an array of [ImageCodecInfo](./) objects that represent supported image decoders. |
| static [GetImageEncoders](./getimageencoders/)() | Returns an array of [ImageCodecInfo](./) objects that represent supported image encoders. |
| [set_FormatID](./set_formatid/)(const Guid\&) | Sets a GUID associated with the format of the codec represented by the current object. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
