---
title: "System::Collections::Generic::List::Enumerator class"
linktitle: "Enumerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::List::Enumerator class. Uppräkning för att iterera genom listelementen. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 6100
url: /sv/cpp/system.collections.generic/list/enumerator/
---
## Enumerator class


[Enumerator](./) to iterate through list elements. Objects of this class should only be allocated using [System::MakeObject()](../../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Enumerator : public System::Collections::Generic::SimpleEnumerator<vector_t>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Enumerator](./enumerator/)(const ThisPtr\&) | Skapar en uppräkning som itererar genom en specifik lista. |
## Se även

* Class [SimpleEnumerator](../../simpleenumerator/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
