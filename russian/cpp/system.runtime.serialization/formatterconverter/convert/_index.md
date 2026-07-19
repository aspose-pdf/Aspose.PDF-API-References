---
title: "System::Runtime::Serialization::FormatterConverter::Convert метод"
linktitle: "Преобразовать"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Runtime::Serialization::FormatterConverter::Convert метод. Информация RTTI в C++."
type: docs
weight: 100
url: /ru/cpp/system.runtime.serialization/formatterconverter/convert/
---
## FormatterConverter::Convert(System::SharedPtr\<Object\>, const TypeInfo\&) method


Информация RTTI.

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, const TypeInfo &type) override
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
* Class [FormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.PDF for C++](../../../)
## FormatterConverter::Convert(System::SharedPtr\<Object\>, TypeCode) method


Преобразует значение в указанный [System::TypeCode](../../../system/typecode/).

```cpp
System::SharedPtr<Object> System::Runtime::Serialization::FormatterConverter::Convert(System::SharedPtr<Object> value, TypeCode typeCode) override
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
* Class [FormatterConverter](../)
* Namespace [System::Runtime::Serialization](../../)
* Library [Aspose.PDF for C++](../../../)
