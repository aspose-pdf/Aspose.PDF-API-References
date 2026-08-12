---
title: "System::ComponentModel::CancelEventArgs-klass"
linktitle: "CancelEventArgs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ComponentModel::CancelEventArgs-klass. Argument för avbrytbar händelse. Objekt av den här klassen bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.componentmodel/canceleventargs/
---
## CancelEventArgs class


Argument för avbrytbar händelse. Objekt av den här klassen bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class CancelEventArgs : public System::EventArgs
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CancelEventArgs](./canceleventargs/)(bool) | RTTI-information. |
| [CancelEventArgs](./canceleventargs/)() | Konstruktor; sätter Cancel-egenskapen till false. |
| [get_Cancel](./get_cancel/)() | Hämtar värde som indikerar om händelsen ska avbrytas. |
| [set_Cancel](./set_cancel/)(bool) | Sätter värde som indikerar om händelsen ska avbrytas. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | En statisk medlem som representerar en "tom" [EventArgs](../../system/eventargs/) delad pekare (nullpekare). |
## Se även

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
