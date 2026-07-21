---
title: "System::Threading::Tasks::Task::ConfigureAwait método"
linktitle: "ConfigureAwait"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Tasks::Task::ConfigureAwait método. Configura cómo deben comportarse los awaits en esta tarea respecto a la captura del contexto en C++."
type: docs
weight: 700
url: /es/cpp/system.threading.tasks/task/configureawait/
---
## Task::ConfigureAwait method


Configura cómo deben comportarse las esperas en esta tarea respecto a la captura del contexto.

```cpp
Runtime::CompilerServices::ConfiguredTaskAwaitable System::Threading::Tasks::Task::ConfigureAwait(bool continueOnCapturedContext) const
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continueOnCapturedContext | bool | Si continuar en el contexto capturado |

### ReturnValue

[Runtime::CompilerServices::ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/) A configured awaitable

## Ver también

* Class [ConfiguredTaskAwaitable](../../../system.runtime.compilerservices/configuredtaskawaitable/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
