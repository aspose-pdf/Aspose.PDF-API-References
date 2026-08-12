---
title: "System::Runtime::Serialization::FormatterConverter klass"
linktitle: "FormatterConverter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Runtime::Serialization::FormatterConverter klass. Representerar en grundläggande implementation av System::Runtime::Serialization::IFormatterConverter‑gränssnittet i C++."
type: docs
weight: 100
url: /sv/cpp/system.runtime.serialization/formatterconverter/
---
## FormatterConverter class


Representerar en grundläggande implementation av [System::Runtime::Serialization::IFormatterConverter](../iformatterconverter/)-gränssnittet.

```cpp
class FormatterConverter : public System::Runtime::Serialization::IFormatterConverter
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Convert](./convert/)(System::SharedPtr\<Object\>, const TypeInfo\&) override | RTTI-information. |
| [Convert](./convert/)(System::SharedPtr\<Object\>, TypeCode) override | Konverterar ett värde till den givna [System::TypeCode](../../system/typecode/). |
| [ToBoolean](./toboolean/)(System::SharedPtr\<Object\>) override | Konverterar ett värde till en bool. |
| [ToByte](./tobyte/)(System::SharedPtr\<Object\>) override | Konverterar ett värde till en uint8_t. |
| [ToChar](./tochar/)(System::SharedPtr\<Object\>) override | Konverterar ett värde till en char16_t. |
| [ToDateTime](./todatetime/)(System::SharedPtr\<Object\>) override | Konverterar ett värde till en [DateTime](../../system/datetime/). |
| [ToDecimal](./todecimal/)(System::SharedPtr\<Object\>) override | Konverterar ett värde till en [Decimal](../../system/decimal/). |
| [ToDouble](./todouble/)(System::SharedPtr\<Object\>) override | Konverterar ett värde till en double. |
| [ToInt16](./toint16/)(System::SharedPtr\<Object\>) override | Konverterar ett värde till en int16_t. |
| [ToInt32](./toint32/)(System::SharedPtr\<Object\>) override | Konverterar ett värde till en int32_t. |
| [ToInt64](./toint64/)(System::SharedPtr\<Object\>) override | Konverterar ett värde till en int64_t. |
| [ToSByte](./tosbyte/)(System::SharedPtr\<Object\>) override | Konverterar ett värde till en int8_t. |
| [ToSingle](./tosingle/)(System::SharedPtr\<Object\>) override | Konverterar ett värde till en float. |
| [ToString](./tostring/)(System::SharedPtr\<Object\>) override | Konverterar ett värde till en [String](../../system/string/). |
| [ToUInt16](./touint16/)(System::SharedPtr\<Object\>) override | Konverterar ett värde till en uint16_t. |
| [ToUInt32](./touint32/)(System::SharedPtr\<Object\>) override | Konverterar ett värde till en uint32_t. |
| [ToUInt64](./touint64/)(System::SharedPtr\<Object\>) override | Konverterar ett värde till en uint64_t. |
## Se även

* Class [IFormatterConverter](../iformatterconverter/)
* Namespace [System::Runtime::Serialization](../)
* Library [Aspose.PDF for C++](../../)
