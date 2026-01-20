---
title: System::IConvertible class
linktitle: IConvertible
second_title: Aspose.PDF for C++ API Reference
description: 'System::IConvertible class. Defines methods that convert the value of the implementing reference or value type to a common language runtime type that has an equivalent value. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3400
url: /cpp/system/iconvertible/
---
## IConvertible class


Defines methods that convert the value of the implementing reference or value type to a common language runtime type that has an equivalent value. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IConvertible : public virtual System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [GetTypeCode](./gettypecode/)() | Returns the type code for this instance. |
| virtual [ToBoolean](./toboolean/)(System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to an equivalent [Boolean](../boolean/) value using the specified culture-specific formatting information. |
| virtual [ToByte](./tobyte/)(System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to an equivalent 8-bit uint32_teger using the specified culture-specific formatting information. |
| virtual [ToChar](./tochar/)(System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to an equivalent Unicode character using the specified culture-specific formatting information. |
| virtual [ToDateTime](./todatetime/)(System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to an equivalent [System::DateTime](../datetime/) using the specified culture-specific formatting information. |
| virtual [ToDecimal](./todecimal/)(System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to an equivalent [System::Decimal](../decimal/) number using the specified culture-specific formatting information. |
| virtual [ToDouble](./todouble/)(System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to an equivalent double-precision floating-point number using the specified culture-specific formatting information.. |
| virtual [ToInt16](./toint16/)(System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to an equivalent 16-bit signed integer using the specified culture-specific formatting information. |
| virtual [ToInt32](./toint32/)(System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to an equivalent 32-bit signed integer using the specified culture-specific formatting information. |
| virtual [ToInt64](./toint64/)(System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to an equivalent 64-bit signed integer using the specified culture-specific formatting information. |
| virtual [ToSByte](./tosbyte/)(System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to an equivalent 8-bit signed integer using the specified culture-specific formatting information. |
| virtual [ToSingle](./tosingle/)(System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to an equivalent single-precision floating-point number using the specified culture-specific formatting information. |
| virtual [ToString](./tostring/)(System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to an equivalent [System::String](../string/) using the specified culture-specific formatting information. |
| virtual [ToString](./tostring/)() const | Analog of C# [Object.ToString()](../object/tostring/) method. Enables converting custom objects to string. |
| virtual [ToType](./totype/)(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to a [System::Object](../object/) of the specified System::Type that has an equivalent value, using the specified culture-specific formatting information. |
| virtual [ToUInt16](./touint16/)(System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to an equivalent 16-bit uint32_teger using the specified culture-specific formatting information. |
| virtual [ToUInt32](./touint32/)(System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to an equivalent 32-bit uint32_teger using the specified culture-specific formatting information. |
| virtual [ToUInt64](./touint64/)(System::SharedPtr\<System::IFormatProvider\>) | Converts the value of this instance to an equivalent 64-bit uint32_teger using the specified culture-specific formatting information. |
## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
