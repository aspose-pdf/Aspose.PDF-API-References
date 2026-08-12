---
title: "System::Collections::Generic::IEnumerable::LINQ_OrderBy metod"
linktitle: "LINQ_OrderBy"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder LINQ_OrderBy-metoden i klassen System::Collections::Generic::IEnumerable i C++."
type: docs
weight: 2400
url: /sv/cpp/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) method




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) method


Sorterar elementen i en sekvens i stigande ordning enligt nyckelvärdena som valts av keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```


| Parameter | Beskrivning |
| --- | --- |
| keySelector | En funktion för att extrahera en nyckel från ett element. |

### ReturnValue

En IOrderedEnumerable vars element är sorterade enligt en nyckel

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
