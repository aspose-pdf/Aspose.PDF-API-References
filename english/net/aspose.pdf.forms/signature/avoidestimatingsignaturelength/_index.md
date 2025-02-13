---
title: Signature.AvoidEstimatingSignatureLength
second_title: Aspose.PDF for .NET API Reference
description: Signature property. Gets and sets an option means whether to avoid estimating the length of a signature
type: docs
weight: 30
url: /net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength property

Gets and sets an option means whether to avoid estimating the length of a signature.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## Remarks

Avoids to estimate signature length before a signing document. Used for signing via [`CustomSignHash`](../customsignhash/) an via [`ExternalSignature`](../../externalsignature/). If [`CustomSignHash`](../customsignhash/) returns a signature longer than [`DefaultSignatureLength`](../defaultsignaturelength/), then [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/) will be thrown. The default value is `false`.

### See Also

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


