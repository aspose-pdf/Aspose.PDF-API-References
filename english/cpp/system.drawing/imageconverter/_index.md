---
title: System::Drawing::ImageConverter class
linktitle: ImageConverter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::ImageConverter class. Converts Image objects from one data type to another. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 1300
url: /cpp/system.drawing/imageconverter/
---
## ImageConverter class


Converts [Image](../image/) objects from one data type to another. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ImageConverter : public System::ComponentModel::TypeConverter
```

## Methods

| Method | Description |
| --- | --- |
| [ConvertTo](./convertto/)(const System::SharedPtr\<System::ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) override | Converts object to specific type. |
| [ConvertTo](./convertto/)(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) | Converts object to specific type. |
| [ImageConverter](./imageconverter/)() | Constructs a new instance of [ImageConverter](./). |
## See Also

* Class [TypeConverter](../../system.componentmodel/typeconverter/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
