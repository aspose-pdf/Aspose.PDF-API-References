---
title: "System::Nullable::operator+= метод"
linktitle: "operator+="
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Nullable::operator+= метод. Применяет operator+=() к значению, представленному текущим объектом, используя значение, представленное указанным объектом Nullable, в качестве правого аргумента в C++."
type: docs
weight: 1300
url: /ru/cpp/system/nullable/operator+=/
---
## Nullable::operator+=(const Nullable\<T1\>\&) method


Применяет [operator+=()](./) к значению, представленному текущим объектом, используя значение, представленное указанным объектом [Nullable](../), в качестве правого аргумента.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```


| Параметр | Описание |
| --- | --- |
| T1 | Базовый тип объекта [Nullable](../), значение которого используется в качестве правого аргумента для [operator+=()](./) |

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Константная ссылка на объект [Nullable](../), значение которого используется в качестве правого аргумента для [operator+=()](./), применяемого к значению, представленному текущим объектом. |

### ReturnValue

Ссылка на себя

## См. также

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator+=(const T1\&) method


Применяет [operator+=()](./) к значению, представленному текущим объектом, используя указанное значение в качестве правого аргумента.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```


| Параметр | Описание |
| --- | --- |
| T1 | Тип значения, используемого в качестве правого значения для [operator+=()](./) |

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const T1\& | Постоянная ссылка на значение, которое используется в качестве правой части оператора [operator+=()](./), применяемого к значению, представленному текущим объектом. |

### ReturnValue

Ссылка на себя

## См. также

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator+=(std::nullptr_t) method


Сбрасывает текущий объект, чтобы он представлял значение null.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```


### ReturnValue

Копия самого себя

## См. также

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
