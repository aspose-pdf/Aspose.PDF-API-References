---
title: "System::Collections::Generic::_ValueCollection-klass"
linktitle: "_ValueCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::_ValueCollection-klass. Samling av Dictionary:s värden. Refererar till samlingen, kopierar ingenting. Objekt av denna klass bör endast allokeras med System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.collections.generic/_valuecollection/
---
## _ValueCollection class


Samling av [Dictionary](../dictionary/)-värden. Refererar till samlingen, kopierar ingenting. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<typename Dict>class _ValueCollection : public System::Collections::Generic::BaseKVCollection<Dict, Dict::map_t::mapped_type>
```

## Nested classes

* Class [Enumerator](./enumerator/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [_ValueCollection](./_valuecollection/)(const typename Dict::Ptr\&) | Initierar en samling som refererar till den angivna dictionaryn. |
| [Contains](./contains/)(const TValue\&) const override | Kontrollerar om objektet finns i behållaren. |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator som itererar genom värden. |
| [idx_get](./idx_get/)(int) const override | Implementerar [IList](../ilist/)‑metod. Stöds inte. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end iterator för den aktuella behållaren. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [TValue](./tvalue/) | Värdetyp. |

## Se även

* Class [BaseKVCollection](../basekvcollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
