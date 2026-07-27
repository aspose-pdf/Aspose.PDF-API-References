---
title: "ExternalSignature"
linktitle: "ExternalSignature"
second_title: "Referência da API Aspose.PDF para Java"
description: "Cria uma assinatura PKCS#7Detached destacada usando um X509Certificate2. Suporta smartcards USB, tokens sem chaves privadas exportáveis."
type: docs
weight: 1350
url: /pt/java/com.aspose.pdf/externalsignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature com.aspose.pdf.ExternalSignature, com.aspose.pdf.Signature, com.aspose.pdf.ExternalSignature

```
public class ExternalSignature extends Signature
```

Cria uma assinatura PKCS#7Detached destacada usando um X509Certificate2. Suporta smartcards USB, tokens sem chaves privadas exportáveis.

## Campos

| Campo | Descrição |
| --- | --- |
| [Certificate](#Certificate) | O certificado com a chave privada. |

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ExternalSignature](#ExternalSignature-java.lang.String-boolean-) | Cria uma assinatura PKCS#7 (detached) usando um X509Certificate2 como string base64. |
| [ExternalSignature](#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Cria uma assinatura PKCS#7 {@code (detached)} usando um X509Certificate2 como string base64. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Obsoleto. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-) | Cria uma assinatura desanexada PKCS#7Detached usando um X509Certificate2. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-) | Cria uma assinatura PKCS#7 (detached) desanexada usando um X509Certificate2. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Obsoleto. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-) | Cria uma assinatura PKCS#7 (detached) desanexada usando um java.security.cert.X509Certificate e java.security.PrivateKey. |

### Certificate {#Certificate}
```
public com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate
```

O certificado com a chave privada.

### ExternalSignature {#ExternalSignature-java.lang.String-boolean-}
Cria uma assinatura PKCS#7 (detached) usando um X509Certificate2 como string base64.

### ExternalSignature {#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Cria uma assinatura PKCS#7 {@code (detached)} usando um X509Certificate2 como string base64.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Obsoleto.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-}
Cria uma assinatura desanexada PKCS#7Detached usando um X509Certificate2.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-}
Cria uma assinatura PKCS#7 (detached) desanexada usando um X509Certificate2.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
Obsoleto.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-}
Cria uma assinatura PKCS#7 (detached) desanexada usando um java.security.cert.X509Certificate e java.security.PrivateKey.
