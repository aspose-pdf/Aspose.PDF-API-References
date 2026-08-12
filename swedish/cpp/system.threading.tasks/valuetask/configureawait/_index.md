---
title: "System::Threading::Tasks::ValueTask::ConfigureAwait metod"
linktitle: "ConfigureAwait"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::ValueTask::ConfigureAwait metod. Konfigurerar en väntare för denna uppgift i C++."
type: docs
weight: 300
url: /sv/cpp/system.threading.tasks/valuetask/configureawait/
---
## ValueTask::ConfigureAwait method


Konfigurerar en väntare för denna uppgift.

```cpp
Runtime::CompilerServices::ConfiguredValueTaskAwaitable System::Threading::Tasks::ValueTask::ConfigureAwait(bool continueOnCapturedContext) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continueOnCapturedContext | bool | true för att försöka vidarebefordra fortsättningen tillbaka till den ursprungliga kontexten som fångats; annars falskt. |

### ReturnValue

ConfiguredValueTaskAwaitable Ett objekt som konfigurerar hur väntare beter sig för denna uppgift.

## Se även

* Class [ConfiguredValueTaskAwaitable](../../../system.runtime.compilerservices/configuredvaluetaskawaitable/)
* Class [ValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
