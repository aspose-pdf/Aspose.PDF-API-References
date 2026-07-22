---
title: "System::ComponentModel::PropertyChangedEventArgs klass"
linktitle: "PropertyChangedEventArgs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ComponentModel::PropertyChangedEventArgs klass. Argument för PropertyChanged‑händelsen. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1200
url: /sv/cpp/system.componentmodel/propertychangedeventargs/
---
## PropertyChangedEventArgs class


Argument för PropertyChanged‑händelsen. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class PropertyChangedEventArgs : public System::EventArgs
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_PropertyName](./get_propertyname/)() | RTTI-information. |
| [PropertyChangedEventArgs](./propertychangedeventargs/)(const String\&) | Initierar argument för PropertyChanged‑händelsen. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | En statisk medlem som representerar en "tom" [EventArgs](../../system/eventargs/) delad pekare (nullpekare). |
## Se även

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
