---
title: "Clase System::Threading::Tasks::Task"
linktitle: "Tarea"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Threading::Tasks::Task. Representa una operación asincrónica que puede esperarse y componerse con otras tareas en C++."
type: docs
weight: 600
url: /es/cpp/system.threading.tasks/task/
---
## Task class


Representa una operación asíncrona que puede esperarse y combinarse con otras tareas.

```cpp
class Task : public System::IDisposable
```

## Métodos

| Método | Descripción |
| --- | --- |
| [Activate](./activate/)(const SharedPtr\<TaskScheduler\>\&) | Activa la tarea para su ejecución en un planificador. |
| [AddCompletionAction](./addcompletionaction/)(const Action<>\&) | Agrega una acción de continuación que se ejecutará al completarse. |
| [Cancel](./cancel/)() | Marca la tarea como cancelada y finaliza la tarea. |
| [Complete](./complete/)() | Marca la tarea como completada y finaliza la tarea. |
| [ConfigureAwait](./configureawait/)(bool) const | Configura cómo deben comportarse las esperas en esta tarea respecto a la captura del contexto. |
| [ContinueWith](./continuewith/)(const Action\<TaskPtr\>\&) | Crea una continuación que se ejecuta cuando la tarea se completa. |
| [ContinueWith](./continuewith/)(const Func\<TaskPtr, TResult\>\&) | Crea una continuación que se ejecuta cuando la tarea se completa. |
| [Deactivate](./deactivate/)() | Desactiva la tarea para su ejecución en su planificador actual, si lo hay. |
| [Dispose](./dispose/)() override | Libera los recursos asociados con la tarea. |
| [Execute](./execute/)() | Ejecuta la función de la tarea. |
| [get_AsyncState](./get_asyncstate/)() const | Obtiene el objeto de estado definido por el usuario asociado a la tarea. |
| static [get_CompletedTask](./get_completedtask/)() | Obtiene una tarea completada (singleton) |
| static [get_CurrentId](./get_currentid/)() |  |
| [get_Exception](./get_exception/)() const | Obtiene el ID de la tarea. |
| [get_Id](./get_id/)() const |  |
| [get_IsCanceled](./get_iscanceled/)() const | Obtiene si la tarea se completó debido a una cancelación. |
| [get_IsCompleted](./get_iscompleted/)() const | Obtiene si la tarea ha completado. |
| [get_IsFaulted](./get_isfaulted/)() const | Obtiene si la tarea se completó debido a una excepción no controlada. |
| [get_Scheduler](./get_scheduler/)() const | Obtiene el planificador asociado a esta tarea. |
| [get_Status](./get_status/)() const | Obtiene el estado actual de la tarea. |
| [GetAwaiter](./getawaiter/)() const | Obtiene un awaiter para esta tarea para usar con Await. |
| [RunSynchronously](./runsynchronously/)() | Ejecuta la tarea de forma sincrónica en el hilo actual. |
| [RunSynchronously](./runsynchronously/)(const SharedPtr\<TaskScheduler\>\&) | Ejecuta la tarea de forma sincrónica usando el planificador especificado. |
| [set_Function](./set_function/)(const FunctionT\&) | Establece la función interna a ejecutar. |
| [set_Scheduler](./set_scheduler/)(const SharedPtr\<TaskScheduler\>\&) | Establece el planificador asociado a esta tarea. |
| [set_Status](./set_status/)(TaskStatus) | Establece el estado de la tarea. |
| [Start](./start/)() | Inicia la ejecución de la tarea usando el planificador predeterminado. |
| [Start](./start/)(const SharedPtr\<TaskScheduler\>\&) | Inicia la ejecución de la tarea usando el programador especificado. |
| [Task](./task/)(const Action<>\&) | Construye un [Task](./) con una acción para ejecutar. |
| [Task](./task/)(const Action<>\&, const CancellationToken\&) | Construye un [Task](./) con una acción y un token de cancelación. |
| [Task](./task/)(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) | Construye un [Task](./) con una acción con estado y un objeto de estado. |
| [Task](./task/)(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) | Construye un [Task](./) con acción con estado, estado y token de cancelación. |
| [Task](./task/)() | Constructor interno para crear tareas no inicializadas. |
| [Wait](./wait/)(const CancellationToken\&) | Espera a que la tarea se complete con soporte de cancelación. |
| [Wait](./wait/)() | Espera a que la tarea se complete. |
| [~Task](./~task/)() | Destructor. |
## Typedefs

| Typedef | Descripción |
| --- | --- |
| [FunctionT](./functiont/) | Implementación interna. No para código de usuario. |
## Observaciones


Proporciona una implementación en C++ similar a [System.Threading.Tasks.Task](./) en .NET, que admite cancelación, continuaciones y patrones async/await.
## Ver también

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
