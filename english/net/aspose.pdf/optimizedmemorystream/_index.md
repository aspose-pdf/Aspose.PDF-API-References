---
title: Class OptimizedMemoryStream
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OptimizedMemoryStream class. Defines a MemoryStream that can contains more standard capacity
type: docs
weight: 6380
url: /net/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream class

Defines a MemoryStream that can contains more standard capacity

```csharp
public class OptimizedMemoryStream : Stream
```

## Constructors

| Name | Description |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | Initializes a new instance of the `OptimizedMemoryStream` class. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | Initializes a new instance of the `OptimizedMemoryStream` class based on the specified byte array. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | Initializes a new instance of the `OptimizedMemoryStream` class. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | Initializes a new instance of the `OptimizedMemoryStream` class based on the specified byte array. |

## Properties

| Name | Description |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | Gets or sets the size of the underlying buffers. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | When overridden in a derived class, gets a value indicating whether the current stream supports reading. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | When overridden in a derived class, gets a value indicating whether the current stream supports seeking. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | When overridden in a derived class, gets a value indicating whether the current stream supports writing. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | Gets or sets a value indicating whether to free the underlying buffers on dispose. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | When overridden in a derived class, gets the length in bytes of the stream. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | When overridden in a derived class, gets or sets the position within the current stream. |

## Methods

| Name | Description |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | The function overrided. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/)(byte[], int, int) | When overridden in a derived class, reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | When overridden in a derived class, sets the position within the current stream. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | When overridden in a derived class, sets the length of the current stream. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | Converts the current stream to a byte array. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/)(byte[], int, int) | When overridden in a derived class, writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | Writes to the specified stream. |

## Fields

| Name | Description |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | Default buffer size value in bytes. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


