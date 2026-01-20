---
title: System::Threading::Tasks::Task::ConfigureAwait method
linktitle: ConfigureAwait
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::Task::ConfigureAwait method. Configures how awaits on this task should behave regarding context capture in C++.'
type: docs
weight: 600
url: /cpp/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait method


Configures how awaits on this task should behave regarding context capture.

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| continueOnCapturedContext | bool | Whether to continue on the captured context |

### ReturnValue

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) A configured awaitable

## See Also

* Class [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
