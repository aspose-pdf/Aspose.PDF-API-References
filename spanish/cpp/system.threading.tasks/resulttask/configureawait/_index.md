---
title: "System::Threading::Tasks::ResultTask::ConfigureAwait method"
linktitle: "ConfigureAwait"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Tasks::ResultTask::ConfigureAwait method. Configura cómo deben comportarse los await en esta tarea de resultado respecto a la captura de contexto en C++."
type: docs
weight: 300
url: /es/cpp/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait method


Configura cómo deben comportarse los await en esta tarea de resultado respecto a la captura del contexto.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continueOnCapturedContext | bool | Si continuar en el contexto capturado |

### ReturnValue

[Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T>](../../../system.runtime.compilerservices/configuredresulttaskawaitable/) A configured awaitable for the result
## Observaciones



Esto permite un control granular sobre el flujo de contexto para los patrones async/await

## Ver también

* Class [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
