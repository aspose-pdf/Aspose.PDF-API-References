---
title: Signature.AvoidEstimatingSignatureLength
second_title: Aspose.PDF for .NET API Reference
description: Propriété Signature. Obtient et définit une option qui signifie s'il faut éviter d'estimer la longueur d'une signature
type: docs
weight: 30
url: /fr/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Propriété Signature.AvoidEstimatingSignatureLength

Obtient et définit une option qui signifie s'il faut éviter d'estimer la longueur d'une signature.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## Remarques

Évite d'estimer la longueur de la signature avant de signer un document. Utilisé pour signer via [`CustomSignHash`](../customsignhash/) et via [`ExternalSignature`](../../externalsignature/). Si [`CustomSignHash`](../customsignhash/) retourne une signature plus longue que [`DefaultSignatureLength`](../defaultsignaturelength/), alors [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/) sera levée. La valeur par défaut est `false`.

### Voir aussi

* classe [Signature](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)