---
title: "Signature.AvoidEstimatingSignatureLength"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Signature-egenskap. Hämtar och anger ett alternativ som bestämmer om man ska undvika att uppskatta signaturens längd"
type: docs
weight: 30
url: /sv/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength property

Hämtar och anger ett alternativ som avgör om man ska undvika att uppskatta längden på en signatur.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## Anmärkningar

Undviker att uppskatta signaturens längd innan ett dokument signeras. Används för signering via [`CustomSignHash`](../customsignhash/) och via [`ExternalSignature`](../../externalsignature/). Om [`CustomSignHash`](../customsignhash/) returnerar en signatur som är längre än [`DefaultSignatureLength`](../defaultsignaturelength/), kastas [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/). Standardvärdet är `false`.

### Se även

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


