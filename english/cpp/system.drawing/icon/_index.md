---
title: System::Drawing::Icon class
linktitle: Icon
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Icon class. Represents a Windows icon. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1100
url: /cpp/system.drawing/icon/
---
## Icon class


Represents a [Windows](../../system.windows/) icon. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Icon : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Height](./get_height/)() const | Returns the hegiht of the icon. |
| [get_Width](./get_width/)() const | Returns the width of the icon. |
| [Icon](./icon/)(const String\&) | Constructs a new instance of [Icon](./) class that represents an icon from the specified file. |
| [ToBitmap](./tobitmap/)() | Converts the current object to a [Bitmap](../bitmap/) object. |
| virtual [~Icon](./~icon/)() | Destructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
