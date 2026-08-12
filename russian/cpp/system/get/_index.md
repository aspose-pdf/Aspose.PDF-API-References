---
title: "метод System::Get"
linktitle: "Get"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Get. Функция для получения N‑го элемента кортежа. Перегрузка для базового объекта в C++."
type: docs
weight: 21200
url: /ru/cpp/system/get/
---
## System::Get(const SharedPtr\<Object\>\&) method


Функция для получения N‑го элемента кортежа. Перегрузка для базового объекта.

```cpp
template<std::size_t> auto System::Get(const SharedPtr<Object> &object)
```


| Параметр | Описание |
| --- | --- |
| N | индекс элемента. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| объект | const SharedPtr\<Object\>\& | объект для инспекции. |

### ReturnValue

значение N‑го элемента кортежа, приведённое к объекту.

## См. также

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(const SharedPtr\<T\>\&) method


Функция для получения N‑го элемента кортежа. Перегрузка для shared pointers.

```cpp
template<std::size_t,typename T> auto System::Get(const SharedPtr<T> &pointer)
```


| Параметр | Описание |
| --- | --- |
| N | индекс элемента. |
| T | тип инспектируемого объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| объект | const SharedPtr\<T\>\& | объект для инспекции. |

### ReturnValue

значение N‑го элемента кортежа.

## См. также

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(const T\&) method


Функция для получения N‑го элемента кортежа. Перегрузка для объектов с методом Deconstruct.

```cpp
template<std::size_t,typename T> auto System::Get(const T &object)
```


| Параметр | Описание |
| --- | --- |
| N | индекс элемента. |
| T | тип инспектируемого объекта. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| объект | const T\& | объект для инспекции. |

### ReturnValue

значение N‑го элемента кортежа.

## См. также

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(const ValueTuple\<Args...\>\&) method


Получает N‑й элемент кортежа значений.

```cpp
template<std::size_t,typename...> auto System::Get(const ValueTuple<Args...> &tuple)
```


| Параметр | Описание |
| --- | --- |
| N | индекс элемента. |
| Аргументы | элементы кортежа. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| кортеж | const ValueTuple\<Args...\>\& | кортеж, из которого получить элемент. |

### ReturnValue

значение N‑го элемента кортежа.

## См. также

* Class [ValueTuple](../valuetuple/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(T\&, const Index\&) method


Реализация выражений collection[index].

```cpp
template<typename T> auto & System::Get(T &collection, const Index &index)
```


| Параметр | Описание |
| --- | --- |
| T | Тип коллекции. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| коллекция | T\& | Объект коллекции. |
| index | const Index\& | Индекс элемента типа [System.Index](../index/). |

### ReturnValue

Элемент коллекции по вычисленному смещению.

## См. также

* Class [Index](../index/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::Get(T\&, const Range\&) method


Возвращает срез указанной коллекции, определённый заданным диапазоном.

```cpp
template<typename T> auto System::Get(T &collection, const Range &range)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| коллекция | T\& | Коллекция для среза. |
| диапазон | const Range\& | Диапазон, определяющий границы среза. |

### ReturnValue

Представление или срез коллекции, начиная с вычисленного начального смещения и длины.

## См. также

* Class [Range](../range/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
