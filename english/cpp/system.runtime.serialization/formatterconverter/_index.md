---
title: System::Runtime::Serialization::FormatterConverter class
linktitle: FormatterConverter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Runtime::Serialization::FormatterConverter class. Represents a base implementation of the System::Runtime::Serialization::IFormatterConverter interface in C++.'
type: docs
weight: 100
url: /cpp/system.runtime.serialization/formatterconverter/
---
## FormatterConverter class


Represents a base implementation of the [System::Runtime::Serialization::IFormatterConverter](../iformatterconverter/) interface.

```cpp
class FormatterConverter : public System::Runtime::Serialization::IFormatterConverter
```

## Methods

| Method | Description |
| --- | --- |
| [Convert](./convert/)(System::SharedPtr\<Object\>, const TypeInfo\&) override | RTTI information. |
| [Convert](./convert/)(System::SharedPtr\<Object\>, TypeCode) override | Converts a value to the given [System::TypeCode](../../system/typecode/). |
| [ToBoolean](./toboolean/)(System::SharedPtr\<Object\>) override | Converts a value to a bool. |
| [ToByte](./tobyte/)(System::SharedPtr\<Object\>) override | Converts a value to a uint8_t. |
| [ToChar](./tochar/)(System::SharedPtr\<Object\>) override | Converts a value to a char16_t. |
| [ToDateTime](./todatetime/)(System::SharedPtr\<Object\>) override | Converts a value to a [DateTime](../../system/datetime/). |
| [ToDecimal](./todecimal/)(System::SharedPtr\<Object\>) override | Converts a value to a [Decimal](../../system/decimal/). |
| [ToDouble](./todouble/)(System::SharedPtr\<Object\>) override | Converts a value to a double. |
| [ToInt16](./toint16/)(System::SharedPtr\<Object\>) override | Converts a value to a int16_t. |
| [ToInt32](./toint32/)(System::SharedPtr\<Object\>) override | Converts a value to a int32_t. |
| [ToInt64](./toint64/)(System::SharedPtr\<Object\>) override | Converts a value to a int64_t. |
| [ToSByte](./tosbyte/)(System::SharedPtr\<Object\>) override | Converts a value to a int8_t. |
| [ToSingle](./tosingle/)(System::SharedPtr\<Object\>) override | Converts a value to a float. |
| [ToString](./tostring/)(System::SharedPtr\<Object\>) override | Converts a value to a [String](../../system/string/). |
| [ToUInt16](./touint16/)(System::SharedPtr\<Object\>) override | Converts a value to a uint16_t. |
| [ToUInt32](./touint32/)(System::SharedPtr\<Object\>) override | Converts a value to a uint32_t. |
| [ToUInt64](./touint64/)(System::SharedPtr\<Object\>) override | Converts a value to a uint64_t. |
## See Also

* Class [IFormatterConverter](../iformatterconverter/)
* Namespace [System::Runtime::Serialization](../)
* Library [Aspose.PDF for C++](../../)
