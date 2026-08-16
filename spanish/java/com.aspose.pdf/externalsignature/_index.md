---
title: "ExternalSignature"
linktitle: "ExternalSignature"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Crea una firma PKCS#7Detached separada usando un X509Certificate2. Soporta tarjetas inteligentes usb, tokens sin claves privadas exportables."
type: docs
weight: 1350
url: /es/java/com.aspose.pdf/externalsignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature com.aspose.pdf.ExternalSignature, com.aspose.pdf.Signature, com.aspose.pdf.ExternalSignature

```
public class ExternalSignature extends Signature
```

Crea una firma PKCS#7Detached separada usando un X509Certificate2. Soporta tarjetas inteligentes usb, tokens sin claves privadas exportables.

## Campos

| Campo | Descripción |
| --- | --- |
| [Certificate](#Certificate) | El certificado con la clave privada. |

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ExternalSignature](#ExternalSignature-java.lang.String-boolean-) | Crea una firma PKCS#7 (detached) usando un X509Certificate2 como cadena base64. |
| [ExternalSignature](#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Crea una firma PKCS#7 {@code (detached)} usando un X509Certificate2 como cadena base64. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Obsoleto. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-) | Crea una firma PKCS#7Detached separada usando un X509Certificate2. |
| [ExternalSignature](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-) | Crea una firma PKCS#7 (detached) separada usando un X509Certificate2. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | Obsoleto. |
| [ExternalSignature](#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-) | Crea una firma PKCS#7 (detached) separada usando un java.security.cert.X509Certificate y java.security.PrivateKey. |

### Certificate {#Certificate}
```
public com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 Certificate
```

El certificado con la clave privada.

### ExternalSignature {#ExternalSignature-java.lang.String-boolean-}
Crea una firma PKCS#7 (detached) usando un X509Certificate2 como cadena base64.

### ExternalSignature {#ExternalSignature-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Crea una firma PKCS#7 {@code (detached)} usando un X509Certificate2 como cadena base64.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Obsoleto.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-boolean-}
Crea una firma PKCS#7Detached separada usando un X509Certificate2.

### ExternalSignature {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.DigestHashAlgorithm-}
Crea una firma PKCS#7 (detached) separada usando un X509Certificate2.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
Obsoleto.

### ExternalSignature {#ExternalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-com.aspose.pdf.DigestHashAlgorithm-}
Crea una firma PKCS#7 (detached) separada usando un java.security.cert.X509Certificate y java.security.PrivateKey.
