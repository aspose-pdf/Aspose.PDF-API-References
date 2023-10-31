---
title: ExternalSignature
second_title: Aspose.PDF for Java API Reference
description: Creates a detached PKCS7Detached signature using a X509Certificate2.
type: docs
weight: 105
url: /java/com.aspose.pdf/externalsignature/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Signature](../../com.aspose.pdf/signature)
```
public class ExternalSignature extends Signature
```

Creates a detached PKCS\#7Detached signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys.
## Constructors

| Constructor | Description |
| --- | --- |
| [ExternalSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)](#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Creates a detached PKCS\#7Detached signature using a X509Certificate2. |
## Methods

| Method | Description |
| --- | --- |
| [getCertificate()](#getCertificate--) | The certificate with the private key. |
### ExternalSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate) {#ExternalSignature-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
```
public ExternalSignature(System.Security.Cryptography.X509Certificates.X509Certificate2 certificate)
```


Creates a detached PKCS\#7Detached signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificate | com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 | The certificate with the private key |

### getCertificate() {#getCertificate--}
```
public final System.Security.Cryptography.X509Certificates.X509Certificate2 getCertificate()
```


The certificate with the private key.

**Returns:**
com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 - X509Certificate2 instance with the private key
