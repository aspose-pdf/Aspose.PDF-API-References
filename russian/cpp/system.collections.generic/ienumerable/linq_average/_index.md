---
title: "System::Collections::Generic::IEnumerable::LINQ_Average метод"
linktitle: "LINQ_Average"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::IEnumerable::LINQ_Average метод. Вычисляет среднее значение последовательности числовых значений в C++."
type: docs
weight: 900
url: /ru/cpp/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() method


Вычисляет среднее значение последовательности числовых значений.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```


### ReturnValue

Среднее значение элементов последовательности.

## См. также

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## См. также

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) method


Вычисляет среднее значение последовательности значений, полученных вызовом функции преобразования для каждого элемента входной последовательности.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```


| Параметр | Описание |
| --- | --- |
| ResultType | Тип значения, возвращаемого селектором. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| selector | const Func\<T, ResultType\>\& | Функция преобразования, применяемая к каждому элементу. |

### ReturnValue

Среднее значение проецируемых значений.

## См. также

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
