---
title: "System::Threading::Semaphore-klass"
linktitle: "Semaphore"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Semaphore-klass. Semaphore-implementation. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1000
url: /sv/cpp/system.threading/semaphore/
---
## Semaphore class


[Semaphore](./) implementation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Semaphore : public System::Threading::WaitHandle
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Release](./release/)() | Frigör lås på semafor. |
| [Release](./release/)(int) | Frigör flera lås på semafor. |
| virtual [Reset](./reset/)() | Sätter semafor till icke-signaliserat tillstånd. Stöds inte. |
| [Semaphore](./semaphore/)(int, int) | RTTI-information. |
| [Semaphore](./semaphore/)(int, int, const String\&) | Skapar namngiven semafor. |
| [Semaphore](./semaphore/)(int, int, const String\&, bool\&) | Skapar namngiven semafor. |
| virtual [Set](./set/)() | Sätter semafor till signaliserat tillstånd. Stöds inte. |
| [WaitOne](./waitone/)() override | Låser semafor. Utför obegränsad väntan om nödvändigt. |
| [WaitOne](./waitone/)(int) override | Låser semafor. Utför väntan om nödvändigt. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Speciellt värde som ska returneras av funktionen annars returneras index för signaliserat objekt i arrayen, om tidsgränsen överskrids och inget signalerar. |
## Se även

* Class [WaitHandle](../waithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
