---
title: "Método System::IO::Stream::ReadAsync"
linktitle: "ReadAsync"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::IO::Stream::ReadAsync. Lee de forma asíncrona una secuencia de bytes del flujo actual, avanza la posición dentro del flujo por la cantidad de bytes leídos y supervisa las solicitudes de cancelación en C++."
type: docs
weight: 1900
url: /es/cpp/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


De forma asíncrona, lee una secuencia de bytes del flujo actual, avanza la posición dentro del flujo en la cantidad de bytes leídos y supervisa las solicitudes de cancelación.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const ArrayPtr\<uint8_t\>\& | La matriz de bytes donde escribir los bytes leídos. |
| desplazamiento | int32_t | Una posición basada en cero en **buffer** donde comenzar a escribir. |
| count | int32_t | El número de bytes a leer. |

### ReturnValue

Una tarea que representa la operación de lectura asíncrona. El valor del parámetro TResult contiene el número total de bytes leídos en el buffer. El valor del resultado puede ser menor que la cantidad de bytes solicitada si el número de bytes actualmente disponibles es menor que el solicitado, o puede ser 0 (cero) si se ha alcanzado el final del flujo.

## Ver también

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method


De forma asíncrona, lee una secuencia de bytes del flujo actual, avanza la posición dentro del flujo en la cantidad de bytes leídos y supervisa las solicitudes de cancelación.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| búfer | const ArrayPtr\<uint8_t\>\& | La matriz de bytes donde escribir los bytes leídos. |
| desplazamiento | int32_t | Una posición basada en cero en **buffer** donde comenzar a escribir. |
| count | int32_t | El número de bytes a leer. |
| cancellationToken | const Threading::CancellationToken\& | El token para supervisar las solicitudes de cancelación. |

### ReturnValue

Una tarea que representa la operación de lectura asíncrona. El valor del parámetro TResult contiene el número total de bytes leídos en el buffer. El valor del resultado puede ser menor que la cantidad de bytes solicitada si el número de bytes actualmente disponibles es menor que el solicitado, o puede ser 0 (cero) si se ha alcanzado el final del flujo.

## Ver también

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
