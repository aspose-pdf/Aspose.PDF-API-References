---
title: System::Threading::Tasks::ResultTask class
linktitle: ResultTask
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::ResultTask class. A Task specialization that returns a result value upon completion in C++.'
type: docs
weight: 100
url: /cpp/system.threading.tasks/resulttask/
---
## ResultTask class


A [Task](../task/) specialization that returns a result value upon completion.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```


| Parameter | Description |
| --- | --- |
| T | The type of the result value returned by the task |
## Methods

| Method | Description |
| --- | --- |
| [ConfigureAwait](./configureawait/)(bool) const | Configures how awaits on this result task should behave regarding context capture. |
| [ContinueWith](./continuewith/)(const Action\<RTaskPtr\<T\>\>\&) | Creates a continuation that executes when the result task completes. |
| [get_Result](./get_result/)() const | Gets the result of the asynchronous operation. |
| [GetAwaiter](./getawaiter/)() const | Gets an awaiter for this result task for use with Await. |
| [ResultTask](./resulttask/)(const Func\<T\>\&) | Constructs a [ResultTask](./) with a function that returns a value. |
| [ResultTask](./resulttask/)() | Internal implementation. Not for user code. |
| [ResultTask](./resulttask/)(const T\&) | Internal constructor for creating result tasks with specified result. |
| [set_Result](./set_result/)(const T\&) | Sets the result value for the task. |
## Remarks



Represents an asynchronous operation that produces a result, similar to [System.Threading.Tasks.Task<TResult>](../task/) in .NET 
## See Also

* Class [Task](../task/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
