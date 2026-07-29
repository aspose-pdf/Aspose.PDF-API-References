---
title: "ExternalSignature"
linktitle: "ExternalSignature"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Erstellt eine losgelöste PKCS#7Detached-Signatur mithilfe eines X509Certificate2. Sie unterstützt USB-Smartcards, Token ohne exportierbare private Schlüssel."
type: docs
weight: 1350
url: /de/java/com.aspose.pdf/externalsignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature com.aspose.pdf.ExternalSignature, com.aspose.pdf.Signature, com.aspose.pdf.ExternalSignature

```
public class ExternalSignature extends Signature
```

Erstellt eine losgelöste PKCS#7Detached-Signatur mithilfe eines X509Certificate2. Sie unterstützt USB-Smartcards, Token ohne exportierbare private Schlüssel.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [Certificate](#Certificate) | Das Zertifikat mit dem privaten Schlüssel. |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ExternalSignature](#ExternalSignature-java.lang.String-boolean-) | Erstellt eine PKCS#7 (detached) Signatur unter Verwendung eines X509Certificate2 als Base64‑String. |
| [ExternalSignature](#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Erstellt eine PKCS#7 {@code (detached)} Signatur unter Verwendung eines X509Certificate2 als Base64‑String. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Veraltet. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-) | Erstellt eine abgetrennte PKCS#7Detached‑Signatur unter Verwendung eines X509Certificate2. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-) | Erstellt eine abgetrennte PKCS#7 (detached) Signatur unter Verwendung eines X509Certificate2. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Veraltet. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-) | Erstellt eine abgetrennte PKCS#7 (detached) Signatur unter Verwendung eines java.security.cert.X509Certificate und java.security.PrivateKey. |

### Certificate {#Certificate}
```
public com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate
```

Das Zertifikat mit dem privaten Schlüssel.

### ExternalSignature {#ExternalSignature-java.lang.String-boolean-}
Erstellt eine PKCS#7 (detached) Signatur unter Verwendung eines X509Certificate2 als Base64‑String.

### ExternalSignature {#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Erstellt eine PKCS#7 {@code (detached)} Signatur unter Verwendung eines X509Certificate2 als Base64‑String.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Veraltet.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-}
Erstellt eine abgetrennte PKCS#7Detached‑Signatur unter Verwendung eines X509Certificate2.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-}
Erstellt eine abgetrennte PKCS#7 (detached) Signatur unter Verwendung eines X509Certificate2.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
Veraltet.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-}
Erstellt eine abgetrennte PKCS#7 (detached) Signatur unter Verwendung eines java.security.cert.X509Certificate und java.security.PrivateKey.
