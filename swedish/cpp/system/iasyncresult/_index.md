---
title: "System::IAsyncResult-klass"
linktitle: "IAsyncResult"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IAsyncResult-klass. Representerar status för en asynkron operation. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 3200
url: /sv/cpp/system/iasyncresult/
---
## IAsyncResult class


Representerar status för en asynkron operation. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class IAsyncResult : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_AsyncState](./get_asyncstate/)() | Returnerar ett objekt som innehåller information om en asynkron operation. |
| virtual [get_AsyncWaitHandle](./get_asyncwaithandle/)() | Returnerar en instans av WaitHandle som kan användas för att vänta på att den asynkrona operationen ska slutföras. |
| virtual [get_CompletedSynchronously](./get_completedsynchronously/)() | Returnerar ett värde som indikerar om den asynkrona operationen slutfördes synkront. |
| virtual [get_IsCompleted](./get_iscompleted/)() | Returnerar ett värde som indikerar om den asynkrona operationen har slutförts. |
| virtual [~IAsyncResult](./~iasyncresult/)() | Destruktor. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [smart_ptr](./smart_ptr/) | Delad pekare till [IAsyncResult](./). |
## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
