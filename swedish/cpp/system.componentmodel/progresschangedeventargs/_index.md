---
title: "System::ComponentModel::ProgressChangedEventArgs-klass"
linktitle: "ProgressChangedEventArgs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ComponentModel::ProgressChangedEventArgs-klass. En instans av denna klass skickas som argument till delegaten ProgressChangedEventHandler. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1100
url: /sv/cpp/system.componentmodel/progresschangedeventargs/
---
## ProgressChangedEventArgs class


En instans av denna klass skickas som argument till delegaten ProgressChangedEventHandler. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ProgressChangedEventArgs : public System::EventArgs
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_ProgressPercentage](./get_progresspercentage/)() const | Hämtar den asynkrona uppgiftens förloppsprocent. |
| [get_UserState](./get_userstate/)() const | Hämtar ett unikt användartillstånd. |
| [ProgressChangedEventArgs](./progresschangedeventargs/)(int, System::SharedPtr\<System::Object\>) | Konstruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | En statisk medlem som representerar en "tom" [EventArgs](../../system/eventargs/) delad pekare (nullpekare). |
## Se även

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
