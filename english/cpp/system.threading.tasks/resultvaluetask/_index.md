---
title: System::Threading::Tasks::ResultValueTask class
linktitle: ResultValueTask
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::ResultValueTask class. Represents a hybrid task-like type that can wrap either a direct result value or a ResultTask<T> in C++.'
type: docs
weight: 500
url: /cpp/system.threading.tasks/resultvaluetask/
---
## ResultValueTask class


Represents a hybrid task-like type that can wrap either a direct result value or a [ResultTask<T>](../resulttask/).

```cpp
template<typename T>class ResultValueTask : public System::IEquatable<ResultValueTask<T>>,
                                            public System::Details::BoxableObjectBase
```


| Parameter | Description |
| --- | --- |
| T | The type of the result produced by the task. |
## Methods

| Method | Description |
| --- | --- |
| [AsTask](./astask/)() const | Converts this [ResultValueTask](./) to a shared pointer to [ResultTask<T>](../resulttask/). |
| [ConfigureAwait](./configureawait/)(bool) const | Configures an awaiter for this task. |
| [Equals](./equals/)(ResultValueTask) override | Determines whether this instance equals another [ResultValueTask](./) instance. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determines whether this instance equals another object. |
| [get_IsCanceled](./get_iscanceled/)() const | Gets a value indicating whether the task completed due to being canceled. |
| [get_IsCompleted](./get_iscompleted/)() const | Gets a value indicating whether the task has completed. |
| [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | Gets a value indicating whether the task completed successfully. |
| [get_IsFaulted](./get_isfaulted/)() const | Gets a value indicating whether the task completed due to an unhandled exception. |
| [get_Result](./get_result/)() | Gets the result of the completed task. |
| [GetAwaiter](./getawaiter/)() const | Gets an awaiter for this task to support await expressions. |
| [operator!=](./operator!=/)(const ResultValueTask\&) const | Inequality operator for [ResultValueTask](./). |
| [operator==](./operator==/)(const ResultValueTask\&) const | Equality operator for [ResultValueTask](./). |
| [ResultValueTask](./resultvaluetask/)() | Constructs an empty, uninitialized [ResultValueTask](./). |
| [ResultValueTask](./resultvaluetask/)(const T\&) | Constructs a completed [ResultValueTask](./) with the specified result. |
| [ResultValueTask](./resultvaluetask/)(const RTaskPtr\<T\>\&) | Constructs a [ResultValueTask](./) from a shared pointer to a [ResultTask<T>](../resulttask/). |
## Remarks


[ResultValueTask](./) combines the benefits of [ValueTask](../valuetask/) (reduced allocations for synchronous results) with the ability to wrap existing [ResultTask<T>](../resulttask/) objects. It provides awaitable interface and various task status inspection methods. 
## See Also

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
