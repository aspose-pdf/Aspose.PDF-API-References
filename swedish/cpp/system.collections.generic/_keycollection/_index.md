---
title: "System::Collections::Generic::_KeyCollection klass"
linktitle: "_KeyCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::_KeyCollection klass. Samling av Dictionarys nycklar. Refererar till samlingen, kopierar ingenting. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.collections.generic/_keycollection/
---
## _KeyCollection class


Samling av [Dictionary](../dictionary/)'s nycklar. Refererar till samlingen, kopierar ingenting. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<typename Dict>class _KeyCollection : public System::Collections::Generic::BaseKVCollection<Dict, Dict::map_t::key_type>
```

## Nested classes

* Class [Enumerator](./enumerator/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [_KeyCollection](./_keycollection/)(const typename Dict::Ptr\&) | Initierar en samling som refererar till den angivna dictionaryn. |
| [Contains](./contains/)(const TKey\&) const override | Kontrollerar om objektet finns i behållaren. |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator som itererar genom nycklar. |
| [idx_get](./idx_get/)(int) const override | Implementerar [IList](../ilist/)‑metod. Stöds inte. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end iterator för den aktuella behållaren. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [TKey](./tkey/) | Nyckeltyp. |

## Se även

* Class [BaseKVCollection](../basekvcollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
