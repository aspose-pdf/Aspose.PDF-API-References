---
title: "Método System::Threading::Tasks::WaitAll"
linktitle: "WaitAll"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Threading::Tasks::WaitAll. Espera a que todos los objetos Task proporcionados completen su ejecución en C++."
type: docs
weight: 2000
url: /es/cpp/system.threading.tasks/waitall/
---
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&) method


Espera a que todos los objetos [Task](../task/) proporcionados completen su ejecución.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | Una matriz de instancias [Task](../task/) sobre las que esperar. |

## Ver también

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WaitAll(const ArrayPtr\<TaskPtr\>\&, const CancellationToken\&) method


Espera a que todos los objetos [Task](../task/) proporcionados completen su ejecución.

```cpp
void System::Threading::Tasks::WaitAll(const ArrayPtr<TaskPtr> &tasks, const CancellationToken &cancellationToken)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tasks | const ArrayPtr\<TaskPtr\>\& | Una matriz de instancias [Task](../task/) sobre las que esperar. |
| cancellationToken | const CancellationToken\& | Un [CancellationToken](../../system.threading/cancellationtoken/) a observar mientras se espera a que las tareas se completen. |

## Ver también

* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
