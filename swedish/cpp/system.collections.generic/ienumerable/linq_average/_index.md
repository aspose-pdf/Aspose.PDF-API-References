---
title: "System::Collections::Generic::IEnumerable::LINQ_Average metod"
linktitle: "LINQ_Average"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::IEnumerable::LINQ_Average metod. Beräknar medelvärdet av en sekvens av numeriska värden i C++."
type: docs
weight: 900
url: /sv/cpp/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() method


Beräknar medelvärdet för en sekvens av numeriska värden.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```


### ReturnValue

Medelvärdet av värdena i sekvensen.

## Se även

* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) method




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## Se även

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) method


Beräknar medelvärdet för en sekvens av värden som erhålls genom att anropa en transformfunktion på varje element i inmatningssekvensen.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```


| Parameter | Beskrivning |
| --- | --- |
| ResultType | Typen av värdet som returneras av selector. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| selector | const Func\<T, ResultType\>\& | En transformfunktion som ska tillämpas på varje element. |

### ReturnValue

Medelvärdet av de projicerade värdena.

## Se även

* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
