---
title: ExternalSignature.ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: ExternalSignature constructor. Creates a detached PKCS7Detached signature using a X509Certificate2. It supports usb smartcards tokens without exportable private keys
type: docs
weight: 10
url: /net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

Creates a detached PKCS#7Detached signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | The certificate with the private key |

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_1}

Creates a PKCS#7 (detached) signature using a X509Certificate2 as base64 string.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Parameter | Type | Description |
| --- | --- | --- |
| base64 | String | X509Certificate2 as base64 string. |
| detached | Boolean | Is detached. |

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


