---
title: "System::Collections::Generic::SortedList::Enumerator klass"
linktitle: "Enumerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::SortedList::Enumerator klass. Enumerator-klass för att iterera genom listan. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2600
url: /sv/cpp/system.collections.generic/sortedlist/enumerator/
---
## Enumerator class


[Enumerator](./) class to iterate through list. Objects of this class should only be allocated using [System::MakeObject()](../../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Enumerator : public System::Collections::Generic::SimpleEnumerator<map_t, KVPair>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Enumerator](./enumerator/)(const Ptr\&) | Skapar enumerator som itererar genom en specifik dictionary. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [EnumeratorType](./enumeratortype/) | typalias för [Enumerator](./). |
## Se även

* Class [SimpleEnumerator](../../simpleenumerator/)
* Class [SortedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
