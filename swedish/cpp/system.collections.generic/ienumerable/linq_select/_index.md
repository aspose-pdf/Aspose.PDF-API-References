---
title: "System::Collections::Generic::IEnumerable::LINQ_Select metod"
linktitle: "LINQ_Select"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder LINQ_Select‑metoden i System::Collections::Generic::IEnumerable‑klassen i C++."
type: docs
weight: 2700
url: /sv/cpp/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## Se även

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

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) method


Transformerar varje element i en sekvens till en ny form genom att inkludera elementets index.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```


| Parameter | Beskrivning |
| --- | --- |
| ResultType | Typen av värdet som returneras av **selector**. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| selector | const Func\<T, int32_t, ResultType\>\& | En transformfunktion. |

### ReturnValue

En [IEnumerable](../) som innehåller element som returneras av **selector**‑funktionen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) method


Transformerar element i en sekvens.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```


| Parameter | Beskrivning |
| --- | --- |
| ResultType | Typen av värdet som returneras av **selector**. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| selector | const Func\<T, ResultType\>\& | En transformfunktion. |

### ReturnValue

En [IEnumerable](../) som innehåller element som returneras av **selector**‑funktionen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
