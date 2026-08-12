---
title: "System::Collections::Generic::IEnumerable::LINQ_SelectMany метод"
linktitle: "LINQ_SelectMany"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод LINQ_SelectMany класса System::Collections::Generic::IEnumerable в C++."
type: docs
weight: 2800
url: /ru/cpp/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) method


Проецирует каждый элемент последовательности и объединяет полученные последовательности в одну.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```


| Параметр | Описание |
| --- | --- |
| ResultType | Тип значения, возвращаемого **selector**. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| selector | const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\& | Функция преобразования. |

### ReturnValue

Объект [IEnumerable](../), содержащий результат вызова функции проекции один-ко-многим для каждого элемента входной последовательности.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
