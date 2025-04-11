---
title: OutputIntents.CopyTo
second_title: Aspose.PDF for .NET API Reference
description: OutputIntents 方法。将集合的元素复制到数组中，从特定的 arrayIndex 开始。
type: docs
weight: 70
url: /zh/net/aspose.pdf/outputintents/copyto/
---
## OutputIntents.CopyTo 方法

将集合的元素复制到 *array* 中，从特定的 *arrayIndex* 开始。

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | OutputIntent[] | 一维数组，是从集合中复制的输出意图的目标。数组必须具有零基索引。 |
| arrayIndex | Int32 | 在 *array* 中开始复制的零基索引。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *array* 为 null。 |
| ArgumentOutOfRangeException | *arrayIndex* 小于 0。 |
| ArgumentException | 源 [`OutputIntents`](../) 中的元素数量大于从 *arrayIndex* 到目标 *array* 末尾的可用空间。 |

### 另请参阅

* 类 [OutputIntent](../../outputintent/)
* 类 [OutputIntents](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)