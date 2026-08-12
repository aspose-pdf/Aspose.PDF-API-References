---
title: "System::Collections::Generic::Dictionary-klass"
linktitle: "Dictionary"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::Dictionary-klass. Framåtriktad deklaration av Dictionary-klass i C++."
type: docs
weight: 1100
url: /sv/cpp/system.collections.generic/dictionary/
---
## Dictionary class


Framåtriktad deklaration av [Dictionary](./) klass.

```cpp
template<typename TKey,typename TValue>class Dictionary : public System::Collections::Generic::BaseDictionary<std::unordered_map<TKey, TValue, EqualityComparerHashAdapter<TKey>, EqualityComparerAdapter<TKey>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
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
| [Dictionary](./dictionary/)() | Skapar tomt dictionary. |
| [Dictionary](./dictionary/)(const map_t\&) | Kopierar data från karta. |
| [Dictionary](./dictionary/)(int) | Överlagring som motsvarar att skapa förallokerat dictionary; allokerar faktiskt inget. |
| [Dictionary](./dictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) | Kopieringskonstruktor. |
| [Dictionary](./dictionary/)(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) | Kopieringskonstruktor. |
| [Dictionary](./dictionary/)(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) | Skapar tomt dictionary. |
| [Dictionary](./dictionary/)(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) | Skapar tomt dictionary. |
| [GetEnumerator](./getenumerator/)() override | Skapar enumeratorobjekt. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Pekare till enumerable‑gränssnitt. |
| [IEnumeratorPtr](./ienumeratorptr/) | Pekare till enumerator. |
| [KeyCollection](./keycollection/) | RTTI-information. |
| [KVPair](./kvpair/) | Nyckel‑värde‑par‑typ. |
| [map_t](./map_t/) | Underliggande datatyp. |
| [Ptr](./ptr/) | Pekartyp. |
| [ValueCollection](./valuecollection/) | Samling av värden att extrahera. |
## Anmärkningar


[Dictionary](./) that maps values to keys. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Skapa instansen av Dictionary-klassen.
  auto dictionary = MakeObject<Dictionary<int, String>>();

  // Fyll dictionary.
  dictionary->Add(0, u"Foo");
  dictionary->Add(1, u"Bar");
  dictionary->Add(2, u"Baz");

  // Skriv ut dictionary‑objekten.
  for (const auto &pair: dictionary)
  {
    std::cout << pair.get_Key() << " - " << pair.get_Value() << std::endl;
  }

  return 0;
}
/*
This code example produces the following output:
0 - Foo
1 - Bar
2 - Baz
*/
```

## Se även

* Class [BaseDictionary](../basedictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
