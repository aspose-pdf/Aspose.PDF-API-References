---
title: "Método System::Threading::Tasks::Yield"
linktitle: "Yield"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Threading::Tasks::Yield. Crea una tarea awaitable que cede de forma asíncrona al contexto actual cuando se espera en C++."
type: docs
weight: 3200
url: /es/cpp/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield method


Crea una tarea awaitable que cede de forma asíncrona al contexto actual cuando se espera.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```


### ReturnValue

Un YieldAwaitable que puede esperarse para ceder el control.
## Observaciones



Este método es útil para forzar que un método asíncrono ceda el control, permitiendo que se procesen otros trabajos pendientes antes de continuar.
## Ver también

* Class [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
