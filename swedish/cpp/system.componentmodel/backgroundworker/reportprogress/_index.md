---
title: "System::ComponentModel::BackgroundWorker::ReportProgress metod"
linktitle: "ReportProgress"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ComponentModel::BackgroundWorker::ReportProgress metod. Höjer System::ComponentModel::BackgroundWorker::ProgressChanged‑händelsen i C++."
type: docs
weight: 400
url: /sv/cpp/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) method


Utlöser händelsen **System::ComponentModel::BackgroundWorker::ProgressChanged**.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| percentProgress | int | Procentandelen, från 0 till 100, av bakgrundsoperationen som är klar. |

## Se även

* Class [BackgroundWorker](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) method


Utlöser händelsen **System::ComponentModel::BackgroundWorker::ProgressChanged** med userState‑objekt.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| percentProgress | int | Procentandelen, från 0 till 100, av bakgrundsoperationen som är klar. |
| userState | const System::SharedPtr\<System::Object\>\& | Tillståndsobjektet som skickas till System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [BackgroundWorker](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
