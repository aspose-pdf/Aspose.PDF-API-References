---
title: System::Threading::Tasks::ResultTask::ConfigureAwait method
linktitle: ConfigureAwait
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::ResultTask::ConfigureAwait method. Configures how awaits on this result task should behave regarding context capture in C++.'
type: docs
weight: 200
url: /cpp/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait method


Configures how awaits on this result task should behave regarding context capture.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| continueOnCapturedContext | bool | Whether to continue on the captured context |

### ReturnValue

[Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T>](../../../system.runtime.compilerservices/configuredresulttaskawaitable/) A configured awaitable for the result
## Remarks



This enables fine-grained control over context flow for async/await patterns 

## See Also

* Class [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
