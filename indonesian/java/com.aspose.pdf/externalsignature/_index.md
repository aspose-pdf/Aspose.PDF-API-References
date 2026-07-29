---
title: "ExternalSignature"
linktitle: "ExternalSignature"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Membuat tanda tangan PKCS#7Detached yang terpisah menggunakan X509Certificate2. Mendukung smartcard USB, token tanpa kunci pribadi yang dapat diekspor."
type: docs
weight: 1350
url: /id/java/com.aspose.pdf/externalsignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature com.aspose.pdf.ExternalSignature, com.aspose.pdf.Signature, com.aspose.pdf.ExternalSignature

```
public class ExternalSignature extends Signature
```

Membuat tanda tangan PKCS#7Detached yang terpisah menggunakan X509Certificate2. Mendukung smartcard USB, token tanpa kunci pribadi yang dapat diekspor.

## Fields

| Field | Deskripsi |
| --- | --- |
| [Certificate](#Certificate) | Sertifikat dengan kunci pribadi. |

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ExternalSignature](#ExternalSignature-java.lang.String-boolean-) | Membuat tanda tangan PKCS#7 (detached) menggunakan X509Certificate2 sebagai string base64. |
| [ExternalSignature](#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Membuat tanda tangan PKCS#7 {@code (detached)} menggunakan X509Certificate2 sebagai string base64. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Usang. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-) | Membuat tanda tangan PKCS#7Detached terpisah menggunakan X509Certificate2. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-) | Membuat tanda tangan PKCS#7 (detached) terpisah menggunakan X509Certificate2. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Usang. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-) | Membuat tanda tangan PKCS#7 (detached) terpisah menggunakan java.security.cert.X509Certificate dan java.security.PrivateKey. |

### Certificate {#Certificate}
```
public com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate
```

Sertifikat dengan kunci pribadi.

### ExternalSignature {#ExternalSignature-java.lang.String-boolean-}
Membuat tanda tangan PKCS#7 (detached) menggunakan X509Certificate2 sebagai string base64.

### ExternalSignature {#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Membuat tanda tangan PKCS#7 {@code (detached)} menggunakan X509Certificate2 sebagai string base64.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Usang.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-}
Membuat tanda tangan PKCS#7Detached terpisah menggunakan X509Certificate2.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-}
Membuat tanda tangan PKCS#7 (detached) terpisah menggunakan X509Certificate2.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
Usang.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-}
Membuat tanda tangan PKCS#7 (detached) terpisah menggunakan java.security.cert.X509Certificate dan java.security.PrivateKey.
