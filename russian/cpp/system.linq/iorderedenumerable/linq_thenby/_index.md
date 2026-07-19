---
title: "System::Linq::IOrderedEnumerable::LINQ_ThenBy метод"
linktitle: "LINQ_ThenBy"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод LINQ_ThenBy класса System::Linq::IOrderedEnumerable в C++."
type: docs
weight: 300
url: /ru/cpp/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) method




```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IOrderedEnumerable](../)
* Namespace [System::Linq](../../)
* Library [Aspose.PDF for C++](../../../)
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) method


Выполняет последующую сортировку элементов последовательности по возрастанию в соответствии с ключом.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```


| Параметр | Описание |
| --- | --- |
| Ключ | Тип ключа, возвращаемого keySelector. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| keySelector | const Func\<T, Key\>\& | Функция для извлечения ключа из каждого элемента. |

### ReturnValue

[System::Linq::IOrderedEnumerable](../) whose elements are sorted according to a key.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IOrderedEnumerable](../)
* Namespace [System::Linq](../../)
* Library [Aspose.PDF for C++](../../../)
