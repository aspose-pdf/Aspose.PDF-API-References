---
title: System::Threading::Tasks::ValueTask::ConfigureAwait method
linktitle: ConfigureAwait
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::ValueTask::ConfigureAwait method. Configures an awaiter for this task in C++.'
type: docs
weight: 300
url: /cpp/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait method


Configures an awaiter for this task.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```


| Parameter | Type | Description |
| --- | --- | --- |
| continueOnCapturedContext | bool | true to attempt to marshal the continuation back to the original context captured; otherwise, false. |

### ReturnValue

ConfiguredValueTaskAwaitable An object that configures how awaiters behave for this task.

## See Also

* Class [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* Class [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
