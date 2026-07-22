---
title: "System::Collections::Generic::IEnumerable::LINQ_GroupBy metod"
linktitle: "LINQ_GroupBy"
second_title: "Aspose.PDF för C++ API-referens"
description: "Hur man använder LINQ_GroupBy metod för System::Collections::Generic::IEnumerable-klassen i C++."
type: docs
weight: 1800
url: /sv/cpp/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) method




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) method




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) method


Grupperar elementen i en sekvens.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```


| Parameter | Beskrivning |
| --- | --- |
| Nyckel | Typen av nyckeln som returneras av keyPredicate |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keyPredicate | System::Func\<T, Key\> | En funktion för att extrahera nyckeln för varje element. |

### ReturnValue

En [IEnumerable](../) som innehåller en sekvens av objekt och en nyckel

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) method


Grupperar elementen i en sekvens.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```


| Parameter | Beskrivning |
| --- | --- |
| Nyckel | Typen av nyckeln som returneras av keyPredicate |
| Element | Typen av elementet som returneras av elementSelector |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keyPredicate | System::Func\<T, Key\> | En funktion för att extrahera nyckeln för varje element. |
| elementSelector | System::Func\<T, Element\> | En funktion för att extrahera värde-nyckeln för varje element. |

### ReturnValue

En [IEnumerable](../) som innehåller en sekvens av objekt och en nyckel

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEnumerable](../)
* Class [IGrouping](../../../system.linq/igrouping/)
* Class [Func](../../../system/func/)
* Class [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
