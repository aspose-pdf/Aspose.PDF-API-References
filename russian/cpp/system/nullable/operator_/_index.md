---
title: "System::Nullable::operator< method"
linktitle: "operator<"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Nullable::operator< method. Определяет, меньше ли значение, представленное текущим объектом, чем значение, представленное указанным объектом Nullable, путем применения operator<() к этим значениям в C++."
type: docs
weight: 1600
url: /ru/cpp/system/nullable/operator_/
---
## Nullable::operator<(const Nullable\<T1\>\&) const method


Определяет, меньше ли значение, представленное текущим объектом, чем значение, представленное указанным объектом [Nullable](../), путем применения [operator<()](./) к этим значениям.

```cpp
template<typename T1> bool System::Nullable<T>::operator<(const Nullable<T1> &other) const
```


| Параметр | Описание |
| --- | --- |
| T1 | Базовый тип объекта [Nullable](../), с которым производится сравнение |

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Константная ссылка на объект [Nullable](../), с которым производится сравнение |

### ReturnValue

True, если значение, представленное текущим объектом, меньше значения, представленного указанным объектом [Nullable](../), иначе — false

## См. также

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator<(const T1\&) const method


Определяет, меньше ли значение, представленное текущим объектом, чем указанное значение, путем применения [operator<()](./) к этим значениям.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator<(const T1 &other) const
```


| Параметр | Описание |
| --- | --- |
| T1 | Тип сравниваемой величины |

| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | const T1\& | Константная ссылка на сравниваемую величину |

### ReturnValue

True, если значение, представленное текущим объектом, меньше указанного значения, иначе — false

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator<(std::nullptr_t) const method


Всегда возвращает false.

```cpp
bool System::Nullable<T>::operator<(std::nullptr_t) const
```

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
---
заголовок: System::Nullable::operator> method
linktitle: operator>
second_title: Aspose.PDF для C++ справочник API
описание: 'System::Nullable::operator> method. Определяет, больше ли значение, представленное текущим объектом, чем значение, представленное указанным объектом Nullable, путем применения operator>() к этим значениям в C++.'
type: docs
вес: 2000
url: /cpp/system/nullable/operator_/
---
## Nullable::operator>(const Nullable\<T1\>\&) const method


Определяет, больше ли значение, представленное текущим объектом, чем значение, представленное указанным объектом [Nullable](../), путем применения [operator>()](./) к этим значениям.

```cpp
template<typename T1> bool System::Nullable<T>::operator>(const Nullable<T1> &other) const
```


| Параметр | Описание |
| --- | --- |
| T1 | Базовый тип объекта [Nullable](../), с которым производится сравнение |

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const Nullable\<T1\>\& | Константная ссылка на объект [Nullable](../), с которым производится сравнение |

### ReturnValue

True, если значение, представленное текущим объектом, больше значения, представленного указанным объектом [Nullable](../), иначе - false

## См. также

* Class [Nullable](../)
* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator>(const T1\&) const method


Определяет, больше ли значение, представленное текущим объектом, чем указанное значение, применяя к этим значениям [operator>()](./).

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, bool>::type System::Nullable<T>::operator>(const T1 &other) const
```


| Параметр | Описание |
| --- | --- |
| T1 | Тип сравниваемой величины |

| Параметр | Тип | Описание |
| --- | --- | --- |
| другое | const T1\& | Константная ссылка на сравниваемую величину |

### ReturnValue

True, если значение, представленное текущим объектом, больше указанного значения, иначе - false

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Nullable::operator>(std::nullptr_t) const method


Всегда возвращает false.

```cpp
bool System::Nullable<T>::operator>(std::nullptr_t) const
```

## См. также

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
