---
title: "System::Collections::Generic::BaseDictionary klass"
linktitle: "BaseDictionary"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::BaseDictionary klass. Implementerar gemensam kod för olika dictionary‑liknande datastrukturer (t.ex. Dictionary, SortedDictionary). Bör inte användas direkt, förutom vid arv när containrar definieras. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 500
url: /sv/cpp/system.collections.generic/basedictionary/
---
## BaseDictionary class


Implementerar gemensam kod för olika dictionary‑liknande datastrukturer (t.ex. [Dictionary](../dictionary/), [SortedDictionary](../sorteddictionary/)). Bör inte användas direkt, förutom vid arv när containrar definieras. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
template<typename Map>class BaseDictionary : public System::Collections::Generic::IDictionary<Map::key_type, Map::mapped_type>
```


| Parameter | Beskrivning |
| --- | --- |
| Map | Underliggande karttyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [_add_range](./_add_range/)(std::initializer_list\<typename Map::value_type\>) | C++-specifik. |
| [Add](./add/)(const key_t\&, const mapped_t\&) override | Lägger till ett nyckel‑värde‑par i dictionary. |
| [BaseDictionary](./basedictionary/)() | Skapar en tom datastruktur. |
| [BaseDictionary](./basedictionary/)(int, const Args\&...) | Vidarebefordrande konstruktor för att skicka argument till den underliggande kartkonstruktorn. |
| [BaseDictionary](./basedictionary/)(BaseType *, const Args\&...) | Kopieringskonstruktor. |
| [BaseDictionary](./basedictionary/)(BaseType *) | Kopieringskonstruktor. |
| [begin](./begin/)() const | Returnerar en iterator till KVPair‑omslag för nyckel‑värde‑elementet i behållaren. Implementerad i C#‑stil – iteratorn ska returnera KVPair‑objektet med get_Key() och get_Value()‑gränssnitt. Om behållaren är tom kommer den returnerade iteratorn att vara lika med [end()](../ienumerable/end/). |
| [cbegin](./cbegin/)() const | Returnerar en iterator till det första elementet i behållaren. Implementerad i STL‑stil. Om behållaren är tom kommer den returnerade iteratorn att vara lika med [end()](../ienumerable/end/). |
| [cend](./cend/)() const | Returnerar en iterator till elementet som följer efter det sista elementet i behållaren. Implementerad i STL‑stil. Detta element fungerar som en platshållare; försök att komma åt det resulterar i odefinierat beteende. |
| [Clear](./clear/)() override | Raderar alla element. |
| [ContainsKey](./containskey/)(const key_t\&) const override | Kontrollerar om nyckeln finns i ordboken. |
| [ContainsValue](./containsvalue/)(const mapped_t\&) | Kontrollerar om värdet finns i ordboken. Använder operatorn == för att jämföra värden. |
| [data](./data/)() | Underliggande datalagringsåtkomst. |
| [data](./data/)() const | Underliggande datalagringsåtkomst. |
| [end](./end/)() const | Returnerar en iterator till KVPair-wrappern för nyckel‑värde‑elementet som följer det sista elementet i behållaren. Implementerad i C#‑stil – iteratorn bör returnera KVPair‑objektet med get_Key() och get_Value()‑gränssnittet. Detta element fungerar som en platshållare; försök att komma åt det resulterar i odefinierat beteende. |
| [get_Count](./get_count/)() const override | Hämtar antalet element. |
| virtual [GetEnumerator](./getenumerator/)() | Skapar en enumeratorinstans, bör implementeras av underklass. |
| [GetValueOrDefault](./getvalueordefault/)(const key_t\&) const override | Returnerar värdet om det hittas; annars **Value()**. |
| [GetValueOrDefault](./getvalueordefault/)(const key_t\&, const mapped_t\&) const override | Returnerar värdet om det hittas; annars **defaultValue**. |
| [GetValueOrNull](./getvalueornull/)(const key_t\&) const override | Returnerar värdet om det hittas; annars **null**. Gäller endast för referenstyper. |
| [idx_get](./idx_get/)(const key_t\&) const override | Nyckelbaserad getter‑funktion. |
| [idx_set](./idx_set/)(const key_t\&, mapped_t) override | Nyckelbaserad setter‑funktion. Ändrar eller skapar element. |
| virtual [operator[]](./operator[]/)(const key_t\&) | Åtkomstfunktion. |
| [Remove](./remove/)(const key_t\&) override | Tar bort en specifik nyckel från ordboken. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(unsigned int) override |  |
| [TryGetValue](./trygetvalue/)(const key_t\&, mapped_t\&) const override | Söker efter nyckelvärde och hämtar det om det hittas. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end iterator för den aktuella behållaren. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [BaseType](./basetype/) | Implementerat gränssnitt. |
| [const_iterator](./const_iterator/) | Typ för konstant iterator. |
| [iterator](./iterator/) | Iterator-typ. |
| [KeyCollection](./keycollection/) | Se till att vi använder rätt allokerare med den underliggande lagringstypen. |
| [KVPair](./kvpair/) | Nyckel‑värde‑par‑typ. |
| [map_t](./map_t/) | Intern karttyp. |
| [ValueCollection](./valuecollection/) | Samling av värden. |

## Se även

* Class [IDictionary](../idictionary/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
