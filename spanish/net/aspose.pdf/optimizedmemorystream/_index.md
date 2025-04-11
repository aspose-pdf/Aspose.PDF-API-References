---
title: Class OptimizedMemoryStream
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.OptimizedMemoryStream. Define un MemoryStream que puede contener más capacidad estándar
type: docs
weight: 7990
url: /es/net/aspose.pdf/optimizedmemorystream/
---
## Clase OptimizedMemoryStream

Define un MemoryStream que puede contener más capacidad estándar

```csharp
public class OptimizedMemoryStream : Stream
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | Inicializa una nueva instancia de la clase `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | Inicializa una nueva instancia de la clase `OptimizedMemoryStream` basada en el arreglo de bytes especificado. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | Inicializa una nueva instancia de la clase `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | Inicializa una nueva instancia de la clase `OptimizedMemoryStream` basada en el arreglo de bytes especificado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | Obtiene o establece el tamaño de los buffers subyacentes. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | Cuando se anula en una clase derivada, obtiene un valor que indica si el flujo actual admite la lectura. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | Cuando se anula en una clase derivada, obtiene un valor que indica si el flujo actual admite la búsqueda. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | Cuando se anula en una clase derivada, obtiene un valor que indica si el flujo actual admite la escritura. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | Obtiene o establece un valor que indica si se deben liberar los buffers subyacentes al desechar. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | Cuando se anula en una clase derivada, obtiene la longitud en bytes del flujo. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | Cuando se anula en una clase derivada, obtiene o establece la posición dentro del flujo actual. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | La función anulada. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | Cuando se anula en una clase derivada, lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo por el número de bytes leídos. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | Lee un byte del flujo y avanza la posición dentro del flujo un byte, o devuelve -1 si está al final del flujo. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | Cuando se anula en una clase derivada, establece la posición dentro del flujo actual. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | Cuando se anula en una clase derivada, establece la longitud del flujo actual. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | Convierte el flujo actual en un arreglo de bytes. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | Cuando se anula en una clase derivada, escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo por el número de bytes escritos. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | Escribe un byte en la posición actual del flujo y avanza la posición dentro del flujo un byte. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | Escribe en el flujo especificado. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | Valor del tamaño de buffer predeterminado en bytes. |

### Ver También

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)