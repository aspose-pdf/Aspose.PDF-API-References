---
title: System::Threading::Tasks::ResultValueTask::AsTask method
linktitle: AsTask
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::ResultValueTask::AsTask method. Converts this ResultValueTask to a shared pointer to ResultTask<T> in C++.'
type: docs
weight: 200
url: /cpp/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask method


Converts this [ResultValueTask](../) to a shared pointer to [ResultTask<T>](../../resulttask/).

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```


### ReturnValue

[RTaskPtr<T>](../../../system/rtaskptr/) A shared pointer to a [ResultTask<T>](../../resulttask/) that represents this operation.
## Remarks



If the [ResultValueTask](../) contains a direct result, creates a completed task with that result. If it contains a task, returns a shared pointer to that task. 

## See Also

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
