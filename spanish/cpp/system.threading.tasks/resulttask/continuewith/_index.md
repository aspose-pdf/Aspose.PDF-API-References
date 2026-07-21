---
title: "Método System::Threading::Tasks::ResultTask::ContinueWith"
linktitle: "ContinueWith"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Threading::Tasks::ResultTask::ContinueWith. Crea una continuación que se ejecuta cuando la tarea de resultado se completa en C++."
type: docs
weight: 400
url: /es/cpp/system.threading.tasks/resulttask/continuewith/
---
## ResultTask::ContinueWith(const Action\<RTaskPtr\<T\>\>\&) method


Crea una continuación que se ejecuta cuando la tarea de resultado se completa.

```cpp
TaskPtr System::Threading::Tasks::ResultTask<T>::ContinueWith(const Action<RTaskPtr<T>> &continuationAction)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continuationAction | const Action\<RTaskPtr\<T\>\>\& | [Action](../../../system/action/) para ejecutar cuando esta tarea se completa, recibiendo esta tarea de resultado |

### ReturnValue

[TaskPtr](../../../system/taskptr/) A new task representing the continuation
## Observaciones



La acción de continuación recibe este [ResultTask](../) para acceder al valor del resultado

## Ver también

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [Action](../../../system/action/)
* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ContinueWith(const Action\<TaskPtr\>\&) method


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
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ContinueWith(const Func\<RTaskPtr\<T\>, TNewResult\>\&) method


Crea una continuación que se ejecuta cuando la tarea de resultado se completa.

```cpp
template<typename TNewResult> RTaskPtr<TNewResult> System::Threading::Tasks::ResultTask<T>::ContinueWith(const Func<RTaskPtr<T>, TNewResult> &continuationFunction)
```


| Parámetro | Descripción |
| --- | --- |
| TNewResult | Tipo de resultado de la continuación de la tarea |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| continuationFunction | const Func\<RTaskPtr\<T\>, TNewResult\>\& | Función para obtener el resultado de la continuación cuando esta tarea se completa, recibiendo esta tarea de resultado |

### ReturnValue

[RTaskPtr](../../../system/rtaskptr/) A new task representing the continuation
## Observaciones



La función de continuación recibe este [ResultTask](../) para acceder al valor del resultado

## Ver también

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [Func](../../../system/func/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ContinueWith(const Func\<TaskPtr, TResult\>\&) method


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
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
