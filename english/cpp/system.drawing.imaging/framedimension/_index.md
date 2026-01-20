---
title: System::Drawing::Imaging::FrameDimension class
linktitle: FrameDimension
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::FrameDimension class. Provides properties that get the frame dimensions of an image. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 800
url: /cpp/system.drawing.imaging/framedimension/
---
## FrameDimension class


Provides properties that get the frame dimensions of an image. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FrameDimension : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Equals](./equals/)(FrameDimensionPtr) | Determines if the specified [FrameDimension](./) object is equivalent to the current object. |
| [FrameDimension](./framedimension/)(const System::Guid\&) | Constructs a new [FrameDimension](./) object and initializes it with the specified GUID. |
| [get_Guid](./get_guid/)() const | Returns GUID associated with the current object. |
| static [get_Page](./get_page/)() | Returns the page dimension. |
| static [get_Resolution](./get_resolution/)() | Returns the resolution dimension. |
| static [get_Time](./get_time/)() | Returns the time dimension. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
