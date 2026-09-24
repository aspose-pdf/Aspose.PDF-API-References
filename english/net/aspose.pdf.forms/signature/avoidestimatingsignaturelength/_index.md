---
title: "Signature.AvoidEstimatingSignatureLength"
linktitle: "AvoidEstimatingSignatureLength"
articleTitle: "AvoidEstimatingSignatureLength"
second_title: "Aspose.PDF for .NET API Reference"
description: "Signature property. Gets and sets an option means whether to avoid estimating the length of a signature."
type: docs
weight: 220
url: "/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/"
product_version: "26.9.0"
---
## Signature.AvoidEstimatingSignatureLength property

Gets and sets an option means whether to avoid estimating the length of a signature.

Avoids to estimate signature length before a signing document.
 Used for signing via `CustomSignHash` an via [`ExternalSignature`](../../../aspose.pdf.forms/externalsignature/).
 If `CustomSignHash` returns a signature longer than `DefaultSignatureLength`, then [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/) will be thrown.
 The default value is `false`.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

### Property Value

bool

### See Also

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

