---
title: "PdfFileSignature.VerifySignature"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfFileSignature. Verifica la validità di una firma."
type: docs
weight: 320
url: /it/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

Verifica la validità di una firma.

```csharp
public bool VerifySignature(SignatureName signName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signName | SignatureName | Il nome della firma. |

### Valore di ritorno

Restituisce un risultato di tipo bool.

### Vedi anche

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

Verifica la validità di una firma.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signName | SignatureName | Il nome della firma. |
| options | ValidationOptions | Le opzioni di verifica. |
| validationResult | ValidationResult& | Il risultato della convalida del certificato. |

### Valore di ritorno

Restituisce un risultato di tipo bool.

## Osservazioni

Questo metodo consente di verificare il certificato di firma utilizzando OCSP e/o CRL (lista di revoca dei certificati) per la revoca. Questo metodo non controlla la catena del certificato né la sua validità, ma verifica se il certificato finale è stato revocato.

### Vedi anche

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) {#verifysignature_3}

Verifica la validità di una firma. La verifica è eseguita utilizzando il certificato della chiave pubblica esterna.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate, 
    ValidationOptions options, out ValidationResult validationResult)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signName | SignatureName | Il nome della firma. |
| publicKeyCertificate | X509Certificate2 | Il certificato della chiave pubblica per la verifica. |
| options | ValidationOptions | Le opzioni di verifica. |
| validationResult | ValidationResult& | Il risultato della convalida del certificato. |

### Valore di ritorno

Restituisce un risultato di tipo bool.

## Osservazioni

Questo metodo consente di verificare il certificato di firma utilizzando OCSP e/o CRL (lista di revoca dei certificati) per la revoca. Questo metodo non controlla la catena del certificato né la sua validità, ma verifica se il certificato finale è stato revocato.

### Vedi anche

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2) {#verifysignature_2}

Verifica la validità di una firma. La verifica è eseguita utilizzando il certificato della chiave pubblica esterna.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signName | SignatureName | Il nome della firma. |
| publicKeyCertificate | X509Certificate2 | Il certificato della chiave pubblica per la verifica. |

### Valore di ritorno

Restituisce un risultato di tipo bool.

### Vedi anche

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


