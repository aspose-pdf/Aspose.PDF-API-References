---
title: "Clase System::Threading::ThreadPoolImpl"
linktitle: "ThreadPoolImpl"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Threading::ThreadPoolImpl. Datos internos del pool de hilos. Este es un tipo singleton con la gestión de memoria realizada mediante función(es) de acceso. Nunca debe crear instancias de ella directamente en C++."
type: docs
weight: 1400
url: /es/cpp/system.threading/threadpoolimpl/
---
## ThreadPoolImpl class


[Thread](../thread/) pool internal data. This is a singleton type with memory management done by access function(s). You should never create instances of it directly.

```cpp
class ThreadPoolImpl
```

## Métodos

| Método | Descripción |
| --- | --- |
| [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Obtiene el número de hilos disponibles. |
| static [GetInitialized](./getinitialized/)() | Obtiene el singleton del estado de inicialización. |
| [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Obtiene el número máximo de hilos concurrentes. |
| [GetMinThreads](./getminthreads/)(int\&, int\&) | Obtiene el número mínimo de hilos creados por el pool. |
| [JoinAll](./joinall/)() | Une todos los hilos propios. Espera indefinidamente. |
| [QueueUserWorkItem](./queueuserworkitem/)(WaitCallback, const System::SharedPtr\<System::Object\>\&) | Agrega un elemento de trabajo a la cola. |
| [SetMaxThreads](./setmaxthreads/)(int, int) | Establece el número de hilos propiedad del pool. |
| [SetMinThreads](./setminthreads/)(int, int) | Establece el número mínimo de hilos propiedad del pool. |
| [ThreadPoolImpl](./threadpoolimpl/)() | Constructor. |
| [~ThreadPoolImpl](./~threadpoolimpl/)() | Destructor. Une todos los hilos si aún no se han terminado. |
## Ver también

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
