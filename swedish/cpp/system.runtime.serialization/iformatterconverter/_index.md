---
title: "System::Runtime::Serialization::IFormatterConverter klass"
linktitle: "IFormatterConverter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Runtime::Serialization::IFormatterConverter klass. Tillhandahåller anslutningen mellan en instans av System::Runtime::Serialization::SerializationInfo och den formatter‑tillhandahållna klass som är bäst lämpad att tolka data i System::Runtime::Serialization::SerializationInfo i C++."
type: docs
weight: 200
url: /sv/cpp/system.runtime.serialization/iformatterconverter/
---
## IFormatterConverter class


Tillhandahåller anslutningen mellan en instans av [System::Runtime::Serialization::SerializationInfo](../serializationinfo/) och den formatter‑tillhandahållna klass som är bäst lämpad att tolka data i [System::Runtime::Serialization::SerializationInfo](../serializationinfo/).

```cpp
class IFormatterConverter : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Convert](./convert/)(System::SharedPtr\<Object\>, const TypeInfo\&) | RTTI-information. |
| virtual [Convert](./convert/)(System::SharedPtr\<Object\>, TypeCode) | Konverterar ett värde till den givna [System::TypeCode](../../system/typecode/). |
| virtual [ToBoolean](./toboolean/)(System::SharedPtr\<Object\>) | Konverterar ett värde till en bool. |
| virtual [ToByte](./tobyte/)(System::SharedPtr\<Object\>) | Konverterar ett värde till en uint8_t. |
| virtual [ToChar](./tochar/)(System::SharedPtr\<Object\>) | Konverterar ett värde till en char16_t. |
| virtual [ToDateTime](./todatetime/)(System::SharedPtr\<Object\>) | Konverterar ett värde till en [DateTime](../../system/datetime/). |
| virtual [ToDecimal](./todecimal/)(System::SharedPtr\<Object\>) | Konverterar ett värde till en [Decimal](../../system/decimal/). |
| virtual [ToDouble](./todouble/)(System::SharedPtr\<Object\>) | Konverterar ett värde till en double. |
| virtual [ToInt16](./toint16/)(System::SharedPtr\<Object\>) | Konverterar ett värde till en int16_t. |
| virtual [ToInt32](./toint32/)(System::SharedPtr\<Object\>) | Konverterar ett värde till en int32_t. |
| virtual [ToInt64](./toint64/)(System::SharedPtr\<Object\>) | Konverterar ett värde till en int64_t. |
| virtual [ToSByte](./tosbyte/)(System::SharedPtr\<Object\>) | Konverterar ett värde till en int8_t. |
| virtual [ToSingle](./tosingle/)(System::SharedPtr\<Object\>) | Konverterar ett värde till en float. |
| virtual [ToString](./tostring/)(System::SharedPtr\<Object\>) | Konverterar ett värde till en [String](../../system/string/). |
| virtual [ToUInt16](./touint16/)(System::SharedPtr\<Object\>) | Konverterar ett värde till en uint16_t. |
| virtual [ToUInt32](./touint32/)(System::SharedPtr\<Object\>) | Konverterar ett värde till en uint32_t. |
| virtual [ToUInt64](./touint64/)(System::SharedPtr\<Object\>) | Konverterar ett värde till en uint64_t. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Runtime::Serialization](../)
* Library [Aspose.PDF for C++](../../)
