---
title: System::ComponentModel::BackgroundWorker class
linktitle: BackgroundWorker
second_title: Aspose.PDF for C++ API Reference
description: 'System::ComponentModel::BackgroundWorker class. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.componentmodel/backgroundworker/
---
## BackgroundWorker class


Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class BackgroundWorker : public System::ComponentModel::Component
```

## Methods

| Method | Description |
| --- | --- |
| [BackgroundWorker](./backgroundworker/)() | RTTI information. |
| [get_WorkerReportsProgress](./get_workerreportsprogress/)() const | Gets a value indicating whether the [System::ComponentModel::BackgroundWorker](./) can report progress updates. |
| [ReportProgress](./reportprogress/)(int) | Raises the **System::ComponentModel::BackgroundWorker::ProgressChanged** event. |
| [ReportProgress](./reportprogress/)(int, const System::SharedPtr\<System::Object\>\&) | Raises the **System::ComponentModel::BackgroundWorker::ProgressChanged** event with userState object. |
| [RunWorkerAsync](./runworkerasync/)() | Starts execution of a background operation. |
| [RunWorkerAsync](./runworkerasync/)(const System::SharedPtr\<System::Object\>\&) | Starts execution of a background operation. |
| [set_WorkerReportsProgress](./set_workerreportsprogress/)(bool) | Sets a value indicating whether the [System::ComponentModel::BackgroundWorker](./) can report progress updates. |
| [~BackgroundWorker](./~backgroundworker/)() | Destructor. |
## See Also

* Class [Component](../component/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
