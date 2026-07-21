---
title: "Método System::Threading::Tasks::FromException"
linktitle: "FromException"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Threading::Tasks::FromException. Crea una tarea que ha finalizado con una excepción especificada en C++."
type: docs
weight: 1300
url: /es/cpp/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) method


Crea una tarea que ha finalizado con una excepción especificada.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| excepción | const Exception\& | La excepción con la que completar la tarea. |

### ReturnValue

Una tarea con error.

## Ver también

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::FromException(const Exception\&) method


Crea una tarea que ha finalizado con una excepción especificada y un tipo de resultado.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```


| Parámetro | Descripción |
| --- | --- |
| TResult | El tipo del resultado de la tarea. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| excepción | const Exception\& | La excepción con la que completar la tarea. |

### ReturnValue

Una tarea con error con el tipo de resultado especificado.

## Ver también

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [Exception](../../system/exception/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
