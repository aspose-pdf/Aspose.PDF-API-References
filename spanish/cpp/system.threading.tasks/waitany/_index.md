---
title: "System::Threading::Tasks::WaitAny method"
linktitle: "WaitAny"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Tasks::WaitAny method. Espera a que cualquiera de los objetos Task proporcionados complete su ejecución en C++."
type: docs
weight: 2200
url: /es/cpp/system.threading.tasks/waitany/
---
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&) method


Espera a que cualquiera de los objetos [Task](../task/) proporcionados complete la ejecución.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | Una matriz de instancias [Task](../task/) sobre las que esperar. |

### ReturnValue

El índice de la tarea completada en el arreglo de tareas.

## Ver también

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WaitAny(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) method


Espera a que cualquiera de los objetos [Task](../task/) proporcionados complete la ejecución.

```cpp
int32_t System::Threading::Tasks::WaitAny(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | Una matriz de instancias [Task](../task/) sobre las que esperar. |
| cancellationToken | const CancellationToken\& | Un [CancellationToken](../../system.threading/cancellationtoken/) a observar mientras se espera a que las tareas se completen. |

### ReturnValue

El índice de la tarea completada en el arreglo de tareas.

## Ver también

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
