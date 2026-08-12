---
title: "System::Linq::IOrderedEnumerable::LINQ_ThenBy-metod"
linktitle: "LINQ_ThenBy"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder LINQ_ThenBy-metoden i System::Linq::IOrderedEnumerable-klassen i C++."
type: docs
weight: 300
url: /sv/cpp/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) method




```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IOrderedEnumerable](../)
* Namespace [System::Linq](../../)
* Library [Aspose.PDF for C++](../../../)
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) method


Utför en efterföljande sortering av elementen i en sekvens i stigande ordning enligt en nyckel.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```


| Parameter | Beskrivning |
| --- | --- |
| Nyckel | Typen av nyckeln som returneras av keySelector. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keySelector | const Func\<T, Key\>\& | En funktion för att extrahera en nyckel från varje element. |

### ReturnValue

[System::Linq::IOrderedEnumerable](../) whose elements are sorted according to a key.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../)
* Class [Func](../../../system/func/)
* Class [IOrderedEnumerable](../)
* Namespace [System::Linq](../../)
* Library [Aspose.PDF for C++](../../../)
