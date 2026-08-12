---
title: "System::Nullable::operator== method"
linktitle: "operator=="
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Nullable::operator== method. Определяет, равно ли значение, представленное текущим объектом, значению, представленному указанным объектом Nullable в C++."
type: docs
weight: 1900
url: /ru/cpp/system/nullable/operator==/
---
## Nullable::operator==(const Nullable\<T1\>\&) const method


Определяет, равно ли значение, представленное текущим объектом, значению, представленному указанным объектом [Nullable](../).

```cpp
template<typename T1> bool System::Nullable<T>::operator==(const Nullable<T1> &other) const
```


| Параметр | Описание |
| --- | --- |
| T1 | Базовый тип объекта [Nullable](../), с которым производится сравнение |

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Константная ссылка на объект [Nullable](../), с которым производится сравнение |

### ReturnValue

True, если значение, представленное текущим объектом, равно значению, представленному указанным объектом [Nullable](../), иначе - false

## См. также

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator==(const T1\&) const method


Определяет, равно ли значение, представленное текущим объектом, указанному значению.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator==(const T1 &other) const
```


| Параметр | Описание |
| --- | --- |
| T1 | Тип сравниваемой величины |

| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | const T1\& | Константная ссылка на сравниваемую величину |

### ReturnValue

True, если значение, представленное текущим объектом, равно указанному значению, иначе - false

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator==(std::nullptr_t) const method


Определяет, является ли значение, представленное текущим объектом, null.

```cpp
bool System::Nullable<T>::operator==(std::nullptr_t) const
```


### ReturnValue

True, если значение, представленное текущим объектом, равно null, иначе - false

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
