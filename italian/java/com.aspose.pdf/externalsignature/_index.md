---
title: "ExternalSignature"
linktitle: "ExternalSignature"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Crea una firma PKCS#7Detached separata utilizzando un X509Certificate2. Supporta smartcard USB, token senza chiavi private esportabili."
type: docs
weight: 1350
url: /it/java/com.aspose.pdf/externalsignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature com.aspose.pdf.ExternalSignature, com.aspose.pdf.Signature, com.aspose.pdf.ExternalSignature

```
public class ExternalSignature extends Signature
```

Crea una firma PKCS#7Detached separata utilizzando un X509Certificate2. Supporta smartcard USB, token senza chiavi private esportabili.

## Campi

| Campo | Descrizione |
| --- | --- |
| [Certificate](#Certificate) | Il certificato con la chiave privata. |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ExternalSignature](#ExternalSignature-java.lang.String-boolean-) | Crea una firma PKCS#7 (detached) utilizzando un X509Certificate2 come stringa base64. |
| [ExternalSignature](#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Crea una firma PKCS#7 {@code (detached)} utilizzando un X509Certificate2 come stringa base64. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Obsoleto. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-) | Crea una firma PKCS#7Detached (detached) utilizzando un X509Certificate2. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-) | Crea una firma PKCS#7 (detached) utilizzando un X509Certificate2. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Obsoleto. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-) | Crea una firma PKCS#7 (detached) utilizzando un java.security.cert.X509Certificate e java.security.PrivateKey. |

### Certificate {#Certificate}
```
public com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate
```

Il certificato con la chiave privata.

### ExternalSignature {#ExternalSignature-java.lang.String-boolean-}
Crea una firma PKCS#7 (detached) utilizzando un X509Certificate2 come stringa base64.

### ExternalSignature {#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Crea una firma PKCS#7 {@code (detached)} utilizzando un X509Certificate2 come stringa base64.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Obsoleto.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-}
Crea una firma PKCS#7Detached (detached) utilizzando un X509Certificate2.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-}
Crea una firma PKCS#7 (detached) utilizzando un X509Certificate2.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
Obsoleto.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-}
Crea una firma PKCS#7 (detached) utilizzando un java.security.cert.X509Certificate e java.security.PrivateKey.
