---
title: "System::Threading::Tasks::ResultValueTask::ResultValueTask constructor"
linktitle: "ResultValueTask"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Tasks::ResultValueTask::ResultValueTask constructor. Construye un ResultValueTask vacío y sin inicializar en C++."
type: docs
weight: 100
url: /es/cpp/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() constructor


Construye un [ResultValueTask](../) vacío y sin inicializar.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Observaciones



La tarea no está completada y no contiene resultado. Intentar obtener el resultado lanzará una excepción.

## Ver también

* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) constructor


Construye un [ResultValueTask](../) a partir de un puntero compartido a un [ResultTask<T>](../../resulttask/).

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tarea | const RTaskPtr\<T\>\& | La tarea a envolver. Puede ser nula para una tarea vacía. |
## Observaciones



El [ResultValueTask](../) representará el estado y el resultado de la tarea proporcionada.

## Ver también

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultValueTask::ResultValueTask(const T\&) constructor


Construye un [ResultValueTask](../) completado con el resultado especificado.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resultado | const T\& | El valor de resultado para envolver en una tarea completada. |
## Observaciones



Esto crea una tarea completada con éxito que devuelve inmediatamente el valor.

## Ver también

* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
