---
title: "System::Threading::Tasks::ResultTask::ConfigureAwait method"
linktitle: "ConfigureAwait"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::ResultTask::ConfigureAwait method. Konfigurerar hur väntningar på detta resultatuppgift ska bete sig avseende kontextfångst i C++."
type: docs
weight: 300
url: /sv/cpp/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait method


Konfigurerar hur väntningar på denna resultatuppgift ska bete sig avseende kontextfångst.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| continueOnCapturedContext | bool | Om den ska fortsätta på den fångade kontexten |

### ReturnValue

[Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T>](../../../system.runtime.compilerservices/configuredresulttaskawaitable/) A configured awaitable for the result
## Anmärkningar



Detta möjliggör finjusterad kontroll över kontextflödet för async/await-mönster

## Se även

* Class [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
