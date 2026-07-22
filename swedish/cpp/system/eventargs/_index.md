---
title: "System::EventArgs‑klass"
linktitle: "EventArgs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::EventArgs‑klass. Bas‑klassen för klasser som representerar ett sammanhang som skickas till händelseprenumeranter när en händelse utlöses. Objekt av denna klass bör endast allokeras med System::MakeObject() funktion. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2600
url: /sv/cpp/system/eventargs/
---
## EventArgs class


Bas‑klassen för klasser som representerar ett sammanhang som skickas till händelseprenumeranter när en händelse utlöses. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/) funktion. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class EventArgs : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [EventArgs](./eventargs/)() | Konstruktor. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](./empty/) | En statisk medlem som representerar en "empty" [EventArgs](./) shared pointer (null-pointer). |
## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
