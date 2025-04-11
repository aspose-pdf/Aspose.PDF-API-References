---
title: OptimizedMemoryStream.Read
second_title: Aspose.PDF for .NET API Reference
description: 优化的MemoryStream 方法。当在派生类中重写时，从当前流中读取字节序列，并通过读取的字节数推进流中的位置
type: docs
weight: 100
url: /zh/net/aspose.pdf/optimizedmemorystream/read/
---
## 优化的MemoryStream.Read 方法

当在派生类中重写时，从当前流中读取字节序列，并通过读取的字节数推进流中的位置。

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | Byte[] | 字节数组。当此方法返回时，缓冲区包含指定的字节数组及其值 |
| offset | Int32 | 从当前流中开始存储读取数据的零基字节偏移量。 |
| count | Int32 | 从当前流中要读取的最大字节数。 |

### 返回值

读取到缓冲区的字节总数。如果当前没有那么多字节可用，则可能少于请求的字节数，或者在到达流的末尾时为零 (0)。

### 另请参见

* 类 [优化的MemoryStream](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)