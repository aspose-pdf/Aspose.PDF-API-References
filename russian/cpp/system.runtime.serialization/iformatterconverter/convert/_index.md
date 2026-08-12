---
title: "System::Runtime::Serialization::IFormatterConverter::Convert method"
linktitle: "Преобразовать"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Runtime::Serialization::IFormatterConverter::Convert method. Информация RTTI в C++."
type: docs
weight: 100
url: /ru/cpp/system.runtime.serialization/iformatterconverter/convert/
---
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method


Информация RTTI.

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | System::SharedPtr\<Object\> | Объект, который будет преобразован. |
| type | const TypeInfo\& | Тип [System::TypeInfo](../../../system/typeinfo/), в который должно быть преобразовано значение. |

### ReturnValue

Преобразованное значение.
## Примечания


Преобразует значение в указанный [System::TypeInfo](../../../system/typeinfo/).
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [TypeInfo](../../../system/typeinfo/)
* Class [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.PDF for C++](../../../)
## IFormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method


Преобразует значение в указанный [System::TypeCode](../../../system/typecode/).

```cpp
virtual System::SharedPtr<Object> System::Runtime::Serialization::IFormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| value | System::SharedPtr\<Object\> | Объект, который будет преобразован. |
| typeCode | TypeCode | Тип [System::TypeCode](../../../system/typecode/), в который должно быть преобразовано значение. |

### ReturnValue

Преобразованное значение.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Enum [TypeCode](../../../system/typecode/)
* Class [IFormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.PDF for C++](../../../)
