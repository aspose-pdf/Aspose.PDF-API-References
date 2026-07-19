---
title: "Метод System::IConvertible::ToString"
linktitle: "ToString"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::IConvertible::ToString. Аналог метода C# Object.ToString(). Позволяет преобразовывать пользовательские объекты в строку в C++."
type: docs
weight: 1300
url: /ru/cpp/system/iconvertible/tostring/
---
## IConvertible::ToString() const method


Аналог метода C# [Object.ToString()](../../object/tostring/). Позволяет преобразовывать пользовательские объекты в строку.

```cpp
virtual String System::Object::ToString() const
```


### ReturnValue

[String](../../string/) representation as provided by final class.

## См. также

* Class [String](../../string/)
* Class [IConvertible](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) method


Преобразует значение этого экземпляра в эквивалентный [System::String](../../string/) с использованием указанных сведений о форматировании, зависящих от культуры.

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| provider | System::SharedPtr\<System::IFormatProvider\> | Реализация интерфейса [System::IFormatProvider](../../iformatprovider/), предоставляющая культурно-зависимые сведения о форматировании. |

### ReturnValue

Экземпляр [System::String](../../string/) эквивалентный значению этого экземпляра.

## См. также

* Class [String](../../string/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [IConvertible](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
