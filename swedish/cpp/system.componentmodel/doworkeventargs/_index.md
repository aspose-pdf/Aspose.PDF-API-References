---
title: "System::ComponentModel::DoWorkEventArgs-klass"
linktitle: "DoWorkEventArgs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ComponentModel::DoWorkEventArgs-klass. DoWork‑händelseargument. Objekt av den här klassen bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.componentmodel/doworkeventargs/
---
## DoWorkEventArgs class


DoWork‑händelseargument. Objekt av den här klassen bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class DoWorkEventArgs : public System::ComponentModel::CancelEventArgs
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [DoWorkEventArgs](./doworkeventargs/)(const SharedPtr\<System::Object\>\&) | RTTI-information. |
| [get_Argument](./get_argument/)() | Hämtar Argument‑egenskapen; inte implementerad. |
| [get_Result](./get_result/)() | Hämtar Result‑egenskapen; inte implementerad. |
| [set_Result](./set_result/)(const SharedPtr\<System::Object\>\&) | Sätter Result‑egenskapen; inte implementerad. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | En statisk medlem som representerar en "tom" [EventArgs](../../system/eventargs/) delad pekare (nullpekare). |
## Se även

* Class [CancelEventArgs](../canceleventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
