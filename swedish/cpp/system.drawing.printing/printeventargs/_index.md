---
title: "System::Drawing::Printing::PrintEventArgs klass"
linktitle: "PrintEventArgs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Printing::PrintEventArgs klass. Tillhandahåller data för BeginPrint- och EndPrint‑händelserna. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 800
url: /sv/cpp/system.drawing.printing/printeventargs/
---
## PrintEventArgs class


Tillhandahåller data för BeginPrint- och EndPrint‑händelserna. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class PrintEventArgs : public System::ComponentModel::CancelEventArgs
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_PrintAction](./get_printaction/)() | Returnerar ett värde som specificerar en utskriftsåtgärd som representeras av det aktuella objektet. |
| [PrintEventArgs](./printeventargs/)() | Skapar en ny instans av [PrintEventArgs](./)‑objektet. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | En statisk medlem som representerar en "tom" [EventArgs](../../system/eventargs/) delad pekare (nullpekare). |
## Se även

* Class [CancelEventArgs](../../system.componentmodel/canceleventargs/)
* Namespace [System::Drawing::Printing](../)
* Library [Aspose.PDF for C++](../../)
