---
title: Delegate SignHash
second_title: Aspose.PDF for .NET API Reference
description: 用于自定义签署文档哈希的委托
type: docs
weight: 5260
url: /zh/net/aspose.pdf.forms/signhash/
---
## SignHash 委托

用于自定义签署文档哈希的委托。

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| hash | Byte[] | 文档的输入哈希。 |
| digestHashAlgorithm | DigestHashAlgorithm | 用于创建哈希的摘要算法。该值永远不会等于 Auto。 |

### 返回值

输出签名。

## 备注

请注意，无论数字签名是否分离，哈希参数始终是最终要签署的哈希。

### 另见

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)