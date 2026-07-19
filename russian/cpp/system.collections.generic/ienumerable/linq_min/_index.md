---
title: "Метод System::Collections::Generic::IEnumerable::LINQ_Min"
linktitle: "LINQ_Min"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод LINQ_Min класса System::Collections::Generic::IEnumerable в C++."
type: docs
weight: 2200
url: /ru/cpp/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## См. также

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) method


Вызывает функцию преобразования для каждого элемента обобщённой последовательности и возвращает минимальное полученное значение.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```


| Параметр | Описание |
| --- | --- |
| ResultType | Тип значения, возвращаемого селектором. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| selector | const Func\<T, ResultType\>\& | Функция преобразования, применяемая к каждому элементу. |

### ReturnValue

Минимальное значение в последовательности.

## См. также

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
