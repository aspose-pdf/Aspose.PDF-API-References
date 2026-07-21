---
title: "System::Threading::Tasks::FromResult método"
linktitle: "FromResult"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Threading::Tasks::FromResult método. Crea una tarea que se ha completado con éxito con el resultado especificado en C++."
type: docs
weight: 1500
url: /es/cpp/system.threading.tasks/fromresult/
---
## System::Threading::Tasks::FromResult method


Crea una tarea que se ha completado con éxito con el resultado especificado.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromResult(TResult result)
```


| Parámetro | Descripción |
| --- | --- |
| TResult | El tipo del resultado de la tarea. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resultado | TResult | El valor del resultado con el que completar la tarea. |

### ReturnValue

Una tarea completada con éxito.

## Ver también

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
