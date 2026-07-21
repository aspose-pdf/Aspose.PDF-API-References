---
title: "System::Threading::Tasks::Task::Task constructor"
linktitle: "Tarea"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Tasks::Task::Task constructor. Constructor interno para crear tareas no inicializadas en C++."
type: docs
weight: 100
url: /es/cpp/system.threading.tasks/task/task/
---
## Task::Task() constructor


Constructor interno para crear tareas no inicializadas.

```cpp
System::Threading::Tasks::Task::Task()
```

## Ver también

* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) constructor


Construye un [Task](../) con una acción con estado y un objeto de estado.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| acción | const Action\<SharedPtr\<Object\>\>\& | La acción a ejecutar (acepta un objeto de estado) |
| state | const SharedPtr\<Object\>\& | Objeto de estado definido por el usuario pasado a la acción |

## Ver también

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) constructor


Construye un [Task](../) con acción con estado, estado y token de cancelación.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| acción | const Action\<SharedPtr\<Object\>\>\& | La acción a ejecutar (acepta un objeto de estado) |
| state | const SharedPtr\<Object\>\& | Objeto de estado definido por el usuario pasado a la acción |
| cancellationToken | const CancellationToken\& | Token para monitorizar solicitudes de cancelación |

## Ver también

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action<>\&) constructor


Construye un [Task](../) con una acción a ejecutar.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| acción | const Action<>\& | La acción a ejecutar de forma asíncrona |

## Ver también

* Typedef [Action](../../../system/action/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action<>\&, const CancellationToken\&) constructor


Construye un [Task](../) con una acción y token de cancelación.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| acción | const Action<>\& | La acción a ejecutar de forma asíncrona |
| cancellationToken | const CancellationToken\& | Token para monitorizar solicitudes de cancelación |

## Ver también

* Typedef [Action](../../../system/action/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
