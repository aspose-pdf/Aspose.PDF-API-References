---
title: "System::Collections::Generic::IDictionary klass"
linktitle: "IDictionary"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::IDictionary klass. Gränssnitt för behållare som liknar ordböcker. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid in denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2100
url: /sv/cpp/system.collections.generic/idictionary/
---
## IDictionary class


Gränssnitt för behållare som liknar ordböcker. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid in denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<typename TKey,typename TValue>class IDictionary : public System::Collections::Generic::ICollection<KeyValuePair<TKey, TValue>>
```


| Parameter | Beskrivning |
| --- | --- |
| TKey | Nyckeltyp. |
| TValue | Värdetyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Add](./add/)(const TKey\&, const TValue\&) | Lägger till ett nyckel‑värdepar i behållaren. |
| virtual [ContainsKey](./containskey/)(const TKey\&) const | Kontrollerar om behållaren innehåller nyckeln. |
| [CopyTo](./copyto/)(ArrayPtr\<KeyValuePair\<TKey, TValue\>\>, int) override | Kopierar ordboksinnehåll till befintliga array‑element. |
| virtual [get_Count](./get_count/)() const | Avslöjar medlemsfunktionen get_Count. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Kontrollerar om samlingens storlek är fast. |
| [get_IsSynchronized](./get_issynchronized/)() const | Kontrollerar om behållaren är trådsäker. |
| virtual [get_Keys](./get_keys/)() const | Kommer åt nyckelsamlingen. |
| virtual [get_Values](./get_values/)() const | Kommer åt värdesamlingen. |
| virtual [GetValueOrDefault](./getvalueordefault/)(const TKey\&) const | Returnerar värdet om det hittas; annars **Value()**. |
| virtual [GetValueOrDefault](./getvalueordefault/)(const TKey\&, const TValue\&) const | Returnerar värdet om det hittas; annars **defaultValue**. |
| virtual [GetValueOrNull](./getvalueornull/)(const TKey\&) const | Returnerar värdet om det hittas; annars **null**, meningsfullt endast för referenstyper. |
| virtual [idx_get](./idx_get/)(const TKey\&) const | Getter-funktion. |
| virtual [idx_set](./idx_set/)(const TKey\&, TValue) | Setter-funktion. |
| virtual [Remove](./remove/)(const TKey\&) | Tar bort nyckeln från behållaren. |
| virtual [TryGetValue](./trygetvalue/)(const TKey\&, TValue\&) const | Söker efter värdet och hämtar det om det hittas. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [BaseType](./basetype/) | RTTI-information. |
| [KeyValuePairType](./keyvaluepairtype/) | Typ för nyckel‑värde‑par. |

## Se även

* Class [ICollection](../icollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
