---
title: "System::Threading::Tasks::Task::ConfigureAwait metod"
linktitle: "ConfigureAwait"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::ConfigureAwait metod. Konfigurerar hur awaits på detta uppdrag ska bete sig avseende kontextfångst i C++."
type: docs
weight: 700
url: /sv/cpp/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait method


Konfigurerar hur väntningar på denna uppgift ska bete sig avseende kontextfångst.

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continueOnCapturedContext | bool | Om den ska fortsätta på den fångade kontexten |

### ReturnValue

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) A configured awaitable

## Se även

* Class [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
