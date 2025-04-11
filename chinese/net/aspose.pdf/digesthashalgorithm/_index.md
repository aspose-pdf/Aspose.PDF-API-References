---
title: Enum DigestHashAlgorithm
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DigestHashAlgorithm 枚举。表示将数据映射到哈希的算法类型
type: docs
weight: 3720
url: /zh/net/aspose.pdf/digesthashalgorithm/
---
## DigestHashAlgorithm 枚举

表示将数据映射到“哈希”的算法类型

```csharp
public enum DigestHashAlgorithm
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Auto | `0` | 根据签名算法的判断自动设置哈希算法。对于 EDCSA，默认值由密钥大小决定。对于未分离的 PKCS7，默认值为 Sha1。 |
| Sha1 | `1` | SHA-1。安全哈希算法 1。它是未分离的 PKCS7 的默认值。 |
| Sha256 | `2` | SHA-256。安全哈希算法 2。它是分离的 PKCS7 的默认值。 |
| Sha384 | `3` | SHA-384。安全哈希算法 2。 |
| Sha512 | `4` | SHA-512。安全哈希算法 2。 |
| Sha3_256 | `5` | SHA3-256。安全哈希算法 3。 |
| Sha3_384 | `6` | SHA3-384。安全哈希算法 3。 |
| Sha3_512 | `7` | SHA3-512。安全哈希算法 3。 |

### 另请参阅

* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)