---
title: "Метод System::Collections::Generic::IEnumerable::LINQ_GroupBy"
linktitle: "LINQ_GroupBy"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод LINQ_GroupBy класса System::Collections::Generic::IEnumerable в C++."
type: docs
weight: 1800
url: /ru/cpp/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) method




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) method




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) method


Группирует элементы последовательности.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```


| Параметр | Описание |
| --- | --- |
| Ключ | Тип ключа, возвращаемый keyPredicate |

| Параметр | Тип | Описание |
| --- | --- | --- |
| keyPredicate | System::Func\<T, Key\> | Функция для извлечения ключа для каждого элемента. |

### ReturnValue

Объект [IEnumerable](../), содержащий последовательность объектов и ключ

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) method


Группирует элементы последовательности.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```


| Параметр | Описание |
| --- | --- |
| Ключ | Тип ключа, возвращаемый keyPredicate |
| Элемент | Тип элемента, возвращаемый elementSelector |

| Параметр | Тип | Описание |
| --- | --- | --- |
| keyPredicate | System::Func\<T, Key\> | Функция для извлечения ключа для каждого элемента. |
| elementSelector | System::Func\<T, Element\> | Функция для извлечения значения ключа для каждого элемента. |

### ReturnValue

Объект [IEnumerable](../), содержащий последовательность объектов и ключ

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
