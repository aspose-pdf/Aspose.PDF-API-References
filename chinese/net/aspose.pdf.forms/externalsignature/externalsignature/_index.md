---
title: ExternalSignature.ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: ExternalSignature 构造函数。使用 X509Certificate2 创建一个分离的 PKCS7 分离签名。它支持没有可导出私钥的 USB 智能卡令牌
type: docs
weight: 10
url: /zh/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

使用 X509Certificate2 创建一个分离的 PKCS#7 `(detached)` 签名。它支持 USB 智能卡，没有可导出私钥的令牌。

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| certificate | X509Certificate2 | 带有私钥的证书。 |

## 备注

摘要算法将根据证书密钥数据自动选择。

### 另见

* 类 [ExternalSignature](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

使用 X509Certificate2 创建一个分离的 PKCS#7 `(detached)` 签名。它支持 USB 智能卡，没有可导出私钥的令牌。

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| certificate | X509Certificate2 | 带有私钥的证书。 |
| digestHashAlgorithm | DigestHashAlgorithm | 用于签署文档的摘要算法。 |

### 另见

* 枚举 [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* 类 [ExternalSignature](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

使用 X509Certificate2 创建一个分离的 PKCS#7 签名。它支持 USB 智能卡，没有可导出私钥的令牌。

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| certificate | X509Certificate2 | 带有私钥的证书。 |
| detached | Boolean | 如果签名应该是分离的，则为 true，否则为 false。 |

## 备注

对于 detached 设置为 false，摘要算法将始终为 `SHA1`。否则，摘要算法将根据证书密钥数据自动选择（见 Auto）。

### 另见

* 类 [ExternalSignature](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

使用 X509Certificate2 作为 base64 字符串创建 PKCS#7 签名。

```csharp
public ExternalSignature(string base64, bool detached)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| base64 | String | X509Certificate2 作为 base64 字符串。 |
| detached | Boolean | 如果签名应该是分离的，则为 true，否则为 false。 |

## 备注

对于 detached 设置为 false，摘要算法将始终为 `SHA1`。否则，摘要算法将根据证书密钥数据自动选择（见 Auto）。

### 另见

* 类 [ExternalSignature](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

使用 X509Certificate2 作为 base64 字符串创建一个 PKCS#7 `(detached)` 签名。

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| base64 | String | X509Certificate2 作为 base64 字符串。 |
| digestHashAlgorithm | DigestHashAlgorithm | 用于签署文档的摘要算法。 |

### 另见

* 枚举 [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* 类 [ExternalSignature](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)