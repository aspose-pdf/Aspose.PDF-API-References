---
title: Class TimestampAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.TimestampAlgorithmInfo 类。表示有关时间戳签名算法的信息的类
type: docs
weight: 10030
url: /zh/net/aspose.pdf.security/timestampalgorithminfo/
---
## TimestampAlgorithmInfo 类

表示有关时间戳签名算法的信息的类。

```csharp
public sealed class TimestampAlgorithmInfo : SignatureAlgorithmInfo
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | 获取签名字段的名称。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | 将当前信息对象转换为其字符串表示形式。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | 获取用于签署 PDF 文档的签名算法类型。 |
| readonly [ContentHashAlgorithm](../../aspose.pdf.security/timestampalgorithminfo/contenthashalgorithm/) | 获取对文档内容进行哈希并使用 [`DigestHashAlgorithm`](../signaturealgorithminfo/digesthashalgorithm/) 签名的哈希算法。 |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | 获取用于签署 PDF 文档的密码标准。 |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | 获取用于签名的摘要哈希算法。对于时间戳，这是用于签署文档内容哈希的摘要哈希算法。 |

### 另请参阅

* 类 [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* 命名空间 [Aspose.Pdf.Security](../../aspose.pdf.security/)
* 程序集 [Aspose.PDF](../../)