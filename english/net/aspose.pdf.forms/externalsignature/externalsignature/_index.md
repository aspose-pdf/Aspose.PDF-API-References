---
title: "ExternalSignature.ExternalSignature"
linktitle: "ExternalSignature"
articleTitle: "ExternalSignature"
second_title: "Aspose.PDF for .NET API Reference"
description: "ExternalSignature constructor. Initializes a new instance of the ExternalSignature class."
type: docs
weight: 10
url: "/net/aspose.pdf.forms/externalsignature/externalsignature/"
product_version: "26.9.0"
---
## ExternalSignature(X509Certificate2) {#constructor}

Creates a detached PKCS#7 `(detached)` signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys.

The digest algorithm will be automatically selected based on the certificate key data.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | The certificate with the private key. |

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)) {#constructor_1}

Creates a detached PKCS#7 `(detached)` signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | The certificate with the private key. |
| digestHashAlgorithm | DigestHashAlgorithm | The digest algorithm to sign a document. |

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

Creates a detached PKCS#7 signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys.

For detached set to false the digest algorithm will always be `SHA1`.
 Otherwise, the digest algorithm will be automatically selected based on the certificate key data( see `Auto` ).

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | The certificate with the private key. |
| detached | bool | True if the signature should be detached, otherwise false. |

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_3}

Creates a PKCS#7 signature using a X509Certificate2 as base64 string.

For detached set to false the digest algorithm will always be `SHA1`.
 Otherwise, the digest algorithm will be automatically selected based on the certificate key data( see `Auto` ).

```csharp
public ExternalSignature(string base64, bool detached)
```

| Parameter | Type | Description |
| --- | --- | --- |
| base64 | string | X509Certificate2 as base64 string. |
| detached | bool | True if the signature should be detached, otherwise false. |

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)) {#constructor_4}

Creates a PKCS#7 `(detached)` signature using a X509Certificate2 as base64 string.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Type | Description |
| --- | --- | --- |
| base64 | string | X509Certificate2 as base64 string. |
| digestHashAlgorithm | DigestHashAlgorithm | The digest algorithm to sign a document. |

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

