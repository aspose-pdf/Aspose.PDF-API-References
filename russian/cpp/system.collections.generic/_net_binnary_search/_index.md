---
title: "Метод System::Collections::Generic::_net_binnary_search"
linktitle: "_net_binnary_search"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Collections::Generic::_net_binnary_search. Реализует бинарный поиск в контейнере с произвольным доступом. Специализация для умных указателей. Использует метод System::Object::CompareTo в C++."
type: docs
weight: 4900
url: /ru/cpp/system.collections.generic/_net_binnary_search/
---
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T) method


Реализует бинарный поиск в контейнере с произвольным доступом. Специализация для умных указателей. Использует метод CompareTo.

```cpp
template<template< typename, typename > class,class T,class Allocator> std::enable_if<IsSmartPtr<T>::value, int>::type System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value)
```


| Параметр | Описание |
| --- | --- |
| containerT | Тип шаблона контейнера в стиле STL с двумя параметрами шаблона: типом элемента и типом аллокатора. |
| T | Тип элемента. |
| Allocator | Тип аллокатора. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| контейнер | const containterT\<T, Allocator\>\& | Контейнер для поиска. |
| индекс | int | Индекс начала диапазона поиска. |
| count | int | Длина диапазона поиска. |
| value | T | Искомое значение. |

### ReturnValue

Если найдено, индекс следующего элемента; иначе — дополнение индекса, на котором поиск остановился.

## См. также

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T) method


Реализует бинарный поиск в контейнере с произвольным доступом. Специализация для типовых значений. Использует метод CompareTo.

```cpp
template<template< typename, typename > class,class T,class Allocator> std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, int>::type System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value)
```


| Параметр | Описание |
| --- | --- |
| containerT | Тип шаблона контейнера в стиле STL с двумя параметрами шаблона: типом элемента и типом аллокатора. |
| T | Тип элемента. |
| Allocator | Тип аллокатора. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| контейнер | const containterT\<T, Allocator\>\& | Контейнер для поиска. |
| индекс | int | Индекс начала диапазона поиска. |
| count | int | Длина диапазона поиска. |
| value | T | Искомое значение. |

### ReturnValue

Если найдено, индекс следующего элемента; иначе — дополнение индекса, на котором поиск остановился.

## См. также

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T) method


Реализует бинарный поиск в контейнере с произвольным доступом. Специализация для скалярных типов. Сравнивает элементы с помощью операторов > и <.

```cpp
template<template< typename, typename > class,class T,class Allocator> std::enable_if<std::is_scalar<T>::value, int>::type System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value)
```


| Параметр | Описание |
| --- | --- |
| containerT | Тип шаблона контейнера в стиле STL с двумя параметрами шаблона: типом элемента и типом аллокатора. |
| T | Тип элемента. |
| Allocator | Тип аллокатора. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| контейнер | const containterT\<T, Allocator\>\& | Контейнер для поиска. |
| индекс | int | Индекс начала диапазона поиска. |
| count | int | Длина диапазона поиска. |
| value | T | Искомое значение. |

### ReturnValue

Если найдено, индекс следующего элемента; иначе — дополнение индекса, на котором поиск остановился.

## См. также

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
## System::Collections::Generic::_net_binnary_search(const containterT\<T, Allocator\>\&, int, int, T, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method


Реализует бинарный поиск в контейнере с произвольным доступом.

```cpp
template<template< typename, typename > class,class T,class Allocator> int System::Collections::Generic::_net_binnary_search(const containterT<T, Allocator> &container, int index, int count, T value, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer)
```


| Параметр | Описание |
| --- | --- |
| containerT | Тип шаблона контейнера в стиле STL с двумя параметрами шаблона: типом элемента и типом аллокатора. |
| T | Тип элемента. |
| Allocator | Тип аллокатора. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| контейнер | const containterT\<T, Allocator\>\& | Контейнер для поиска. |
| индекс | int | Индекс начала диапазона поиска. |
| count | int | Длина диапазона поиска. |
| value | T | Искомое значение. |
| comparer | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | [Comparer](../comparer/) объект. |

### ReturnValue

Если найдено, индекс следующего элемента; иначе — дополнение индекса, на котором поиск остановился.

## См. также

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IComparer](../icomparer/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
