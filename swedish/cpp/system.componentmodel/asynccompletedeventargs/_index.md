---
title: "System::ComponentModel::AsyncCompletedEventArgs klass"
linktitle: "AsyncCompletedEventArgs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ComponentModel::AsyncCompletedEventArgs klass. En instans av denna klass skickas som argument till AsyncCompletedEventHandler‑delegaten. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.componentmodel/asynccompletedeventargs/
---
## AsyncCompletedEventArgs class


En instans av den här klassen skickas som argument till AsyncCompletedEventHandler-delegaten. Objekt av den här klassen bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class AsyncCompletedEventArgs : public System::EventArgs
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AsyncCompletedEventArgs](./asynccompletedeventargs/)() | Konstruktor. |
| [AsyncCompletedEventArgs](./asynccompletedeventargs/)(const System::Exception\&, bool, const System::SharedPtr\<System::Object\>\&) | Initierar en ny instans av klassen [System.ComponentModel.AsyncCompletedEventArgs](./). |
| [get_Cancelled](./get_cancelled/)() const | Hämtar ett värde som indikerar om en asynkron operation har avbrutits. true om bakgrundsoperationen har avbrutits; annars false. Standardvärdet är false. |
| [get_Error](./get_error/)() const | Hämtar ett värde som indikerar vilket fel som inträffade under en asynkron operation. |
| [get_UserState](./get_userstate/)() const | Hämtar den unika identifieraren för den asynkrona uppgiften. En objektreferens som unikt identifierar den asynkrona uppgiften; annars null om inget värde har satts. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | En statisk medlem som representerar en "tom" [EventArgs](../../system/eventargs/) delad pekare (nullpekare). |
## Se även

* Class [EventArgs](../../system/eventargs/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
