---
title: "System::Web::Services::Protocols::InvokeCompletedEventArgs klass"
linktitle: "InvokeCompletedEventArgs"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Web::Services::Protocols::InvokeCompletedEventArgs klass. En instans av denna klass skickas som argument till InvokeCompletedEventHandler-delegaten. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system.web.services.protocols/invokecompletedeventargs/
---
## InvokeCompletedEventArgs class


En instans av denna klass skickas som argument till InvokeCompletedEventHandler-delegaten. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class InvokeCompletedEventArgs : public System::ComponentModel::AsyncCompletedEventArgs
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Results](./get_results/)() | Returnerar en samling av asynkrona operationsresultat. |
| [InvokeCompletedEventArgs](./invokecompletedeventargs/)(Exception, bool, System::SharedPtr\<Object\>, System::ArrayPtr\<System::SharedPtr\<Object\>\>) | Skapar en ny instans. |
## Fält

| Fält | Beskrivning |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | En statisk medlem som representerar en "tom" [EventArgs](../../system/eventargs/) delad pekare (nullpekare). |
## Se även

* Class [AsyncCompletedEventArgs](../../system.componentmodel/asynccompletedeventargs/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.PDF for C++](../../)
