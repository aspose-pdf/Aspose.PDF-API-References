---
title: "System::ComponentModel::BackgroundWorker::ReportProgress метод"
linktitle: "ReportProgress"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::ComponentModel::BackgroundWorker::ReportProgress метод. Вызывает событие System::ComponentModel::BackgroundWorker::ProgressChanged в C++."
type: docs
weight: 400
url: /ru/cpp/system.componentmodel/backgroundworker/reportprogress/
---
## BackgroundWorker::ReportProgress(int) method


Вызывает событие **System::ComponentModel::BackgroundWorker::ProgressChanged**.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| percentProgress | int | Процент (от 0 до 100) завершения фоновой операции. |

## См. также

* Class [BackgroundWorker](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
## BackgroundWorker::ReportProgress(int, const System::SharedPtr\<System::Object\>\&) method


Вызывает событие **System::ComponentModel::BackgroundWorker::ProgressChanged** с объектом userState.

```cpp
void System::ComponentModel::BackgroundWorker::ReportProgress(int percentProgress, const System::SharedPtr<System::Object> &userState)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| percentProgress | int | Процент (от 0 до 100) завершения фоновой операции. |
| userState | const System::SharedPtr\<System::Object\>\& | Объект состояния, передаваемый в System::ComponentModel::BackgroundWorker::RunWorkerAsync(System::Object). |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [BackgroundWorker](../)
* Namespace [System::ComponentModel](../../)
* Library [Aspose.PDF for C++](../../../)
