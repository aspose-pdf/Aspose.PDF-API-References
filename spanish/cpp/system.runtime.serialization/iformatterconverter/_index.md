---
title: "System::Runtime::Serialization::IFormatterConverter clase"
linktitle: "IFormatterConverter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Runtime::Serialization::IFormatterConverter clase. Proporciona la conexión entre una instancia de System::Runtime::Serialization::SerializationInfo y la clase proporcionada por el formateador que mejor se adapta para analizar los datos dentro de System::Runtime::Serialization::SerializationInfo en C++."
type: docs
weight: 200
url: /es/cpp/system.runtime.serialization/iformatterconverter/
---
## IFormatterConverter class


Proporciona la conexión entre una instancia de [System::Runtime::Serialization::SerializationInfo](../serializationinfo/) y la clase proporcionada por el formateador que mejor se adapta para analizar los datos dentro del [System::Runtime::Serialization::SerializationInfo](../serializationinfo/).

```cpp
class IFormatterConverter : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [Convert](./convert/)(System::SharedPtr\<Object\>, const TypeInfo\&) | Información RTTI. |
| virtual [Convert](./convert/)(System::SharedPtr\<Object\>, TypeCode) | Convierte un valor al [System::TypeCode](../../system/typecode/) especificado. |
| virtual [ToBoolean](./toboolean/)(System::SharedPtr\<Object\>) | Convierte un valor a un bool. |
| virtual [ToByte](./tobyte/)(System::SharedPtr\<Object\>) | Convierte un valor a un uint8_t. |
| virtual [ToChar](./tochar/)(System::SharedPtr\<Object\>) | Convierte un valor a un char16_t. |
| virtual [ToDateTime](./todatetime/)(System::SharedPtr\<Object\>) | Convierte un valor a un [DateTime](../../system/datetime/). |
| virtual [ToDecimal](./todecimal/)(System::SharedPtr\<Object\>) | Convierte un valor a un [Decimal](../../system/decimal/). |
| virtual [ToDouble](./todouble/)(System::SharedPtr\<Object\>) | Convierte un valor a un double. |
| virtual [ToInt16](./toint16/)(System::SharedPtr\<Object\>) | Convierte un valor a un int16_t. |
| virtual [ToInt32](./toint32/)(System::SharedPtr\<Object\>) | Convierte un valor a un int32_t. |
| virtual [ToInt64](./toint64/)(System::SharedPtr\<Object\>) | Convierte un valor a un int64_t. |
| virtual [ToSByte](./tosbyte/)(System::SharedPtr\<Object\>) | Convierte un valor a un int8_t. |
| virtual [ToSingle](./tosingle/)(System::SharedPtr\<Object\>) | Convierte un valor a un float. |
| virtual [ToString](./tostring/)(System::SharedPtr\<Object\>) | Convierte un valor a un [String](../../system/string/). |
| virtual [ToUInt16](./touint16/)(System::SharedPtr\<Object\>) | Convierte un valor a un uint16_t. |
| virtual [ToUInt32](./touint32/)(System::SharedPtr\<Object\>) | Convierte un valor a un uint32_t. |
| virtual [ToUInt64](./touint64/)(System::SharedPtr\<Object\>) | Convierte un valor a un uint64_t. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Runtime::Serialization](../)
* Library [Aspose.PDF for C++](../../)
