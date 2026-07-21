---
title: "Método System::Threading::Tasks::WhenAll"
linktitle: "WhenAll"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Threading::Tasks::WhenAll. Crea una tarea que se completará cuando todas las tareas suministradas hayan finalizado en C++."
type: docs
weight: 2400
url: /es/cpp/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) method


Crea una tarea que se completará cuando todas las tareas suministradas hayan finalizado.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


| Parámetro | Descripción |
| --- | --- |
| TResult | El tipo de los resultados de las tareas completadas. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tareas | const ArrayPtr\<RTaskPtr\<TResult\>\>\& | Las tareas a esperar para su finalización. |

### ReturnValue

Una tarea que devuelve una matriz con todos los resultados cuando todas las tareas se completan.

## Ver también

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) method


Crea una tarea que se completará cuando todas las tareas suministradas hayan finalizado.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tareas | const ArrayPtr\<TaskPtr\>\& | Las tareas a esperar para su finalización. |

### ReturnValue

Una tarea que representa la finalización de todas las tareas suministradas.

## Ver también

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) method


Crea una tarea que se completará cuando todas las tareas suministradas hayan finalizado.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


| Parámetro | Descripción |
| --- | --- |
| TResult | El tipo de los resultados de las tareas completadas. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tareas | const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\& | Las tareas a esperar para su finalización. |

### ReturnValue

Una tarea que devuelve una matriz con todos los resultados cuando todas las tareas se completan.

## Ver también

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) method


Crea una tarea que se completará cuando todas las tareas suministradas hayan finalizado.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tareas | const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\& | Las tareas a esperar para su finalización. |

### ReturnValue

Una tarea que representa la finalización de todas las tareas suministradas.

## Ver también

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
