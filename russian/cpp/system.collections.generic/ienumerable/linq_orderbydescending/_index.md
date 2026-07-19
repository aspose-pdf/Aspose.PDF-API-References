---
title: "System::Collections::Generic::IEnumerable::LINQ_OrderByDescending метод"
linktitle: "LINQ_OrderByDescending"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод LINQ_OrderByDescending класса System::Collections::Generic::IEnumerable в C++."
type: docs
weight: 2500
url: /ru/cpp/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) method




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) method


Сортирует элементы последовательности в порядке убывания согласно значениям ключа, выбранным с помощью keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```


| Параметр | Описание |
| --- | --- |
| keySelector | Функция для извлечения ключа из элемента. |

### ReturnValue

IOrderedEnumerable, элементы которого отсортированы по убывающему порядку ключа.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
