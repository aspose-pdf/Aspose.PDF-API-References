---
title: PdfFileSignature.VerifySignature
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileSignature. Verifica la validez de una firma
type: docs
weight: 310
url: /es/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

Verifica la validez de una firma.

```csharp
public bool VerifySignature(SignatureName signName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | SignatureName | El nombre de la firma. |

### Valor de Retorno

Devuelve un resultado de tipo bool.

### Véase También

* clase [SignatureName](../../signaturename/)
* clase [PdfFileSignature](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

Verifica la validez de una firma.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signName | SignatureName | El nombre de la firma. |
| options | ValidationOptions | Las opciones de verificación. |
| validationResult | ValidationResult& | El resultado de la validación del certificado. |

### Valor de Retorno

Devuelve un resultado de tipo bool.

## Observaciones

Este método permite verificar el certificado de firma utilizando OCSP y/o CRL (lista de revocación de certificados) para la revocación. Este método no verifica la cadena de certificados y su validez, pero sí verifica si el certificado final ha sido revocado.

### Véase También

* clase [SignatureName](../../signaturename/)
* clase [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* clase [ValidationResult](../../../aspose.pdf.security/validationresult/)
* clase [PdfFileSignature](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)