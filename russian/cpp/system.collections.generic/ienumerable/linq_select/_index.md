---
title: "System::Collections::Generic::IEnumerable::LINQ_Select метод"
linktitle: "LINQ_Select"
second_title: "Справочник API Aspose.PDF для C++"
description: "Как использовать метод LINQ_Select класса System::Collections::Generic::IEnumerable в C++."
type: docs
weight: 2700
url: /ru/cpp/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) method


Преобразует каждый элемент последовательности в новую форму, учитывая индекс элемента.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```


| Параметр | Описание |
| --- | --- |
| ResultType | Тип значения, возвращаемого **selector**. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| selector | const Func\<T, int32_t, ResultType\>\& | Функция преобразования. |

### ReturnValue

Объект [IEnumerable](../), содержащий элементы, возвращаемые функцией **selector**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) method


Преобразует элементы последовательности.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```


| Параметр | Описание |
| --- | --- |
| ResultType | Тип значения, возвращаемого **selector**. |

| Параметр | Тип | Описание |
| --- | --- | --- |
| selector | const Func\<T, ResultType\>\& | Функция преобразования. |

### ReturnValue

Объект [IEnumerable](../), содержащий элементы, возвращаемые функцией **selector**.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
