---
title: "Clase System::Threading::Tasks::TaskScheduler"
linktitle: "TaskScheduler"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Threading::Tasks::TaskScheduler. Representa un objeto que maneja el trabajo de bajo nivel de encolar tareas en hilos en C++."
type: docs
weight: 700
url: /es/cpp/system.threading.tasks/taskscheduler/
---
## TaskScheduler class


Representa un objeto que maneja el trabajo de bajo nivel de encolar tareas en hilos.

```cpp
class TaskScheduler : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [FromCurrentSynchronizationContext](./fromcurrentsynchronizationcontext/)() | Crea un [TaskScheduler](./) asociado con el hilo actual. |
| static [get_Current](./get_current/)() | Obtiene el [TaskScheduler](./) asociado con la tarea que se está ejecutando actualmente. |
| static [get_Default](./get_default/)() | Obtiene la instancia predeterminada de [TaskScheduler](./) que proporciona el framework. |
| [get_Id](./get_id/)() const | Obtiene el ID único de este [TaskScheduler](./). |
| virtual [get_MaximumConcurrencyLevel](./get_maximumconcurrencylevel/)() const | Indica el nivel máximo de concurrencia que este [TaskScheduler](./) puede soportar. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
