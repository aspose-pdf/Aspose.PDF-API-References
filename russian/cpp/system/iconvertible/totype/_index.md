---
title: "System::IConvertible::ToType method"
linktitle: "ToType"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IConvertible::ToType method. Преобразует значение этого экземпляра в System::Object указанного System::Type, имеющий эквивалентное значение, используя указанные культурно-зависимые сведения о форматировании в C++."
type: docs
weight: 1400
url: /ru/cpp/system/iconvertible/totype/
---
## IConvertible::ToType method


Преобразует значение этого экземпляра в [System::Object](../../object/) указанного System::Type, имеющий эквивалентное значение, используя указанные культурно-зависимые сведения о форматировании.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| conversionType | const TypeInfo\& | System::Type, в который преобразуется значение этого экземпляра. |
| provider | System::SharedPtr\<System::IFormatProvider\> | Реализация интерфейса [System::IFormatProvider](../../iformatprovider/), предоставляющая культурно-зависимые сведения о форматировании. |

### ReturnValue

Экземпляр [System::Object](../../object/) типа conversionType, значение которого эквивалентно значению этого экземпляра.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [IConvertible](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
