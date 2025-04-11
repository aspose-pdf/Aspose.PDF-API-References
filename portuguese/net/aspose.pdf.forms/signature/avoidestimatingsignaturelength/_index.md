---
title: Signature.AvoidEstimatingSignatureLength
second_title: Aspose.PDF for .NET API Reference
description: Propriedade de assinatura. Obtém e define uma opção que significa se deve evitar estimar o comprimento de uma assinatura
type: docs
weight: 30
url: /pt/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Propriedade Signature.AvoidEstimatingSignatureLength

Obtém e define uma opção que significa se deve evitar estimar o comprimento de uma assinatura.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## Observações

Evita estimar o comprimento da assinatura antes de assinar um documento. Usado para assinar via [`CustomSignHash`](../customsignhash/) e via [`ExternalSignature`](../../externalsignature/). Se [`CustomSignHash`](../customsignhash/) retornar uma assinatura mais longa do que [`DefaultSignatureLength`](../defaultsignaturelength/), então [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/) será lançada. O valor padrão é `false`.

### Veja Também

* classe [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)