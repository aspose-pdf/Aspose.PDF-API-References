---
title: "类 OptimizedMemoryStream"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.OptimizedMemoryStream 类。定义一个可以容纳更大标准容量的 MemoryStream"
type: docs
weight: 8130
url: /zh/net/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream class

定义一个可以容纳更大标准容量的 MemoryStream。

```csharp
public class OptimizedMemoryStream : Stream
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | 初始化 `OptimizedMemoryStream` 类的新实例。 |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | 根据指定的字节数组初始化 `OptimizedMemoryStream` 类的新实例。 |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | 初始化 `OptimizedMemoryStream` 类的新实例。 |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | 根据指定的字节数组初始化 `OptimizedMemoryStream` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | 获取或设置底层缓冲区的大小。 |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | 在派生类中重写时，获取一个值，指示当前流是否支持读取。 |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | 在派生类中重写时，获取一个值，指示当前流是否支持定位。 |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | 在派生类中重写时，获取一个值，指示当前流是否支持写入。 |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | 获取或设置一个值，指示在释放时是否释放底层缓冲区。 |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | 在派生类中重写时，获取流的字节长度。 |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | 在派生类中重写时，获取或设置当前流中的位置。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | 已重写的函数。 |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | 在派生类中重写时，从当前流读取一系列字节，并将流中的位置前移读取的字节数。 |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | 从流中读取一个字节，并将流中的位置前移一个字节；如果已到达流的末尾，则返回 -1。 |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | 在派生类中重写时，设置当前流中的位置。 |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | 在派生类中重写时，设置当前流的长度。 |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | 将当前流转换为字节数组。 |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | 在派生类中重写时，将一系列字节写入当前流，并将此流中的当前位置前移写入的字节数。 |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | 向流的当前位置写入一个字节，并将流中的位置前移一个字节。 |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | 写入指定的流。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | 默认缓冲区大小（字节）。 |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


