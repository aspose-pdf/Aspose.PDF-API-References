---
title: "System::Nullable::operator&= метод"
linktitle: "operator&="
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Nullable::operator&= метод. Применяет operator&=() к значению, представленному текущим объектом, используя указанное значение в качестве правого аргумента в C++."
type: docs
weight: 1100
url: /ru/cpp/system/nullable/operator&=/
---
## Nullable::operator&= method


Применяет [operator&=()](./) к значению, представленному текущим объектом, используя указанное значение в качестве правого аргумента.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator&=(bool other)
```


| Параметр | Описание |
| --- | --- |
| T1 | Параметр шаблона, необходимый для работы SFINAE. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | bool | Булево значение, используемое в качестве правого аргумента [operator&=()](./), применяемого к значению, представленному текущим объектом. |

### ReturnValue

Ссылка на себя.

## См. также

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
