---
title: "委托 SignHash"
second_title: "Aspose.PDF for .NET API 参考"
description: "用于自定义签署文档 hash 的委托"
type: docs
weight: 5380
url: /zh/net/aspose.pdf.forms/signhash/
---
## SignHash delegate

用于自定义对文档哈希进行签名的委托。

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 哈希 | Byte[] | 文档的输入哈希。 |
| digestHashAlgorithm | DigestHashAlgorithm | 用于创建哈希的摘要算法。该值永远不会等于 Auto。 |

### 返回值

输出签名。

## 备注

请注意，无论数字签名是否为分离式，hash 参数始终是要签名的最终哈希。

### 另请参见

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


