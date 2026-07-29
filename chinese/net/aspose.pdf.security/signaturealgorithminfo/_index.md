---
title: "类 SignatureAlgorithmInfo"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Security.SignatureAlgorithmInfo 类。表示关于签名算法的信息类，包括其类型、密码标准和摘要哈希算法"
type: docs
weight: 10180
url: /zh/net/aspose.pdf.security/signaturealgorithminfo/
---
## SignatureAlgorithmInfo class

表示有关签名算法信息的类，包括其类型、加密标准和摘要哈希算法。

```csharp
public abstract class SignatureAlgorithmInfo
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
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | 获取用于对 PDF 文档签名的签名算法类型。 |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | 获取用于对 PDF 文档签名的加密标准。 |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | 获取用于签名的摘要哈希算法。对于时间戳，这是用于对文档内容哈希进行签名的摘要哈希算法。 |

### 另请参见

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


