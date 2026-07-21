---
title: "System::Threading::Tasks::ResultValueTask::AsTask método"
linktitle: "AsTask"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Tasks::ResultValueTask::AsTask método. Convierte este ResultValueTask en un puntero compartido a ResultTask<T> en C++."
type: docs
weight: 200
url: /es/cpp/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask method


Convierte este [ResultValueTask](../) en un puntero compartido a [ResultTask<T>](../../resulttask/).

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```


### ReturnValue

[RTaskPtr<T>](../../../system/rtaskptr/) A shared pointer to a [ResultTask<T>](../../resulttask/) that represents this operation.
## Observaciones



Si el [ResultValueTask](../) contiene un resultado directo, crea una tarea completada con ese resultado. Si contiene una tarea, devuelve un puntero compartido a esa tarea.

## Ver también

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
