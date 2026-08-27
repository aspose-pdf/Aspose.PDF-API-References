---
title: "Signature.AvoidEstimatingSignatureLength"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Signature. Obtient et définit une option indiquant s'il faut éviter d'estimer la longueur d'une signature."
type: docs
weight: 30
url: /fr/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength property

Obtient et définit une option indiquant s'il faut éviter d'estimer la longueur d'une signature.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## Remarques

Évite d'estimer la longueur de la signature avant la signature d'un document. Utilisé pour signer via [`CustomSignHash`](../customsignhash/) et via [`ExternalSignature`](../../externalsignature/). Si [`CustomSignHash`](../customsignhash/) renvoie une signature plus longue que [`DefaultSignatureLength`](../defaultsignaturelength/), alors [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/) sera levée. La valeur par défaut est `false`.

### Voir aussi

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


