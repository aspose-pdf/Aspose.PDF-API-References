---
title: "ExternalSignature"
linktitle: "ExternalSignature"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "X509Certificate2 を使用して分離型 PKCS#7Detached 署名を作成します。USB スマートカードや、エクスポート可能なプライベートキーを持たないトークンをサポートします。"
type: docs
weight: 1350
url: /ja/java/com.aspose.pdf/externalsignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature com.aspose.pdf.ExternalSignature, com.aspose.pdf.Signature, com.aspose.pdf.ExternalSignature

```
public class ExternalSignature extends Signature
```

X509Certificate2 を使用して分離型 PKCS#7Detached 署名を作成します。USB スマートカードや、エクスポート可能なプライベートキーを持たないトークンをサポートします。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Certificate](#Certificate) | プライベートキーを含む証明書です。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ExternalSignature](#ExternalSignature-java.lang.String-boolean-) | X509Certificate2 を base64 文字列として使用して、PKCS#7（デタッチド）署名を作成します。 |
| [ExternalSignature](#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | X509Certificate2 を base64 文字列として使用して、PKCS#7 {@code (detached)} 署名を作成します。 |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | 非推奨です。 |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-) | X509Certificate2 を使用して、デタッチド PKCS#7Detached 署名を作成します。 |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-) | X509Certificate2 を使用して、デタッチド PKCS#7（デタッチド）署名を作成します。 |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | 非推奨です。 |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-) | java.security.cert.X509Certificate と java.security.PrivateKey を使用して、デタッチド PKCS#7（デタッチド）署名を作成します。 |

### Certificate {#Certificate}
```
public com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate
```

プライベートキーを含む証明書です。

### ExternalSignature {#ExternalSignature-java.lang.String-boolean-}
X509Certificate2 を base64 文字列として使用して、PKCS#7（デタッチド）署名を作成します。

### ExternalSignature {#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
X509Certificate2 を base64 文字列として使用して、PKCS#7 {@code (detached)} 署名を作成します。

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
非推奨です。

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-}
X509Certificate2 を使用して、デタッチド PKCS#7Detached 署名を作成します。

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-}
X509Certificate2 を使用して、デタッチド PKCS#7（デタッチド）署名を作成します。

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
非推奨です。

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-}
java.security.cert.X509Certificate と java.security.PrivateKey を使用して、デタッチド PKCS#7（デタッチド）署名を作成します。
