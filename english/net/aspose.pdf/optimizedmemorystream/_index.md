---
title: "OptimizedMemoryStream Class"
linktitle: "OptimizedMemoryStream"
articleTitle: "OptimizedMemoryStream"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.OptimizedMemoryStream class. Defines a MemoryStream that can contains more standard capacity"
type: docs
weight: 2050
url: "/net/aspose.pdf/optimizedmemorystream/"
keywords: "OptimizedMemoryStream, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## OptimizedMemoryStream class

Defines a MemoryStream that can contains more standard capacity

```csharp
public class OptimizedMemoryStream : Stream
```

## Constructors

| Name | Description |
| --- | --- |
| [OptimizedMemoryStream](./optimizedmemorystream/#constructor) | Initializes a new instance of the [`OptimizedMemoryStream`](../../aspose.pdf/optimizedmemorystream/) class. |
| [OptimizedMemoryStream](./optimizedmemorystream/#constructor_1)(*int*) | Initializes a new instance of the [`OptimizedMemoryStream`](../../aspose.pdf/optimizedmemorystream/) class. |
| [OptimizedMemoryStream](./optimizedmemorystream/#constructor_2)(*byte[]*) | Initializes a new instance of the [`OptimizedMemoryStream`](../../aspose.pdf/optimizedmemorystream/) class based on the specified byte array. |
| [OptimizedMemoryStream](./optimizedmemorystream/#constructor_3)(*int, byte[]*) | Initializes a new instance of the [`OptimizedMemoryStream`](../../aspose.pdf/optimizedmemorystream/) class based on the specified byte array. |

## Properties

| Name | Description |
| --- | --- |
| [BufferSize](./buffersize/) { get; set; } | Gets or sets the size of the underlying buffers. |
| [CanRead](./canread/) { get; } | When overridden in a derived class, gets a value indicating whether the current stream supports reading. |
| [CanSeek](./canseek/) { get; } | When overridden in a derived class, gets a value indicating whether the current stream supports seeking. |
| [CanWrite](./canwrite/) { get; } | When overridden in a derived class, gets a value indicating whether the current stream supports writing. |
| [FreeOnDispose](./freeondispose/) { get; set; } | Gets or sets a value indicating whether to free the underlying buffers on dispose. |
| [Length](./length/) { get; } | When overridden in a derived class, gets the length in bytes of the stream. |
| [Position](./position/) { get; set; } | When overridden in a derived class, gets or sets the position within the current stream. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](./dispose/)(*bool*) | Releases the unmanaged resources used by the `Stream` and optionally releases the managed resources. |
| [Flush](./flush/) | The function overrided. |
| [Read](./read/)(*byte[], int, int*) | When overridden in a derived class, reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| [ReadByte](./readbyte/) | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| [Seek](./seek/)(*long, SeekOrigin*) | When overridden in a derived class, sets the position within the current stream. |
| [SetLength](./setlength/)(*long*) | When overridden in a derived class, sets the length of the current stream. |
| [ToArray](./toarray/) | Converts the current stream to a byte array. |
| [Write](./write/)(*byte[], int, int*) | When overridden in a derived class, writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| [WriteByte](./writebyte/)(*byte*) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| [WriteTo](./writeto/)(*Stream*) | Writes to the specified stream. |

## Fields

| Name | Description |
| --- | --- |
| const [DefaultBufferSize](./defaultbuffersize/) | Default buffer size value in bytes. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

