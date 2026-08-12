---
title: "System::Threading::ManualResetEvent klass"
linktitle: "ManualResetEvent"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::ManualResetEvent klass. Händelse för att meddela väntande tråd som inte återställs automatiskt. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 700
url: /sv/cpp/system.threading/manualresetevent/
---
## ManualResetEvent class


[Event](../../system/event/) to notify waiting thread that does not reset automatically. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ManualResetEvent : public System::Threading::EventWaitHandle
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ManualResetEvent](./manualresetevent/)(bool) | RTTI-information. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | Speciellt värde som ska returneras av funktionen annars returneras index för signaliserat objekt i arrayen, om tidsgränsen överskrids och inget signalerar. |
## Se även

* Class [EventWaitHandle](../eventwaithandle/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
