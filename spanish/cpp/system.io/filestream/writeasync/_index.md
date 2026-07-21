---
title: "System::IO::FileStream::WriteAsync método"
linktitle: "WriteAsync"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::IO::FileStream::WriteAsync método. Escribe de forma asíncrona una secuencia de bytes en el flujo actual, avanza la posición actual dentro de este flujo por la cantidad de bytes escritos y supervisa las solicitudes de cancelación en C++."
type: docs
weight: 2000
url: /es/cpp/system.io/filestream/writeasync/
---
## FileStream::WriteAsync method


De forma asíncrona, escribe una secuencia de bytes en el flujo actual, avanza la posición actual dentro de este flujo en la cantidad de bytes escritos y supervisa las solicitudes de cancelación.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const ArrayPtr\<uint8_t\>\& | El arreglo que contiene los bytes a escribir. |
| desplazamiento | int32_t | Un índice basado en cero del elemento en **buffer** en el que comienza el subrango a escribir. |
| count | int32_t | El número de elementos en el subrango a escribir. |
| cancellationToken | const Threading::CancellationToken\& | El token para supervisar las solicitudes de cancelación. |

### ReturnValue

Una tarea que representa la operación de escritura asíncrona.

## Ver también

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
