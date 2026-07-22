---
title: "System::Threading::Tasks::ResultValueTask::ConfigureAwait metod"
linktitle: "ConfigureAwait"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::ResultValueTask::ConfigureAwait metod. Konfigurerar en awaiter för denna uppgift i C++."
type: docs
weight: 300
url: /sv/cpp/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait method


Konfigurerar en väntare för denna uppgift.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continueOnCapturedContext | bool | true för att försöka vidarebefordra fortsättningen tillbaka till den ursprungliga kontexten som fångats; annars falskt. |

### ReturnValue

ConfiguredResultValueTaskAwaitable<T> Ett objekt som konfigurerar hur awaiters beter sig för denna uppgift.

## Se även

* Class [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
