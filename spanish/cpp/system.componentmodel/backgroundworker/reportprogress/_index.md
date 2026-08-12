---
title: "System::ComponentModel::BackgroundWorker::ReportProgress método"
linktitle: "ReportProgress"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::ComponentModel::BackgroundWorker::ReportProgress método. Genera el evento System::ComponentModel::BackgroundWorker::ProgressChanged en C++."
type: docs
weight: 400
url: /es/cpp/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) method


Genera el evento **System::ComponentModel::BackgroundWorker::ProgressChanged**.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| percentProgress | int | El porcentaje, de 0 a 100, de la operación en segundo plano que está completa. |

## Ver también

* Class [BackgroundWorker](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) method


Genera el evento **System::ComponentModel::BackgroundWorker::ProgressChanged** con el objeto userState.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| percentProgress | int | El porcentaje, de 0 a 100, de la operación en segundo plano que está completa. |
| userState | const System::SharedPtr\<System::Object\>\& | El objeto de estado pasado a System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [BackgroundWorker](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
