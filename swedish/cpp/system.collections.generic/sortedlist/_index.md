---
title: "System::Collections::Generic::SortedList-klass"
linktitle: "SortedList"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::SortedList-klass. Sorterad lista som omsluter FlatMap-struktur. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 4200
url: /sv/cpp/system.collections.generic/sortedlist/
---
## SortedList class


Sorterad lista som omsluter FlatMap-struktur. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
template<typename TKey,typename TValue>class SortedList : public System::Collections::Generic::SortedListHelper<TKey, TValue>,
                                                          public System::Collections::Generic::BaseDictionary<Detail::FlatMap<TKey, TValue, ComparerAdapter<TKey>>>
```


| Parameter | Beskrivning |
| --- | --- |
| TKey | Nyckeltyp. |
| TValue | Värdetyp. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [crbegin](./crbegin/)() const | Hämtar en omvänd iterator till det sista const‑kvalificerade elementet i samlingen (första i omvänd ordning). |
| [crend](./crend/)() const | Hämtar en omvänd iterator för ett icke‑existerande const‑kvalificerat element före samlingens början. |
| [get_Capacity](./get_capacity/)() const | Hämtar aktuell listkapacitet. |
| virtual [get_Keys](./get_keys/)() const | Kommer åt nyckelsamlingen. |
| virtual [get_Values](./get_values/)() const | Kommer åt värdesamlingen. |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator som itererar genom den aktuella listan. |
| [IndexOfKey](./indexofkey/)(TKey) const | Söker efter en specifik nyckel. |
| [IndexOfValue](./indexofvalue/)(TValue) const | Söker efter ett specifikt värde. |
| [rbegin](./rbegin/)() | Hämtar en omvänd iterator till det sista elementet i samlingen (första i omvänd ordning). |
| [rbegin](./rbegin/)() const | Hämtar en omvänd iterator till det sista elementet i den const‑kvalificerade samlingen (första i omvänd ordning). |
| [RemoveAt](./removeat/)(int) | Tar bort objektet på angiven position. |
| [rend](./rend/)() | Hämtar en omvänd iterator för ett icke‑existerande element före samlingens början. |
| [rend](./rend/)() const | Hämtar en omvänd iterator för ett icke‑existerande element före den const‑kvalificerade samlingens början. |
| [set_Capacity](./set_capacity/)(int) | Ställer in kapaciteten för den aktuella listan. |
| [SortedList](./sortedlist/)() | Skapar en tom lista. |
| [SortedList](./sortedlist/)(const SharedPtr\<IComparer\<TKey\>\>\&) | Skapar en tom lista. |
| [SortedList](./sortedlist/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) | Kopieringskonstruktor. |
| [SortedList](./sortedlist/)(const map_t\&) | Kopieringskonstruktor. |
| [SortedList](./sortedlist/)(int) | Skapar en tom lista. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [const_iterator](./const_iterator/) | Typ för konstant iterator. |
| [const_reverse_iterator](./const_reverse_iterator/) | Typ för konstant omvänd iterator. |
| [IEnumerablePtr](./ienumerableptr/) | Samling av samma par-typ. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) typ. |
| [iterator](./iterator/) | Iterator-typ. |
| [KeyCollection](./keycollection/) | Nyckelsamlingstyp. |
| [KVPair](./kvpair/) | Typ för nyckel‑värde‑par. |
| [map_t](./map_t/) | Underliggande datatyp. |
| [Ptr](./ptr/) | Pekartyp. |
| [reverse_iterator](./reverse_iterator/) | Omvänd iterator-typ. |
| [this_t](./this_t/) | Denna typ. |
| [ValueCollection](./valuecollection/) | Värdesamlingstyp. |

## Se även

* Class [SortedListHelper](../sortedlisthelper/)
* Class [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
