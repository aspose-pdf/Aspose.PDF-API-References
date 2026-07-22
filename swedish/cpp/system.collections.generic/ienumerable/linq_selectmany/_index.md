---
title: "System::Collections::Generic::IEnumerable::LINQ_SelectMany metod"
linktitle: "LINQ_SelectMany"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder LINQ_SelectMany-metoden i klassen System::Collections::Generic::IEnumerable i C++."
type: docs
weight: 2800
url: /sv/cpp/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) method


Projicerar varje element i en sekvens och kombinerar de resulterande sekvenserna till en sekvens.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```


| Parameter | Beskrivning |
| --- | --- |
| ResultType | Typen av värdet som returneras av **selector**. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| selector | const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\& | En transformfunktion. |

### ReturnValue

En [IEnumerable](../) som innehåller resultatet av att anropa en en‑till‑många projektionfunktion på varje element i indatasekvensen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
