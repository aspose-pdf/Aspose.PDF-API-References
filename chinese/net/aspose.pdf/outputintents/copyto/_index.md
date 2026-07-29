---
title: "OutputIntents.CopyTo"
second_title: "Aspose.PDF for .NET API 参考"
description: "OutputIntents 方法。 将集合的元素复制到数组，从特定的 arrayIndex 开始复制到数组中。"
type: docs
weight: 70
url: /zh/net/aspose.pdf/outputintents/copyto/
---
## OutputIntents.CopyTo method

将集合的元素复制到 *array*，从特定的 *arrayIndex* 开始复制到数组中。

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 数组 | OutputIntent[] | 从集合中复制的输出意图的目标是一维数组。该数组必须使用从零开始的索引。 |
| arrayIndex | Int32 | 该 *array* 中开始复制的零基索引。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *array* 为 null。 |
| ArgumentOutOfRangeException | *arrayIndex* 小于 0。 |
| ArgumentException | 源 [`OutputIntents`](../) 中的元素数量大于从 *arrayIndex* 到目标 *array* 末尾的可用空间。 |

### 另请参见

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


