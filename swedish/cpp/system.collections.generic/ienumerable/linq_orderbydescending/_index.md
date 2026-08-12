---
title: "System::Collections::Generic::IEnumerable::LINQ_OrderByDescending metod"
linktitle: "LINQ_OrderByDescending"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder LINQ_OrderByDescending‑metoden i System::Collections::Generic::IEnumerable‑klassen i C++."
type: docs
weight: 2500
url: /sv/cpp/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) method




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) method


Sorterar elementen i en sekvens i fallande ordning enligt nyckelvärdena som valts av keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```


| Parameter | Beskrivning |
| --- | --- |
| keySelector | En funktion för att extrahera en nyckel från ett element. |

### ReturnValue

En IOrderedEnumerable vars element är sorterade i fallande ordning efter nyckeln.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
