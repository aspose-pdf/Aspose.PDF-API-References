---
title: System::ComponentModel::BackgroundWorker::ReportProgress method
linktitle: ReportProgress
second_title: Aspose.PDF for C++ API Reference
description: 'System::ComponentModel::BackgroundWorker::ReportProgress method. Raises the System::ComponentModel::BackgroundWorker::ProgressChanged event in C++.'
type: docs
weight: 400
url: /cpp/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) method


Raises the **System::ComponentModel::BackgroundWorker::ProgressChanged** event.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```


| Parameter | Type | Description |
| --- | --- | --- |
| percentProgress | int | The percentage, from 0 to 100, of the background operation that is complete. |

## See Also

* Class [BackgroundWorker](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) method


Raises the **System::ComponentModel::BackgroundWorker::ProgressChanged** event with userState object.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```


| Parameter | Type | Description |
| --- | --- | --- |
| percentProgress | int | The percentage, from 0 to 100, of the background operation that is complete. |
| userState | const System::SharedPtr\<System::Object\>\& | The state object passed to System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [BackgroundWorker](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
