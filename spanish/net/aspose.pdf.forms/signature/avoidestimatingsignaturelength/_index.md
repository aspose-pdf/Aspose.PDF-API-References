---
title: Signature.AvoidEstimatingSignatureLength
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de firma. Obtiene y establece una opción que significa si se debe evitar estimar la longitud de una firma
type: docs
weight: 30
url: /es/net/aspose.pdf.forms/signature/avoidestimatingsignaturelength/
---
## Propiedad Signature.AvoidEstimatingSignatureLength

Obtiene y establece una opción que significa si se debe evitar estimar la longitud de una firma.

```csharp
public bool AvoidEstimatingSignatureLength { get; set; }
```

## Observaciones

Evita estimar la longitud de la firma antes de firmar un documento. Se utiliza para firmar a través de [`CustomSignHash`](../customsignhash/) y a través de [`ExternalSignature`](../../externalsignature/). Si [`CustomSignHash`](../customsignhash/) devuelve una firma más larga que [`DefaultSignatureLength`](../defaultsignaturelength/), entonces se lanzará [`SignatureLengthMismatchException`](../../../aspose.pdf.security/signaturelengthmismatchexception/). El valor predeterminado es `false`.

### Véase también

* clase [Signature](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblado [Aspose.PDF](../../../)