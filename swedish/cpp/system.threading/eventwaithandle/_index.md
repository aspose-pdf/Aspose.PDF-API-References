---
title: "System::Threading::EventWaitHandle klass"
linktitle: "EventWaitHandle"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::EventWaitHandle-klass. Händelse som kan skickas till väntande tråd. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 500
url: /sv/cpp/system.threading/eventwaithandle/
---
## EventWaitHandle class


[Event](../../system/event/) that can be sent to waiting thread. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EventWaitHandle : public System::Threading::WaitHandle
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [EventWaitHandle](./eventwaithandle/)(bool, EventResetMode) | RTTI-information. |
| virtual [Reset](./reset/)() | Sätter händelsen till icke-signaliserande tillstånd. |
| virtual [Set](./set/)() | Sätter händelsen till signaliserande tillstånd. |
| [~EventWaitHandle](./~eventwaithandle/)() | Destruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Speciellt värde som ska returneras av funktionen annars returneras index för signaliserat objekt i arrayen, om tidsgränsen överskrids och inget signalerar. |
## Se även

* Class [WaitHandle](../waithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
