---
title: "Метод System::IConvertible::ToDateTime"
linktitle: "ToDateTime"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::IConvertible::ToDateTime. Преобразует значение этого экземпляра в эквивалентный System::DateTime, используя указанные сведения о форматировании, зависящие от культуры, в C++."
type: docs
weight: 500
url: /ru/cpp/system/iconvertible/todatetime/
---
## IConvertible::ToDateTime method


Преобразует значение этого экземпляра в эквивалентный [System::DateTime](../../datetime/) с использованием указанных сведений о форматировании, зависящих от культуры.

```cpp
virtual System::DateTime System::IConvertible::ToDateTime(System::SharedPtr<System::IFormatProvider> provider)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| provider | System::SharedPtr\<System::IFormatProvider\> | Реализация интерфейса [System::IFormatProvider](../../iformatprovider/), предоставляющая культурно-зависимые сведения о форматировании. |

### ReturnValue

Экземпляр [System::DateTime](../../datetime/) эквивалентный значению этого экземпляра.

## См. также

* Class [DateTime](../../datetime/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [IConvertible](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
