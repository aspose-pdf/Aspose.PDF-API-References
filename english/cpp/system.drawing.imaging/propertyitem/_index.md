---
title: System::Drawing::Imaging::PropertyItem class
linktitle: PropertyItem
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::PropertyItem class. Represents a metadata property to be included in an image file. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1400
url: /cpp/system.drawing.imaging/propertyitem/
---
## PropertyItem class


Represents a metadata property to be included in an image file. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class PropertyItem : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Id](./get_id/)() const | Returns the ID of the property represented by the current object. |
| [get_Len](./get_len/)() const | Returns the length of the property represented by the current object in bytes. |
| [get_Type](./get_type/)() const | Returns the type of the property represented by the current object in bytes. |
| [get_Value](./get_value/)() const | Returns the value of the property represented by the current object in bytes. |
| [PropertyItem](./propertyitem/)() | Constructs a new instance of [PropertyItem](./) class. |
| [set_Id](./set_id/)(int32_t) | Sets the ID of the property represented by the current object. |
| [set_Len](./set_len/)(int32_t) | Sets the length of the property represented by the current object in bytes. |
| [set_Type](./set_type/)(int16_t) | Sets the type of the property represented by the current object in bytes. |
| [set_Value](./set_value/)(const System::ArrayPtr\<uint8_t\>\&) | Sets the type of the property represented by the current object in bytes. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
