---
title: "System::Runtime::Serialization::FormatterConverter класс"
linktitle: "FormatterConverter"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Runtime::Serialization::FormatterConverter класс. Представляет базовую реализацию интерфейса System::Runtime::Serialization::IFormatterConverter в C++."
type: docs
weight: 100
url: /ru/cpp/system.runtime.serialization/formatterconverter/
---
## FormatterConverter class


Представляет базовую реализацию интерфейса [System::Runtime::Serialization::IFormatterConverter](../iformatterconverter/).

```cpp
class FormatterConverter : public System::Runtime::Serialization::IFormatterConverter
```

## Методы

| Метод | Описание |
| --- | --- |
| [Convert](./convert/)(System::SharedPtr\<Object\>, const TypeInfo\&) override | Информация RTTI. |
| [Convert](./convert/)(System::SharedPtr\<Object\>, TypeCode) override | Преобразует значение в указанный [System::TypeCode](../../system/typecode/). |
| [ToBoolean](./toboolean/)(System::SharedPtr\<Object\>) override | Преобразует значение в bool. |
| [ToByte](./tobyte/)(System::SharedPtr\<Object\>) override | Преобразует значение в uint8_t. |
| [ToChar](./tochar/)(System::SharedPtr\<Object\>) override | Преобразует значение в char16_t. |
| [ToDateTime](./todatetime/)(System::SharedPtr\<Object\>) override | Преобразует значение в [DateTime](../../system/datetime/). |
| [ToDecimal](./todecimal/)(System::SharedPtr\<Object\>) override | Преобразует значение в [Decimal](../../system/decimal/). |
| [ToDouble](./todouble/)(System::SharedPtr\<Object\>) override | Преобразует значение в double. |
| [ToInt16](./toint16/)(System::SharedPtr\<Object\>) override | Преобразует значение в int16_t. |
| [ToInt32](./toint32/)(System::SharedPtr\<Object\>) override | Преобразует значение в int32_t. |
| [ToInt64](./toint64/)(System::SharedPtr\<Object\>) override | Преобразует значение в int64_t. |
| [ToSByte](./tosbyte/)(System::SharedPtr\<Object\>) override | Преобразует значение в int8_t. |
| [ToSingle](./tosingle/)(System::SharedPtr\<Object\>) override | Преобразует значение в float. |
| [ToString](./tostring/)(System::SharedPtr\<Object\>) override | Преобразует значение в [String](../../system/string/). |
| [ToUInt16](./touint16/)(System::SharedPtr\<Object\>) override | Преобразует значение в uint16_t. |
| [ToUInt32](./touint32/)(System::SharedPtr\<Object\>) override | Преобразует значение в uint32_t. |
| [ToUInt64](./touint64/)(System::SharedPtr\<Object\>) override | Преобразует значение в uint64_t. |
## См. также

* Class [IFormatterConverter](../iformatterconverter/)
* Namespace [System::Runtime::Serialization](../)
* Library [Aspose.PDF for C++](../../)
