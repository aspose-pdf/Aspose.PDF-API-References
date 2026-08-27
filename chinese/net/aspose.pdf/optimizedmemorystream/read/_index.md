---
title: "OptimizedMemoryStream.Read"
second_title: "Aspose.PDF for .NET API 参考"
description: "OptimizedMemoryStream 方法。 在派生类中重写时，从当前流读取字节序列，并按读取的字节数前移流中的位置"
type: docs
weight: 100
url: /zh/net/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream.Read method

在派生类中重写时，从当前流读取一系列字节，并将流中的位置前移读取的字节数。

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 缓冲区 | Byte[] | 字节数组。当此方法返回时，缓冲区包含具有这些值的指定字节数组 |
| 偏移量 | Int32 | 在缓冲区中的零基字节偏移量，指示从何处开始存储从当前流读取的数据。 |
| 计数 | Int32 | 要从当前流读取的最大字节数。 |

### 返回值

读取到缓冲区的字节总数。如果当前可用字节不足请求的字节数，则可能少于请求的字节数；如果已到达流的末尾，则为零 (0)。

### 另请参见

* class [OptimizedMemoryStream](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


