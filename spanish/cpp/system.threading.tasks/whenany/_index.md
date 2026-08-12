---
title: "Método System::Threading::Tasks::WhenAny"
linktitle: "WhenAny"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Threading::Tasks::WhenAny. Crea una tarea que se completará cuando cualquiera de las tareas suministradas haya finalizado en C++."
type: docs
weight: 2800
url: /es/cpp/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) method


Crea una tarea que se completará cuando cualquiera de las tareas suministradas haya finalizado.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


| Parámetro | Descripción |
| --- | --- |
| TResult | El tipo del resultado de la tarea completada. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tareas | const ArrayPtr\<RTaskPtr\<TResult\>\>\& | Las tareas a esperar para su finalización. |

### ReturnValue

Una tarea que devuelve la primera tarea completada cuando cualquier tarea se completa.

## Ver también

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) method


Crea una tarea que se completará cuando cualquiera de las tareas suministradas haya finalizado.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tareas | const ArrayPtr\<TaskPtr\>\& | Las tareas a esperar para su finalización. |

### ReturnValue

Una tarea que representa la finalización de una de las tareas suministradas.

## Ver también

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) method


Crea una tarea que se completará cuando cualquiera de las tareas suministradas haya finalizado.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


| Parámetro | Descripción |
| --- | --- |
| TResult | El tipo del resultado de la tarea completada. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tareas | const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\& | Las tareas a esperar para su finalización. |

### ReturnValue

Una tarea que devuelve la primera tarea completada cuando cualquier tarea se completa.

## Ver también

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) method


Crea una tarea que se completará cuando cualquiera de las tareas suministradas haya finalizado.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tareas | const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\& | Las tareas a esperar para su finalización. |

### ReturnValue

Una tarea que representa la finalización de una de las tareas suministradas.

## Ver también

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
