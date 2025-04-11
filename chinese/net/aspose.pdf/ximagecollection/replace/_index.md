---
title: XImageCollection.Replace
second_title: Aspose.PDF for .NET API Reference
description: XImageCollection 方法。用另一张图像替换集合中的图像
type: docs
weight: 150
url: /zh/net/aspose.pdf/ximagecollection/replace/
---
## Replace(int, Stream) {#replace}

用另一张图像替换集合中的图像。

```csharp
public void Replace(int index, Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 要替换的集合项的索引，范围为 [1..图像数量]。 |
| stream | Stream | 包含图像数据的流（JPEG 格式）。 |

### 另请参见

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Replace(int, Stream, int, bool) {#replace_2}

用另一张图像替换集合中的图像。

```csharp
public void Replace(int index, Stream stream, int quality, bool isBlackAndWhite)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 要替换的集合项的索引，范围为 [1..图像数量]。 |
| stream | Stream | 包含图像数据的流（JPEG 格式）。 |
| quality | Int32 | JPEG 压缩质量，以百分比表示（有效值为 0..100）。 |
| isBlackAndWhite | Boolean | 如果为 true，图像将使用 CCITT 压缩方法进行压缩，该方法为黑白图像提供更好的压缩。仅可用于黑白图像。 |

### 另请参见

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Replace(int, Stream, int) {#replace_1}

用另一张图像替换集合中的图像。

```csharp
public void Replace(int index, Stream stream, int quality)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 要替换的集合项的索引，范围为 [1..图像数量]。 |
| stream | Stream | 包含图像数据的流（JPEG 格式）。 |
| quality | Int32 | JPEG 质量。 |

### 另请参见

* class [XImageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)