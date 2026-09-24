---
title: "ExternalSignature Class"
linktitle: "ExternalSignature"
articleTitle: "ExternalSignature"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Forms.ExternalSignature class. Creates a detached PKCS#7 signature using a X509Certificate2. It supports usb smartcards, tokens without exportable..."
type: docs
weight: 110
url: "/net/aspose.pdf.forms/externalsignature/"
keywords: "ExternalSignature, Aspose.Pdf.Forms, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ExternalSignature class

Creates a detached PKCS#7 signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys.

```csharp
public class ExternalSignature : Signature
```

## Constructors

| Name | Description |
| --- | --- |
| [ExternalSignature](./externalsignature/#constructor)(*X509Certificate2*) | Creates a detached PKCS#7 `(detached)` signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys. |
| [ExternalSignature](./externalsignature/#constructor_1)(*X509Certificate2, [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)*) | Creates a detached PKCS#7 `(detached)` signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys. |
| [ExternalSignature](./externalsignature/#constructor_2)(*X509Certificate2, bool*) | Creates a detached PKCS#7 signature using a X509Certificate2. It supports usb smartcards, tokens without exportable private keys. |
| [ExternalSignature](./externalsignature/#constructor_3)(*string, bool*) | Creates a PKCS#7 signature using a X509Certificate2 as base64 string. |
| [ExternalSignature](./externalsignature/#constructor_4)(*string, [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)*) | Creates a PKCS#7 `(detached)` signature using a X509Certificate2 as base64 string. |

## Methods

| Name | Description |
| --- | --- |
| [Process](../../aspose.pdf.lowcode/signature/process/)(*IPluginOptions*) | Starts the [`Signature`](../../aspose.pdf.lowcode/signature/) processing with the specified parameters. *(Inherited from Signature)* |

## Fields

| Name | Description |
| --- | --- |
| readonly [Certificate](./certificate/) | The certificate with the private key. |

### See Also

* class [Signature](../../aspose.pdf.lowcode/signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)

