---
title: "System::Collections::Generic::IEnumerable::LINQ_Max method"
linktitle: "LINQ_Max"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод LINQ_Max класса System::Collections::Generic::IEnumerable в C++."
type: docs
weight: 2100
url: /ru/cpp/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## См. также

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) method


Вызывает функцию преобразования для каждого элемента обобщённой последовательности и возвращает максимальное полученное значение.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


| Параметр | Описание |
| --- | --- |
| ResultType | Тип значения, возвращаемого селектором. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| selector | const Func\<T, ResultType\>\& | Функция преобразования, применяемая к каждому элементу. |

### ReturnValue

Максимальное значение в последовательности.

## См. также

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
