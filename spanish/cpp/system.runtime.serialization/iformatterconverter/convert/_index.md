---
title: "System::Runtime::Serialization::IFormatterConverter::Convert método"
linktitle: "Convertir"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Runtime::Serialization::IFormatterConverter::Convert método. Información RTTI en C++."
type: docs
weight: 100
url: /es/cpp/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method


Información RTTI.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | System::SharedPtr\<Object\> | El objeto a convertir. |
| type | const TypeInfo\& | El [System::TypeInfo](../../../system/typeinfo/) al que se debe convertir el valor. |

### ReturnValue

El valor convertido.
## Observaciones


Convierte un valor al [System::TypeInfo](../../../system/typeinfo/) especificado.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.PDF for C++](../../../)
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method


Convierte un valor al [System::TypeCode](../../../system/typecode/) especificado.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | System::SharedPtr\<Object\> | El objeto a convertir. |
| typeCode | TypeCode | El [System::TypeCode](../../../system/typecode/) al que se debe convertir el valor. |

### ReturnValue

El valor convertido.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Enum [TypeCode](../../../system/typecode/)
* Class [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.PDF for C++](../../../)
