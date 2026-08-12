---
title: "System::Collections::Generic::SortedDictionary klass"
linktitle: "SortedDictionary"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::SortedDictionary klass. Framåtriktad deklaration av sorterad ordbokstyp i C++."
type: docs
weight: 4000
url: /sv/cpp/system.collections.generic/sorteddictionary/
---
## SortedDictionary class


Framåtriktad deklaration av sorterad ordbokstyp.

```cpp
template<typename TKey,typename TValue>class SortedDictionary : public System::Collections::Generic::BaseDictionary<std::map<TKey, TValue, ComparerAdapter<BasePointerType<TKey>::type>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
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
| [get_Comparer](./get_comparer/)() const | Hämtar [IComparer<TKey>](../icomparer/) som används för att sortera elementen i SortedDictionary<TKey,TValue>. |
| static [GetDefaultKeyComparer](./getdefaultkeycomparer/)() | Singleton-åtkomstfunktion. |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator för att iterera genom den aktuella ordboken. |
| [rbegin](./rbegin/)() | Hämtar en omvänd iterator till det sista elementet i samlingen (första i omvänd ordning). |
| [rbegin](./rbegin/)() const | Hämtar en omvänd iterator till det sista elementet i den const‑kvalificerade samlingen (första i omvänd ordning). |
| [rend](./rend/)() | Hämtar en omvänd iterator för ett icke‑existerande element före samlingens början. |
| [rend](./rend/)() const | Hämtar en omvänd iterator för ett icke‑existerande element före den const‑kvalificerade samlingens början. |
| [SortedDictionary](./sorteddictionary/)() | Skapar en tom ordbok. |
| [SortedDictionary](./sorteddictionary/)(const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) | Skapar en tom ordbok. |
| [SortedDictionary](./sorteddictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) | Kopieringskonstruktor. |
| [SortedDictionary](./sorteddictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IComparer\<typename BasePointerType\<TKey\>::type\>\>\&) | Kopieringskonstruktor. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [const_iterator](./const_iterator/) | Typ för konstant iterator. |
| [const_reverse_iterator](./const_reverse_iterator/) | Typ för konstant omvänd iterator. |
| [IEnumerablePtr](./ienumerableptr/) | Samling av samma element. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) typ. |
| [iterator](./iterator/) | Iterator-typ. |
| [KeyCollection](./keycollection/) | Nyckelsamlingstyp. |
| [KVPair](./kvpair/) | Nyckel‑värde‑par‑typ. |
| [map_t](./map_t/) | Underliggande datatyp. |
| [Ptr](./ptr/) | Pekartyp. |
| [reverse_iterator](./reverse_iterator/) | Omvänd iterator-typ. |
| [this_t](./this_t/) | Självtyp. |
| [ValueCollection](./valuecollection/) | Värdesamlingstyp. |
## Anmärkningar


Sorterad ordboksklass som omsluter STL‑map. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

## Se även

* Class [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
