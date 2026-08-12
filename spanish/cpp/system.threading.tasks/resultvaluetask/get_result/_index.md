---
title: "System::Threading::Tasks::ResultValueTask::get_Result método"
linktitle: "get_Result"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Tasks::ResultValueTask::get_Result método. Obtiene el resultado de la tarea completada en C++."
type: docs
weight: 900
url: /es/cpp/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result method


Obtiene el resultado de la tarea completada.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```


### ReturnValue

T El valor del resultado.
## Observaciones



Si la tarea está respaldada por un [ResultTask<T>](../../resulttask/), este método esperará el resultado y lo almacenará en caché. Las llamadas subsecuentes devolverán el valor almacenado sin esperar.

## Ver también

* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
