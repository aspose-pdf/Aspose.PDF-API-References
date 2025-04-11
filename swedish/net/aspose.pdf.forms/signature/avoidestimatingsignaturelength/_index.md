---
title: Signature.AvoidEstimatingSignatureLength
second_title: Aspose.PDF for .NET API Reference
description: Signatur egenskap. Hämtar och ställer in ett alternativ som innebär huruvida man ska undvika att uppskatta längden på en signatur
type: docs
weight: 30
url: /sv/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength egenskap

Hämtar och ställer in ett alternativ som innebär huruvida man ska undvika att uppskatta längden på en signatur.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## Kommentarer

Undviker att uppskatta signaturens längd innan ett dokument signeras. Används för signering via [`CustomSignHash`](../customsignhash/) och via [`ExternalSignature`](../../externalsignature/). Om [`CustomSignHash`](../customsignhash/) returnerar en signatur som är längre än [`DefaultSignatureLength`](../defaultsignaturelength/), kommer [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/) att kastas. Standardvärdet är `false`.

### Se Även

* klass [Signature](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)