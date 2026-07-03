---
title: ExternalSignature
second_title: Aspose.PDF for Java API Reference
description: Creates a detached PKCS#7Detached signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys.
type: docs
weight: 1350
url: /java/com.aspose.pdf/externalsignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature com.aspose.pdf.ExternalSignature, com.aspose.pdf.Signature, com.aspose.pdf.ExternalSignature

```
public class ExternalSignature extends Signature
```

Creates a detached PKCS#7Detached signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys.

## Fields

| Field | Description |
| --- | --- |
| [Certificate](#Certificate) | The certificate with the private key. |

## Constructors

| Constructor | Description |
| --- | --- |
| [ExternalSignature](#ExternalSignature-java.lang.String-boolean-) | Creates a PKCS#7 (detached) signature using a X509Certificate2 as base64 string. |
| [ExternalSignature](#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Creates a PKCS#7 {@code (detached)} signature using a X509Certificate2 as base64 string. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Deprecated. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-) | Creates a detached PKCS#7Detached signature using a X509Certificate2. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-) | Creates a detached PKCS#7 (detached) signature using a X509Certificate2. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Deprecated. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-) | Creates a detached PKCS#7 (detached) signature using a java.security.cert.X509Certificate and java.security.PrivateKey. |

### Certificate {#Certificate}
```
public com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate
```

The certificate with the private key.

### ExternalSignature {#ExternalSignature-java.lang.String-boolean-}
Creates a PKCS#7 (detached) signature using a X509Certificate2 as base64 string.

### ExternalSignature {#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Creates a PKCS#7 {@code (detached)} signature using a X509Certificate2 as base64 string.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Deprecated.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-}
Creates a detached PKCS#7Detached signature using a X509Certificate2.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-}
Creates a detached PKCS#7 (detached) signature using a X509Certificate2.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
Deprecated.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-}
Creates a detached PKCS#7 (detached) signature using a java.security.cert.X509Certificate and java.security.PrivateKey.
