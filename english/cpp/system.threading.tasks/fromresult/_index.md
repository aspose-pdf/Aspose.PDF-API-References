---
title: System::Threading::Tasks::FromResult method
linktitle: FromResult
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::FromResult method. Creates a task that has successfully completed with the specified result in C++.'
type: docs
weight: 1500
url: /cpp/system.threading.tasks/fromresult/
---
## System::Threading::Tasks::FromResult method


Creates a task that has successfully completed with the specified result.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromResult(TResult result)
```


| Parameter | Description |
| --- | --- |
| TResult | The type of the task's result. |

| Parameter | Type | Description |
| --- | --- | --- |
| result | TResult | The result value with which to complete the task. |

### ReturnValue

A successfully completed task.

## See Also

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
