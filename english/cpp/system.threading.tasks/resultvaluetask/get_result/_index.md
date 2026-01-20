---
title: System::Threading::Tasks::ResultValueTask::get_Result method
linktitle: get_Result
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::ResultValueTask::get_Result method. Gets the result of the completed task in C++.'
type: docs
weight: 900
url: /cpp/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result method


Gets the result of the completed task.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result() const
```


### ReturnValue

T The result value.
## Remarks



If the task is backed by a [ResultTask<T>](../../resulttask/), this method will await the result and cache it. Subsequent calls will return the cached value without awaiting. 

## See Also

* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
