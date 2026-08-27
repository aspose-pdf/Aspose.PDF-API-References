---
title: "Signature.AvoidEstimatingSignatureLength"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà Signature. Ottiene e imposta un'opzione che indica se evitare di stimare la lunghezza di una firma"
type: docs
weight: 30
url: /it/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Signature.AvoidEstimatingSignatureLength property

Ottiene e imposta un'opzione che indica se evitare di stimare la lunghezza di una firma.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## Osservazioni

Evita di stimare la lunghezza della firma prima di firmare un documento. Utilizzato per la firma tramite [`CustomSignHash`](../customsignhash/) e tramite [`ExternalSignature`](../../externalsignature/). Se [`CustomSignHash`](../customsignhash/) restituisce una firma più lunga di [`DefaultSignatureLength`](../defaultsignaturelength/), verrà sollevata l'eccezione [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/). Il valore predefinito è `false`.

### Vedi anche

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


