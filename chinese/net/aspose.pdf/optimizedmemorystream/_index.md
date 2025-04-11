---
title: Class OptimizedMemoryStream
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OptimizedMemoryStream class. 定义一个可以包含更多标准容量的 MemoryStream
type: docs
weight: 7990
url: /zh/net/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream class

定义一个可以包含更多标准容量的 MemoryStream

```csharp
public class OptimizedMemoryStream : Stream
```

## Constructors

| Name | Description |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | 初始化 `OptimizedMemoryStream` 类的新实例。 |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | 基于指定的字节数组初始化 `OptimizedMemoryStream` 类的新实例。 |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | 初始化 `OptimizedMemoryStream` 类的新实例。 |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | 基于指定的字节数组初始化 `OptimizedMemoryStream` 类的新实例。 |

## Properties

| Name | Description |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | 获取或设置基础缓冲区的大小。 |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | 在派生类中重写时，获取一个值，指示当前流是否支持读取。 |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | 在派生类中重写时，获取一个值，指示当前流是否支持查找。 |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | 在派生类中重写时，获取一个值，指示当前流是否支持写入。 |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | 获取或设置一个值，指示在处置时是否释放基础缓冲区。 |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | 在派生类中重写时，获取流的字节长度。 |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | 在派生类中重写时，获取或设置当前流中的位置。 |

## Methods

| Name | Description |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | 重写的函数。 |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | 在派生类中重写时，从当前流中读取字节序列，并根据读取的字节数推进流中的位置。 |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | 从流中读取一个字节，并将流中的位置推进一个字节，如果在流的末尾则返回 -1。 |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | 在派生类中重写时，设置当前流中的位置。 |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | 在派生类中重写时，设置当前流的长度。 |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | 将当前流转换为字节数组。 |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | 在派生类中重写时，将字节序列写入当前流，并根据写入的字节数推进当前流中的位置。 |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | 将一个字节写入流中的当前位置，并将流中的位置推进一个字节。 |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | 写入到指定的流。 |

## Fields

| Name | Description |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | 默认缓冲区大小值（以字节为单位）。 |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)