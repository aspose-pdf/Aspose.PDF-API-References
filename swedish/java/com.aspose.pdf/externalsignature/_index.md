---
title: "ExternalSignature"
linktitle: "ExternalSignature"
second_title: "Aspose.PDF för Java API-referens"
description: "Skapar en fristående PKCS#7Detached-signatur med en X509Certificate2. Den stöder USB-smartkort, token utan exporterbara privata nycklar."
type: docs
weight: 1350
url: /sv/java/com.aspose.pdf/externalsignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature com.aspose.pdf.ExternalSignature, com.aspose.pdf.Signature, com.aspose.pdf.ExternalSignature

```
public class ExternalSignature extends Signature
```

Skapar en fristående PKCS#7Detached-signatur med en X509Certificate2. Den stöder USB-smartkort, token utan exporterbara privata nycklar.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [Certificate](#Certificate) | Certifikatet med den privata nyckeln. |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ExternalSignature](#ExternalSignature-java.lang.String-boolean-) | Skapar en PKCS#7 (frånkopplad) signatur med en X509Certificate2 som base64-sträng. |
| [ExternalSignature](#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Skapar en PKCS#7 {@code (detached)} signatur med en X509Certificate2 som base64-sträng. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Föråldrad. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-) | Skapar en frånkopplad PKCS#7Detached signatur med en X509Certificate2. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-) | Skapar en frånkopplad PKCS#7 (detached) signatur med en X509Certificate2. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Föråldrad. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-) | Skapar en frånkopplad PKCS#7 (detached) signatur med en java.security.cert.X509Certificate och java.security.PrivateKey. |

### Certificate {#Certificate}
```
public com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate
```

Certifikatet med den privata nyckeln.

### ExternalSignature {#ExternalSignature-java.lang.String-boolean-}
Skapar en PKCS#7 (frånkopplad) signatur med en X509Certificate2 som base64-sträng.

### ExternalSignature {#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Skapar en PKCS#7 {@code (detached)} signatur med en X509Certificate2 som base64-sträng.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Föråldrad.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-}
Skapar en frånkopplad PKCS#7Detached signatur med en X509Certificate2.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-}
Skapar en frånkopplad PKCS#7 (detached) signatur med en X509Certificate2.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
Föråldrad.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-}
Skapar en frånkopplad PKCS#7 (detached) signatur med en java.security.cert.X509Certificate och java.security.PrivateKey.
