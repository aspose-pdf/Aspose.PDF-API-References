---
title: "System::Collections::Generic::Stack::Enumerator klass"
linktitle: "Enumerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::Stack::Enumerator klass. Uppräkning för att iterera genom stacken. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller assert‑fel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2000
url: /sv/cpp/system.collections.generic/stack/enumerator/
---
## Enumerator class


[Enumerator](./) to iterate through stack. Objects of this class should only be allocated using [System::MakeObject()](../../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Enumerator : public System::Collections::Generic::ReverseEnumerator<stack_t>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Enumerator](./enumerator/)(const ThisPtr\&) | Skapar en uppräkning som itererar genom den angivna stacken. |
## Se även

* Class [ReverseEnumerator](../../reverseenumerator/)
* Class [Stack](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
