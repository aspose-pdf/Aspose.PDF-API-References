---
title: OptimizedMemoryStream
second_title: Referencia de API de Aspose.PDF para .NET
description: Define un MemoryStream que puede contener más capacidad estándar
type: docs
weight: 5750
url: /es/net/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream class

Define un MemoryStream que puede contener más capacidad estándar

```csharp
public class OptimizedMemoryStream : Stream
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream#constructor)() | Inicializa una nueva instancia del[`OptimizedMemoryStream`](../optimizedmemorystream) clase. |
| [OptimizedMemoryStream](optimizedmemorystream#constructor_1)(byte[]) | Inicializa una nueva instancia del[`OptimizedMemoryStream`](../optimizedmemorystream) clase basada en la matriz de bytes especificada. |
| [OptimizedMemoryStream](optimizedmemorystream#constructor_2)(int) | Inicializa una nueva instancia del[`OptimizedMemoryStream`](../optimizedmemorystream) clase. |
| [OptimizedMemoryStream](optimizedmemorystream#constructor_3)(int, byte[]) | Inicializa una nueva instancia del[`OptimizedMemoryStream`](../optimizedmemorystream) clase basada en la matriz de bytes especificada. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize) { get; set; } | Obtiene o establece el tamaño de los búfer subyacentes. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread) { get; } | Cuando se anula en una clase derivada, obtiene un valor que indica si el flujo actual admite la lectura. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek) { get; } | Cuando se invalida en una clase derivada, obtiene un valor que indica si el flujo actual admite la búsqueda. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite) { get; } | Cuando se anula en una clase derivada, obtiene un valor que indica si el flujo actual admite escritura. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose) { get; set; } | Obtiene o establece un valor que indica si se deben liberar los búfer subyacentes al desechar. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length) { get; } | Cuando se anula en una clase derivada, obtiene la longitud en bytes del flujo. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position) { get; set; } | Cuando se anula en una clase derivada, obtiene o establece la posición dentro de la secuencia actual. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush)() | La función anulada. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read)(byte[], int, int) | Cuando se anula en una clase derivada, lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo según el número de bytes leídos. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte)() | Lee un byte de la secuencia y avanza la posición dentro de la secuencia en un byte, o devuelve -1 si está al final de la secuencia. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek)(long, SeekOrigin) | Cuando se anula en una clase derivada, establece la posición dentro de la secuencia actual. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength)(long) | Cuando se anula en una clase derivada, establece la longitud del flujo actual. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray)() | Convierte el flujo actual en una matriz de bytes. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write)(byte[], int, int) | Cuando se anula en una clase derivada, escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo según el número de bytes escritos. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte)(byte) | Escribe un byte en la posición actual en la secuencia y avanza la posición dentro de la secuencia en un byte. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto)(Stream) | Escribe en el flujo especificado. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize) | Valor de tamaño de búfer predeterminado en bytes. |

### Ver también

* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->