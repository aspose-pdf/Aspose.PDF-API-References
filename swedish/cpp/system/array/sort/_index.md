---
title: "System::Array::Sort metod"
linktitle: "Sortera"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Array::Sort metod. Sorterar två arrayer, en som innehåller nycklar och den andra – motsvarande objekt, baserat på värdena i arrayen som innehåller nycklar, vars element jämförs med operator< i C++."
type: docs
weight: 6000
url: /sv/cpp/system/array/sort/
---
## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&) method


Sorterar två arrayer, en som innehåller nycklar och den andra – motsvarande objekt, baserat på värdena i arrayen som innehåller nycklar, vars element jämförs med operator<.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items)
```


| Parameter | Beskrivning |
| --- | --- |
| TKey | Typen av elementen i **keys**‑arrayen |
| TValue | typen av elementen i **items**‑arrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keys | const ArrayPtr\<TKey\>\& | [Array](../) som innehåller nyckelvärden |
| items | const ArrayPtr\<TValue\>\& | [Array](../) som innehåller objekt som är mappade till nyckelvärdena i **keys**‑arrayen |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<TKey\>\&, const ArrayPtr\<TValue\>\&, int, int) method


Sorterar två arrayer, en som innehåller nycklar och den andra – motsvarande objekt, baserat på värdena i arrayen som innehåller nycklar, vars element jämförs med standardjämförare.

```cpp
template<typename TKey,typename TValue> static void System::Array<T>::Sort(const ArrayPtr<TKey> &keys, const ArrayPtr<TValue> &items, int index, int length)
```


| Parameter | Beskrivning |
| --- | --- |
| TKey | Typen av elementen i **keys**‑arrayen |
| TValue | typen av elementen i **items**‑arrayen |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| keys | const ArrayPtr\<TKey\>\& | [Array](../) som innehåller nyckelvärden |
| items | const ArrayPtr\<TValue\>\& | [Array](../) som innehåller objekt som är mappade till nyckelvärdena i **keys**‑arrayen |
| index | int | Indexet som anger början av intervallet att sortera |
| längd | int | Antalet element i intervallet att sortera |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&) method


Sorterar element i den angivna arrayen med standardjämförare.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Målararray |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) method


Sorterar element i den angivna arrayen med angiven jämförare.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Målararray |
| komparator | const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\& | IComparer<T> objekt som används för att jämföra element i arrayen |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, const SharedPtr\<System::Collections::Generic::IComparer\<Y\>\>\&) method


INTE IMPLEMENTERAD.

```cpp
template<typename Type,typename Y> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const SharedPtr<System::Collections::Generic::IComparer<Y>> &comparator)
```


## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, const System::Comparison\<T\>\&) method


Sorterar element i den angivna arrayen med angiven jämförelse.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, const System::Comparison<T> &comparison)
```

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Comparison](../../comparison/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Array::Sort(const ArrayPtr\<Type\>\&, int, int) method


Sorterar ett intervall av element i den angivna arrayen med standardjämförare.

```cpp
template<typename Type> static void System::Array<T>::Sort(const ArrayPtr<Type> &arr, int startIndex, int count)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const ArrayPtr\<Type\>\& | Målararray |
| startIndex | int | Indexet som anger början på intervallet av element som ska sorteras |
| count | int | Storleken på intervallet av element som ska sorteras |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
