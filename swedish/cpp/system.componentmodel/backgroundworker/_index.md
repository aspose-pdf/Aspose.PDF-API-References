---
title: "System::ComponentModel::BackgroundWorker-klass"
linktitle: "BackgroundWorker"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ComponentModel::BackgroundWorker-klass. Objekt av den här klassen bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 200
url: /sv/cpp/system.componentmodel/backgroundworker/
---
## BackgroundWorker class


Objekt av den här klassen bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körningsfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class BackgroundWorker : public System::ComponentModel::Component
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BackgroundWorker](./backgroundworker/)() | RTTI-information. |
| [get_WorkerReportsProgress](./get_workerreportsprogress/)() const | Hämtar ett värde som indikerar om [System::ComponentModel::BackgroundWorker](./) kan rapportera förloppsuppdateringar. |
| [ReportProgress](./reportprogress/)(int) | Utlöser händelsen **System::ComponentModel::BackgroundWorker::ProgressChanged**. |
| [ReportProgress](./reportprogress/)(int, const System::SharedPtr\<System::Object\>\&) | Utlöser händelsen **System::ComponentModel::BackgroundWorker::ProgressChanged** med userState‑objekt. |
| [RunWorkerAsync](./runworkerasync/)() | Startar exekveringen av en bakgrundsoperation. |
| [RunWorkerAsync](./runworkerasync/)(const System::SharedPtr\<System::Object\>\&) | Startar exekveringen av en bakgrundsoperation. |
| [set_WorkerReportsProgress](./set_workerreportsprogress/)(bool) | Sätter ett värde som indikerar om [System::ComponentModel::BackgroundWorker](./) kan rapportera förloppsuppdateringar. |
| [~BackgroundWorker](./~backgroundworker/)() | Destruktor. |
## Se även

* Class [Component](../component/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
