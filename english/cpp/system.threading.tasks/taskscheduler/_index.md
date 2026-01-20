---
title: System::Threading::Tasks::TaskScheduler class
linktitle: TaskScheduler
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::TaskScheduler class. Represents an object that handles the low-level work of queuing tasks onto threads in C++.'
type: docs
weight: 400
url: /cpp/system.threading.tasks/taskscheduler/
---
## TaskScheduler class


Represents an object that handles the low-level work of queuing tasks onto threads.

```cpp
class TaskScheduler : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [FromCurrentSynchronizationContext](./fromcurrentsynchronizationcontext/)() | Creates a [TaskScheduler](./) associated with the current thread. |
| static [get_Current](./get_current/)() | Gets the [TaskScheduler](./) associated with the currently executing task. |
| static [get_Default](./get_default/)() | Gets the default [TaskScheduler](./) instance that is provided by the framework. |
| [get_Id](./get_id/)() const | Gets the unique ID for this [TaskScheduler](./). |
| virtual [get_MaximumConcurrencyLevel](./get_maximumconcurrencylevel/)() const | Indicates the maximum concurrency level this [TaskScheduler](./) is able to support. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
