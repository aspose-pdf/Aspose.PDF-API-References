---
title: System::Threading::Tasks::ResultValueTask::ConfigureAwait method
linktitle: ConfigureAwait
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::ResultValueTask::ConfigureAwait method. Configures an awaiter for this task in C++.'
type: docs
weight: 300
url: /cpp/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait method


Configures an awaiter for this task.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| continueOnCapturedContext | bool | true to attempt to marshal the continuation back to the original context captured; otherwise, false. |

### ReturnValue

ConfiguredResultValueTaskAwaitable<T> An object that configures how awaiters behave for this task.

## See Also

* Class [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
