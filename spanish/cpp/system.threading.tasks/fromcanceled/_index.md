---
title: "Método System::Threading::Tasks::FromCanceled"
linktitle: "FromCanceled"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Threading::Tasks::FromCanceled. Crea una tarea que ha finalizado debido a la cancelación con el token especificado en C++."
type: docs
weight: 1200
url: /es/cpp/system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled method


Crea una tarea que ha finalizado debido a la cancelación con el token especificado.

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cancellationToken | const CancellationToken\& | El token de cancelación que provocó que la tarea fuera cancelada. |

### ReturnValue

Una tarea cancelada.

## Ver también

* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
