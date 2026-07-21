---
title: "System::IO::FileStream::FlushAsync método"
linktitle: "FlushAsync"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::FileStream::FlushAsync método. Elimina de forma asíncrona todos los buffers de este flujo, hace que los datos almacenados se escriban en el dispositivo subyacente y supervisa las solicitudes de cancelación en C++."
type: docs
weight: 500
url: /es/cpp/system.io/filestream/flushasync/
---
## FileStream::FlushAsync method


De forma asíncrona, limpia todos los búferes de este flujo, hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente y supervisa las solicitudes de cancelación.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cancellationToken | const Threading::CancellationToken\& | El token para supervisar las solicitudes de cancelación. |

### ReturnValue

Una tarea que representa la operación de vaciado asíncrono.

## Ver también

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
