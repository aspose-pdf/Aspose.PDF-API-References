---
title: "Метод System::Collections::Generic::List::LastIndexOf"
linktitle: "LastIndexOf"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Collections::Generic::List::LastIndexOf. Ищет указанный объект и возвращает нулевой индекс последнего вхождения во всём списке в C++."
type: docs
weight: 3400
url: /ru/cpp/system.collections.generic/list/lastindexof/
---
## List::LastIndexOf(const T\&) const method


Ищет указанный объект и возвращает нулевой индекс последнего вхождения во всём списке.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| элемент | const T\& | Объект, который необходимо найти в списке |

### ReturnValue

Нулевой индекс последнего вхождения элемента во всём [List](../), если найден; иначе -1.

## См. также

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::LastIndexOf(const T\&, int32_t) const method


Ищет указанный объект и возвращает нулевой индекс последнего вхождения в диапазоне элементов [List](../), который простирается от первого элемента до указанного индекса.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| элемент | const T\& | Объект, который необходимо найти в списке |
| индекс | int32_t | Нулевой начальный индекс обратного поиска. |

### ReturnValue

Нулевой индекс последнего вхождения элемента в диапазоне элементов [List](../), который простирается от первого элемента до индекса, если найден; иначе -1.

## См. также

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## List::LastIndexOf(const T\&, int32_t, int32_t) const method


Ищет указанный объект и возвращает нулевой индекс последнего вхождения в диапазоне элементов [List](../), который содержит указанное количество элементов и заканчивается на указанном индексе.

```cpp
int32_t System::Collections::Generic::List<T>::LastIndexOf(const T &item, int32_t index, int32_t count) const
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| item | const T\& | Объект, который необходимо найти в [List](../) |
| индекс | int32_t | Нулевой начальный индекс обратного поиска. |
| count | int32_t | Количество элементов в разделе для поиска. |

### ReturnValue

Нулевой индекс последнего вхождения элемента в диапазоне элементов [List](../), который содержит количество элементов count и заканчивается на индексе index, если найден; иначе -1.

## См. также

* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
