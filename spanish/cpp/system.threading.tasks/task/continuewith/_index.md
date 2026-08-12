---
title: "System::Threading::Tasks::Task::ContinueWith método"
linktitle: "ContinueWith"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Tasks::Task::ContinueWith método. Crea una continuación que se ejecuta cuando la tarea se completa en C++."
type: docs
weight: 800
url: /es/cpp/system.threading.tasks/task/continuewith/
---
## Task::ContinueWith(const Action\<TaskPtr\>\&) method


Crea una continuación que se ejecuta cuando la tarea se completa.

```cpp
TaskPtr System::Threading::Tasks::Task::ContinueWith(const Action<TaskPtr> &continuationAction)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continuationAction | const Action\<TaskPtr\>\& | [Action](../../../system/action/) para ejecutar cuando esta tarea se completa |

### ReturnValue

[TaskPtr](../../../system/taskptr/) A new task representing the continuation

## Ver también

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::ContinueWith(const Func\<TaskPtr, TResult\>\&) method


Crea una continuación que se ejecuta cuando la tarea se completa.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Task::ContinueWith(const Func<TaskPtr, TResult> &continuationFunction)
```


| Parámetro | Descripción |
| --- | --- |
| TResult | Un tipo de resultado de tarea |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continuationFunction | const Func\<TaskPtr, TResult\>\& | Función para obtener el resultado cuando esta tarea se completa |

### ReturnValue

[RTaskPtr](../../../system/rtaskptr/) A new task representing the continuation

## Ver también

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Func](../../../system/func/)
* Typedef [TaskPtr](../../../system/taskptr/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
