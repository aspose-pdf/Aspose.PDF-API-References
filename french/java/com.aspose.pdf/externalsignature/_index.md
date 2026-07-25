---
title: "ExternalSignature"
linktitle: "ExternalSignature"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Crée une signature détachée PKCS#7Detached en utilisant un X509Certificate2. Elle prend en charge les cartes à puce USB, les jetons sans clés privées exportables."
type: docs
weight: 1350
url: /fr/java/com.aspose.pdf/externalsignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature com.aspose.pdf.ExternalSignature, com.aspose.pdf.Signature, com.aspose.pdf.ExternalSignature

```
public class ExternalSignature extends Signature
```

Crée une signature détachée PKCS#7Detached en utilisant un X509Certificate2. Elle prend en charge les cartes à puce USB, les jetons sans clés privées exportables.

## Champs

| Champ | Description |
| --- | --- |
| [Certificate](#Certificate) | Le certificat avec la clé privée. |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ExternalSignature](#ExternalSignature-java.lang.String-boolean-) | Crée une signature PKCS#7 (détachée) en utilisant un X509Certificate2 sous forme de chaîne base64. |
| [ExternalSignature](#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Crée une signature PKCS#7 {@code (detached)} en utilisant un X509Certificate2 sous forme de chaîne base64. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Obsolète. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-) | Crée une signature PKCS#7Detached détachée en utilisant un X509Certificate2. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-) | Crée une signature PKCS#7 (détachée) détachée en utilisant un X509Certificate2. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Obsolète. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-) | Crée une signature PKCS#7 (détachée) détachée en utilisant un java.security.cert.X509Certificate et java.security.PrivateKey. |

### Certificate {#Certificate}
```
public com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate
```

Le certificat avec la clé privée.

### ExternalSignature {#ExternalSignature-java.lang.String-boolean-}
Crée une signature PKCS#7 (détachée) en utilisant un X509Certificate2 sous forme de chaîne base64.

### ExternalSignature {#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Crée une signature PKCS#7 {@code (detached)} en utilisant un X509Certificate2 sous forme de chaîne base64.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Obsolète.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-}
Crée une signature PKCS#7Detached détachée en utilisant un X509Certificate2.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-}
Crée une signature PKCS#7 (détachée) détachée en utilisant un X509Certificate2.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
Obsolète.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-}
Crée une signature PKCS#7 (détachée) détachée en utilisant un java.security.cert.X509Certificate et java.security.PrivateKey.
