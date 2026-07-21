---
title: "System::IO::Stream::FlushAsync método"
linktitle: "FlushAsync"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::Stream::FlushAsync método. Vacía de forma asincrónica todos los buffers de este stream, hace que cualquier dato almacenado se escriba en el dispositivo subyacente y supervisa las solicitudes de cancelación en C++."
type: docs
weight: 900
url: /es/cpp/system.io/stream/flushasync/
---
## Stream::FlushAsync() method


De forma asíncrona, limpia todos los búferes de este flujo, hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente y supervisa las solicitudes de cancelación.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```


### ReturnValue

Una tarea que representa la operación de vaciado asíncrono.

## Ver también

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::FlushAsync(const Threading::CancellationToken\&) method


De forma asíncrona, limpia todos los búferes de este flujo, hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente y supervisa las solicitudes de cancelación.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cancellationToken | const Threading::CancellationToken\& | El token para supervisar las solicitudes de cancelación. |

### ReturnValue

Una tarea que representa la operación de vaciado asíncrono.

## Ver también

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
