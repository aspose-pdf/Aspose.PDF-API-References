---
title: "System::Collections::Generic::BaseSet::Enumerator klass"
linktitle: "Enumerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::BaseSet::Enumerator klass. Enumerator-klass. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2800
url: /sv/cpp/system.collections.generic/baseset/enumerator/
---
## Enumerator class


[Enumerator](./) class. Objects of this class should only be allocated using [System::MakeObject()](../../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Enumerator : public System::Collections::Generic::SimpleEnumerator<set_t>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Enumerator](./enumerator/)(const ThisPtr\&) | Skapar en enumerator som itererar genom **set**-objektet. |
## Se även

* Class [SimpleEnumerator](../../simpleenumerator/)
* Class [BaseSet](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
