---
title: "ExternalSignature"
linktitle: "ExternalSignature"
second_title: "Aspose.PDF for Java API 参考"
description: "使用 X509Certificate2 创建分离的 PKCS#7Detached 签名。它支持 USB 智能卡、没有可导出私钥的令牌。"
type: docs
weight: 1350
url: /zh/java/com.aspose.pdf/externalsignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature com.aspose.pdf.ExternalSignature, com.aspose.pdf.Signature, com.aspose.pdf.ExternalSignature

```
public class ExternalSignature extends Signature
```

使用 X509Certificate2 创建分离的 PKCS#7Detached 签名。它支持 USB 智能卡、没有可导出私钥的令牌。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Certificate](#Certificate) | 带有私钥的证书。 |

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ExternalSignature](#ExternalSignature-java.lang.String-boolean-) | 使用 X509Certificate2 的 base64 字符串创建 PKCS#7（分离）签名。 |
| [ExternalSignature](#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | 使用 X509Certificate2 的 base64 字符串创建 PKCS#7 {@code (detached)} 签名。 |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | 已弃用。 |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-) | 使用 X509Certificate2 创建分离的 PKCS#7Detached 签名。 |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-) | 使用 X509Certificate2 创建分离的 PKCS#7（分离）签名。 |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | 已弃用。 |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-) | 使用 java.security.cert.X509Certificate 和 java.security.PrivateKey 创建分离的 PKCS#7（分离）签名。 |

### Certificate {#Certificate}
```
public com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate
```

带有私钥的证书。

### ExternalSignature {#ExternalSignature-java.lang.String-boolean-}
使用 X509Certificate2 的 base64 字符串创建 PKCS#7（分离）签名。

### ExternalSignature {#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
使用 X509Certificate2 的 base64 字符串创建 PKCS#7 {@code (detached)} 签名。

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
已弃用。

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-}
使用 X509Certificate2 创建分离的 PKCS#7Detached 签名。

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-}
使用 X509Certificate2 创建分离的 PKCS#7（分离）签名。

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
已弃用。

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-}
使用 java.security.cert.X509Certificate 和 java.security.PrivateKey 创建分离的 PKCS#7（分离）签名。
