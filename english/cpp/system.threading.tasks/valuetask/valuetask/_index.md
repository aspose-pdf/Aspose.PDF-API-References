---
title: System::Threading::Tasks::ValueTask::ValueTask constructor
linktitle: ValueTask
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::ValueTask::ValueTask constructor. Constructs an empty, uninitialized ValueTask in C++.'
type: docs
weight: 100
url: /cpp/system.threading.tasks/valuetask/valuetask/
---
## ValueTask::ValueTask() constructor


Constructs an empty, uninitialized [ValueTask](../).

```cpp
System::Threading::Tasks::ValueTask::ValueTask()
```

## Remarks



The task is not completed and contains no result. Attempting to get the result will throw an exception. 

## See Also

* Class [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ValueTask::ValueTask(const TaskPtr\&) constructor


Constructs a [ValueTask](../) from a shared pointer to a [Task](../../task/).

```cpp
System::Threading::Tasks::ValueTask::ValueTask(const TaskPtr &task)
```


| Parameter | Type | Description |
| --- | --- | --- |
| task | const TaskPtr\& | The task to wrap. Can be null for an empty task. |
## Remarks



The [ValueTask](../) will represent the state of the provided task. 

## See Also

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
