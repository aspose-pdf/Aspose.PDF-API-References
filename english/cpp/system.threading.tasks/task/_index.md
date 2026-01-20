---
title: System::Threading::Tasks::Task class
linktitle: Task
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::Task class. Represents an asynchronous operation that can be awaited and composed with other tasks in C++.'
type: docs
weight: 300
url: /cpp/system.threading.tasks/task/
---
## Task class


Represents an asynchronous operation that can be awaited and composed with other tasks.

```cpp
class Task : public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| [Activate](./activate/)(TaskScheduler *) | Activates the task for execution on a scheduler. |
| [AddContinuation](./addcontinuation/)(const Action<>\&) | Adds a continuation action to be executed upon completion. |
| [Complete](./complete/)() | Marks the task as completed and finishes task. |
| [ConfigureAwait](./configureawait/)(bool) const | Configures how awaits on this task should behave regarding context capture. |
| [ContinueWith](./continuewith/)(const Action\<TaskPtr\>\&) | Creates a continuation that executes when the task completes. |
| [Dispose](./dispose/)() override | Releases resources associated with the task. |
| [Execute](./execute/)() | Executes the task's function. |
| [get_AsyncState](./get_asyncstate/)() const | Gets the user-defined state object associated with the task. |
| static [get_CompletedTask](./get_completedtask/)() | Gets a completed task (singleton) |
| static [get_CurrentId](./get_currentid/)() |  |
| [get_Id](./get_id/)() const | Gets the ID for task. |
| [get_IsCanceled](./get_iscanceled/)() const | Gets whether the task completed due to cancellation. |
| [get_IsCompleted](./get_iscompleted/)() const | Gets whether the task has completed. |
| [get_IsFaulted](./get_isfaulted/)() const | Gets whether the task completed due to an unhandled exception. |
| [get_Scheduler](./get_scheduler/)() const | Gets the scheduler associated with this task. |
| [get_Status](./get_status/)() const | Gets the current status of the task. |
| [GetAwaiter](./getawaiter/)() const | Gets an awaiter for this task for use with Await. |
| [RunSynchronously](./runsynchronously/)() | Runs the task synchronously on the current thread. |
| [RunSynchronously](./runsynchronously/)(const SharedPtr\<TaskScheduler\>\&) | Runs the task synchronously using the specified scheduler. |
| [set_Function](./set_function/)(const FunctionT\&) | Sets the internal function to execute. |
| [set_Scheduler](./set_scheduler/)(TaskScheduler *) | Sets the scheduler associated with this task. |
| [set_Status](./set_status/)(TaskStatus) | Sets the task status. |
| [Start](./start/)() | Starts the task execution using the default scheduler. |
| [Start](./start/)(const SharedPtr\<TaskScheduler\>\&) | Starts the task execution using the specified scheduler. |
| [Task](./task/)(const Action<>\&) | Constructs a [Task](./) with an action to execute. |
| [Task](./task/)(const Action<>\&, const CancellationToken\&) | Constructs a [Task](./) with an action and cancellation token. |
| [Task](./task/)(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) | Constructs a [Task](./) with a stateful action and state object. |
| [Task](./task/)(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) | Constructs a [Task](./) with stateful action, state, and cancellation token. |
| [Task](./task/)() | Internal constructor for creating uninitialized tasks. |
| [Wait](./wait/)(const CancellationToken\&) const | Waits for the task to complete with cancellation support. |
| [Wait](./wait/)() const | Waits for the task to complete. |
| [~Task](./~task/)() | Destructor. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [FunctionT](./functiont/) | Internal implementation. Not for user code. |
## Remarks


Provides a C++ implementation similar to [System.Threading.Tasks.Task](./) in .NET, supporting cancellation, continuations, and async/await patterns 
## See Also

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
