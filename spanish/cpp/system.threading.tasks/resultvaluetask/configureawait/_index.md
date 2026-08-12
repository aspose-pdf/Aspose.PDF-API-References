---
title: "System::Threading::Tasks::ResultValueTask::ConfigureAwait método"
linktitle: "ConfigureAwait"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Tasks::ResultValueTask::ConfigureAwait método. Configura un awaiter para esta tarea en C++."
type: docs
weight: 300
url: /es/cpp/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait method


Configura un awaiter para esta tarea.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continueOnCapturedContext | bool | true para intentar trasladar la continuación de vuelta al contexto original capturado; de lo contrario, false. |

### ReturnValue

ConfiguredResultValueTaskAwaitable<T> Un objeto que configura cómo se comportan los awaiters para esta tarea.

## Ver también

* Class [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
