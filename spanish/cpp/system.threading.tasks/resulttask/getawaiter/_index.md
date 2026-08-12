---
title: "Método System::Threading::Tasks::ResultTask::GetAwaiter"
linktitle: "GetAwaiter"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Threading::Tasks::ResultTask::GetAwaiter. Obtiene un awaiter para esta tarea de resultado para usar con Await en C++."
type: docs
weight: 600
url: /es/cpp/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter method


Obtiene un awaiter para esta tarea de resultado para usar con Await.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```


### ReturnValue

[Runtime::CompilerServices::ResultTaskAwaiter<T>](../../../system.runtime.compilerservices/resulttaskawaiter/) An awaiter instance that returns the result
## Observaciones



Cuando se espera, la coroutine reanudará con el valor del resultado disponible

## Ver también

* Class [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
