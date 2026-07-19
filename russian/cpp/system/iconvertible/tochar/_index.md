---
title: "System::IConvertible::ToChar метод"
linktitle: "ToChar"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IConvertible::ToChar метод. Преобразует значение этого экземпляра в эквивалентный символ Unicode, используя указанные сведения о форматировании, зависящие от культуры, в C++."
type: docs
weight: 400
url: /ru/cpp/system/iconvertible/tochar/
---
## IConvertible::ToChar method


Преобразует значение этого экземпляра в эквивалентный символ Unicode, используя указанные культурно-специфические сведения о форматировании.

```cpp
virtual char_t System::IConvertible::ToChar(System::SharedPtr<System::IFormatProvider> provider)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| provider | System::SharedPtr\<System::IFormatProvider\> | Реализация интерфейса [System::IFormatProvider](../../iformatprovider/), предоставляющая культурно-зависимые сведения о форматировании. |

### ReturnValue

Символ Unicode, эквивалентный значению данного экземпляра.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [IConvertible](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
