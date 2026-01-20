---
title: System::Runtime::Serialization::IFormatterConverter class
linktitle: IFormatterConverter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Runtime::Serialization::IFormatterConverter class. Provides the connection between an instance of System::Runtime::Serialization::SerializationInfo and the formatter-provided class best suited to parse the data inside the System::Runtime::Serialization::SerializationInfo in C++.'
type: docs
weight: 200
url: /cpp/system.runtime.serialization/iformatterconverter/
---
## IFormatterConverter class


Provides the connection between an instance of [System::Runtime::Serialization::SerializationInfo](../serializationinfo/) and the formatter-provided class best suited to parse the data inside the [System::Runtime::Serialization::SerializationInfo](../serializationinfo/).

```cpp
class IFormatterConverter : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Convert](./convert/)(System::SharedPtr\<Object\>, const TypeInfo\&) | RTTI information. |
| virtual [Convert](./convert/)(System::SharedPtr\<Object\>, TypeCode) | Converts a value to the given [System::TypeCode](../../system/typecode/). |
| virtual [ToBoolean](./toboolean/)(System::SharedPtr\<Object\>) | Converts a value to a bool. |
| virtual [ToByte](./tobyte/)(System::SharedPtr\<Object\>) | Converts a value to a uint8_t. |
| virtual [ToChar](./tochar/)(System::SharedPtr\<Object\>) | Converts a value to a char16_t. |
| virtual [ToDateTime](./todatetime/)(System::SharedPtr\<Object\>) | Converts a value to a [DateTime](../../system/datetime/). |
| virtual [ToDecimal](./todecimal/)(System::SharedPtr\<Object\>) | Converts a value to a [Decimal](../../system/decimal/). |
| virtual [ToDouble](./todouble/)(System::SharedPtr\<Object\>) | Converts a value to a double. |
| virtual [ToInt16](./toint16/)(System::SharedPtr\<Object\>) | Converts a value to a int16_t. |
| virtual [ToInt32](./toint32/)(System::SharedPtr\<Object\>) | Converts a value to a int32_t. |
| virtual [ToInt64](./toint64/)(System::SharedPtr\<Object\>) | Converts a value to a int64_t. |
| virtual [ToSByte](./tosbyte/)(System::SharedPtr\<Object\>) | Converts a value to a int8_t. |
| virtual [ToSingle](./tosingle/)(System::SharedPtr\<Object\>) | Converts a value to a float. |
| virtual [ToString](./tostring/)(System::SharedPtr\<Object\>) | Converts a value to a [String](../../system/string/). |
| virtual [ToUInt16](./touint16/)(System::SharedPtr\<Object\>) | Converts a value to a uint16_t. |
| virtual [ToUInt32](./touint32/)(System::SharedPtr\<Object\>) | Converts a value to a uint32_t. |
| virtual [ToUInt64](./touint64/)(System::SharedPtr\<Object\>) | Converts a value to a uint64_t. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Runtime::Serialization](../)
* Library [Aspose.PDF for C++](../../)
