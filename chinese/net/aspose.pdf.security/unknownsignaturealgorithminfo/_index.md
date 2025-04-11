---
title: Class UnknownSignatureAlgorithmInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.UnknownSignatureAlgorithmInfo 类。表示未知签名算法信息的类
type: docs
weight: 10040
url: /zh/net/aspose.pdf.security/unknownsignaturealgorithminfo/
---
## UnknownSignatureAlgorithmInfo class

表示未知签名算法信息的类。

```csharp
public sealed class UnknownSignatureAlgorithmInfo : SignatureAlgorithmInfo
```

## Properties

| Name | Description |
| --- | --- |
| [SignatureName](../../aspose.pdf.security/signaturealgorithminfo/signaturename/) { get; } | 获取签名字段的名称。 |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.security/signaturealgorithminfo/tostring/)() | 将当前信息对象转换为其字符串表示形式。 |

## Fields

| Name | Description |
| --- | --- |
| readonly [AlgorithmType](../../aspose.pdf.security/signaturealgorithminfo/algorithmtype/) | 获取用于签署 PDF 文档的签名算法类型。 |
| readonly [CryptographicStandard](../../aspose.pdf.security/signaturealgorithminfo/cryptographicstandard/) | 获取用于签署 PDF 文档的密码标准。 |
| readonly [DigestHashAlgorithm](../../aspose.pdf.security/signaturealgorithminfo/digesthashalgorithm/) | 获取用于签名的摘要哈希算法。对于时间戳，这是用于签署文档内容哈希的摘要哈希算法。 |

### See Also

* class [SignatureAlgorithmInfo](../signaturealgorithminfo/)
* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)