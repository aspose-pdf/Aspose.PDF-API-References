---
title: "System::Nullable::operator<= метод"
linktitle: "operator<="
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Nullable::operator<= метод. Определяет, меньше ли или равно значение, представленное текущим объектом, значению, представленному указанным объектом Nullable, применяя operator<=() к этим значениям в C++."
type: docs
weight: 1700
url: /ru/cpp/system/nullable/operator_=/
---
## Nullable::operator<=(const Nullable\<T1\>\&) const method


Определяет, меньше ли или равно значение, представленное текущим объектом, значению, представленному указанным объектом [Nullable](../), применяя [operator<=()](./) к этим значениям.

```cpp
template<typename T1> bool System::Nullable<T>::operator<=(const Nullable<T1> &other) const
```


| Параметр | Описание |
| --- | --- |
| T1 | Базовый тип объекта [Nullable](../), с которым производится сравнение |

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Константная ссылка на объект [Nullable](../), с которым производится сравнение |

### ReturnValue

True, если значение, представленное текущим объектом, меньше или равно значению, представленному указанным объектом [Nullable](../), иначе — false

## См. также

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator<=(const T1\&) const method


Определяет, меньше ли или равно значение, представленное текущим объектом, указанному значению, применяя [operator<=()](./) к этим значениям.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<=(const T1 &other) const
```


| Параметр | Описание |
| --- | --- |
| T1 | Тип сравниваемой величины |

| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | const T1\& | Константная ссылка на сравниваемую величину |

### ReturnValue

True, если значение, представленное текущим объектом, меньше или равно указанному значению, иначе — false

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator<=(std::nullptr_t) const method


Всегда возвращает false.

```cpp
bool System::Nullable<T>::operator<=(std::nullptr_t) const
```

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
---
title: System::Nullable::operator>= метод
linktitle: operator>=
second_title: Aspose.PDF для C++ справочник API
description: 'System::Nullable::operator>= метод. Определяет, больше ли или равно значение, представленное текущим объектом, значению, представленному указанным объектом Nullable, применяя operator>=() к этим значениям в C++.'
type: docs
weight: 2100
url: /cpp/system/nullable/operator_=/
---
## Nullable::operator>=(const Nullable\<T1\>\&) const method


Определяет, больше ли или равно значение, представленное текущим объектом, значению, представленному указанным объектом [Nullable](../), путем применения [operator>=()](./) к этим значениям.

```cpp
template<typename T1> bool System::Nullable<T>::operator>=(const Nullable<T1> &other) const
```


| Параметр | Описание |
| --- | --- |
| T1 | Базовый тип объекта [Nullable](../), с которым производится сравнение |

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Константная ссылка на объект [Nullable](../), с которым производится сравнение |

### ReturnValue

True если значение, представленное текущим объектом, больше или равно значению, представленному указанным объектом [Nullable](../), иначе — false

## См. также

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator>=(const T1\&) const method


Определяет, больше ли или равно значение, представленное текущим объектом, значению, представленному указанным объектом, путем применения [operator>=()](./) к этим значениям.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>=(const T1 &other) const
```


| Параметр | Описание |
| --- | --- |
| T1 | Базовый тип значения, с которым сравнивается значение, представленное текущим объектом |

| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | const T1\& | Константная ссылка на объект, с которым сравнивается текущий объект |

### ReturnValue

True если значение, представленное текущим объектом, больше или равно значению, представленному указанным объектом, иначе — false

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator>=(std::nullptr_t) const method


Всегда возвращает false.

```cpp
bool System::Nullable<T>::operator>=(std::nullptr_t) const
```


### ReturnValue

Всегда — false

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
---
заголовок: System::Nullable::operator|= method
заголовок ссылки: operator|=
second_title: Aspose.PDF для C++ справочник API
описание: 'System::Nullable::operator|= method. Применяет operator|=() к значению, представленному текущим объектом, используя указанное значение в качестве правого аргумента в C++.'
type: docs
вес: 2200
url: /cpp/system/nullable/operator_=/
---
## Nullable::operator|= method


Применяет [operator|=()](./) к значению, представленному текущим объектом, используя указанное значение в качестве правого аргумента.

```cpp
template<typename T1> std::enable_if<std::is_same<T1, bool>::value, Nullable<T>>::type System::Nullable<T>::operator|=(bool other)
```


| Параметр | Описание |
| --- | --- |
| T1 | Параметр шаблона, необходимый для работы SFINAE. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | bool | Логическое значение, которое используется в качестве правого значения [operator | =()](./) применяется к значению, представленному текущим объектом. |

### ReturnValue

Ссылка на себя.

## См. также

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
