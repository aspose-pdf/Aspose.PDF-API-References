---
title: "Método System::Threading::Tasks::Delay"
linktitle: "Retardo"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Threading::Tasks::Delay. Crea una tarea que se completa después de un retraso de tiempo en C++."
type: docs
weight: 1000
url: /es/cpp/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) method


Crea una tarea que se completa después de un retraso de tiempo.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| millisecondsDelay | int32_t | El número de milisegundos a esperar antes de completar la tarea devuelta, o -1 para esperar indefinidamente. |

### ReturnValue

Una tarea que representa el retraso de tiempo.

## Ver también

* Typedef [TaskPtr](../../system/taskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) method


Crea una tarea que se completa después de un retraso de tiempo y puede ser cancelada.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| millisecondsDelay | int32_t | El número de milisegundos a esperar antes de completar la tarea devuelta, o -1 para esperar indefinidamente. |
| cancellationToken | const CancellationToken\& | El token de cancelación que puede usarse para cancelar el retraso. |

### ReturnValue

Una tarea que representa el retraso de tiempo.

## Ver también

* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
