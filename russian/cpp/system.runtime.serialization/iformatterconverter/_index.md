---
title: "System::Runtime::Serialization::IFormatterConverter класс"
linktitle: "IFormatterConverter"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Runtime::Serialization::IFormatterConverter класс. Обеспечивает связь между экземпляром System::Runtime::Serialization::SerializationInfo и классом, предоставляемым форматтером, который лучше всего подходит для разбора данных внутри System::Runtime::Serialization::SerializationInfo в C++."
type: docs
weight: 200
url: /ru/cpp/system.runtime.serialization/iformatterconverter/
---
## IFormatterConverter class


Обеспечивает связь между экземпляром [System::Runtime::Serialization::SerializationInfo](../serializationinfo/) и классом, предоставляемым форматтером, который лучше всего подходит для разбора данных внутри [System::Runtime::Serialization::SerializationInfo](../serializationinfo/).

```cpp
class IFormatterConverter : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [Convert](./convert/)(System::SharedPtr\<Object\>, const TypeInfo\&) | Информация RTTI. |
| virtual [Convert](./convert/)(System::SharedPtr\<Object\>, TypeCode) | Преобразует значение в указанный [System::TypeCode](../../system/typecode/). |
| virtual [ToBoolean](./toboolean/)(System::SharedPtr\<Object\>) | Преобразует значение в bool. |
| virtual [ToByte](./tobyte/)(System::SharedPtr\<Object\>) | Преобразует значение в uint8_t. |
| virtual [ToChar](./tochar/)(System::SharedPtr\<Object\>) | Преобразует значение в char16_t. |
| virtual [ToDateTime](./todatetime/)(System::SharedPtr\<Object\>) | Преобразует значение в [DateTime](../../system/datetime/). |
| virtual [ToDecimal](./todecimal/)(System::SharedPtr\<Object\>) | Преобразует значение в [Decimal](../../system/decimal/). |
| virtual [ToDouble](./todouble/)(System::SharedPtr\<Object\>) | Преобразует значение в double. |
| virtual [ToInt16](./toint16/)(System::SharedPtr\<Object\>) | Преобразует значение в int16_t. |
| virtual [ToInt32](./toint32/)(System::SharedPtr\<Object\>) | Преобразует значение в int32_t. |
| virtual [ToInt64](./toint64/)(System::SharedPtr\<Object\>) | Преобразует значение в int64_t. |
| virtual [ToSByte](./tosbyte/)(System::SharedPtr\<Object\>) | Преобразует значение в int8_t. |
| virtual [ToSingle](./tosingle/)(System::SharedPtr\<Object\>) | Преобразует значение в float. |
| virtual [ToString](./tostring/)(System::SharedPtr\<Object\>) | Преобразует значение в [String](../../system/string/). |
| virtual [ToUInt16](./touint16/)(System::SharedPtr\<Object\>) | Преобразует значение в uint16_t. |
| virtual [ToUInt32](./touint32/)(System::SharedPtr\<Object\>) | Преобразует значение в uint32_t. |
| virtual [ToUInt64](./touint64/)(System::SharedPtr\<Object\>) | Преобразует значение в uint64_t. |
## См. также

* Class [Object](../../system/object/)
* Namespace [System::Runtime::Serialization](../)
* Library [Aspose.PDF for C++](../../)
