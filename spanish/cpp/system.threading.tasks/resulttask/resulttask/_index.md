---
title: "System::Threading::Tasks::ResultTask::ResultTask constructor"
linktitle: "ResultTask"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Tasks::ResultTask::ResultTask constructor. Implementación interna. No para código de usuario en C++."
type: docs
weight: 100
url: /es/cpp/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask() constructor


Implementación interna. No para código de usuario.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Observaciones


Constructor interno para crear tareas de resultado no inicializadas
## Ver también

* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ResultTask(const Func\<T\>\&) constructor


Construye un [ResultTask](../) con una función que devuelve un valor.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| función | const Func\<T\>\& | La función que se ejecuta de forma asíncrona y devuelve un resultado |

## Ver también

* Class [Func](../../../system/func/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ResultTask(const T\&) constructor


Constructor interno para crear tareas de resultado con un resultado especificado.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## Ver también

* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
