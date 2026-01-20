---
title: System::ComponentModel::EnumConverter class
linktitle: EnumConverter
second_title: Aspose.PDF for C++ API Reference
description: 'System::ComponentModel::EnumConverter class. Dummy class for EnumConverter-using translated code to compile. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 700
url: /cpp/system.componentmodel/enumconverter/
---
## EnumConverter class


Dummy class for EnumConverter-using translated code to compile. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EnumConverter : public System::ComponentModel::TypeConverter
```

## Methods

| Method | Description |
| --- | --- |
| [CanConvertFrom](./canconvertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::TypeInfo\&) | Checks if types are convertible; not implemented. |
| [CanConvertTo](./canconvertto/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::TypeInfo\&) | Checks if types are convertible; not implemented. |
| [ConvertFrom](./convertfrom/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&) override | Does actual type conversion; not implemented. |
| [ConvertTo](./convertto/)(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) override | Does actual type conversion; not implemented. |
| [EnumConverter](./enumconverter/)(const System::TypeInfo\&) | RTTI information. |
| [get_EnumType](./get_enumtype/)() | Gets enum type [EnumConverter](./) is working with; not implemented. |
## See Also

* Class [TypeConverter](../typeconverter/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
