---
title: "System::ComponentModel::RunWorkerCompletedEventArgs class"
linktitle: "RunWorkerCompletedEventArgs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ComponentModel::RunWorkerCompletedEventArgs class. En instans av denna klass skickas som argument till RunWorkerCompletedEventHandler‑delegaten. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert‑fel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1300
url: /sv/cpp/system.componentmodel/runworkercompletedeventargs/
---
## RunWorkerCompletedEventArgs class


En instans av denna klass skickas som argument till RunWorkerCompletedEventHandler‑delegaten. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert‑fel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class RunWorkerCompletedEventArgs : public System::ComponentModel::AsyncCompletedEventArgs
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Result](./get_result/)() const | Hämtar ett värde som representerar resultatet av en asynkron operation. |
| [RunWorkerCompletedEventArgs](./runworkercompletedeventargs/)(const System::SharedPtr\<System::Object\>\&, const System::Exception\&, bool) | RTTI-information. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | En statisk medlem som representerar en "tom" [EventArgs](../../system/eventargs/) delad pekare (nullpekare). |
## Se även

* Class [AsyncCompletedEventArgs](../asynccompletedeventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
