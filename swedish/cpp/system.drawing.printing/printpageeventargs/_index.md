---
title: "System::Drawing::Printing::PrintPageEventArgs-klass"
linktitle: "PrintPageEventArgs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Printing::PrintPageEventArgs-klass. Tillhandahåller data för PrintPage‑händelsen. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 900
url: /sv/cpp/system.drawing.printing/printpageeventargs/
---
## PrintPageEventArgs class


Tillhandahåller data för PrintPage‑händelsen. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class PrintPageEventArgs : public System::EventArgs
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Graphics](./get_graphics/)() | INTE IMPLEMENTERAD. |
| [get_HasMorePages](./get_hasmorepages/)() | INTE IMPLEMENTERAD. |
| [get_PageSettings](./get_pagesettings/)() | INTE IMPLEMENTERAD. |
| [PrintPageEventArgs](./printpageeventargs/)(const SharedPtr\<Graphics\>\&, const SharedPtr\<Rectangle\>\&, const SharedPtr\<Rectangle\>\&, const SharedPtr\<PageSettings\>\&) | Skapar en ny instans av [PrintPageEventArgs](./)-klassen. |
| [set_HasMorePages](./set_hasmorepages/)(bool) | INTE IMPLEMENTERAD. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | En statisk medlem som representerar en "tom" [EventArgs](../../system/eventargs/) delad pekare (nullpekare). |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |
## Se även

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::Drawing::Printing](../)
* Library [Aspose.PDF for C++](../../)
