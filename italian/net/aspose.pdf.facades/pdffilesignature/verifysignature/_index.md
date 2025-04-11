---
title: PdfFileSignature.VerifySignature
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileSignature. Controlla la validità di una firma
type: docs
weight: 310
url: /it/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

Controlla la validità di una firma.

```csharp
public bool VerifySignature(SignatureName signName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signName | SignatureName | Il nome della firma. |

### Valore di Ritorno

Restituisce un risultato di tipo bool.

### Vedi Anche

* classe [SignatureName](../../signaturename/)
* classe [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

Controlla la validità di una firma.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signName | SignatureName | Il nome della firma. |
| options | ValidationOptions | Le opzioni di verifica. |
| validationResult | ValidationResult& | Il risultato della validazione del certificato. |

### Valore di Ritorno

Restituisce un risultato di tipo bool.

## Osservazioni

Questo metodo consente di controllare il certificato di firma utilizzando OCSP e/o CRL (lista di revoca dei certificati) per la revoca. Questo metodo non controlla la catena di certificati e la sua validità, ma verifica se il certificato finale è stato revocato.

### Vedi Anche

* classe [SignatureName](../../signaturename/)
* classe [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* classe [ValidationResult](../../../aspose.pdf.security/validationresult/)
* classe [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)