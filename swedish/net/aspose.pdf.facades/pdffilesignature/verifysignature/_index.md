---
title: PdfFileSignature.VerifySignature
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature-metod. Kontrollerar giltigheten av en signatur
type: docs
weight: 310
url: /sv/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

Kontrollerar giltigheten av en signatur.

```csharp
public bool VerifySignature(SignatureName signName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | SignatureName | Namnet på signaturen. |

### Returvärde

Returnerar ett resultat av bool-typ.

### Se Även

* klass [SignatureName](../../signaturename/)
* klass [PdfFileSignature](../)
* namnrum [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

Kontrollerar giltigheten av en signatur.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | SignatureName | Namnet på signaturen. |
| options | ValidationOptions | Verifieringsalternativen. |
| validationResult | ValidationResult& | Resultatet av certifikatvalideringen. |

### Returvärde

Returnerar ett resultat av bool-typ.

## Kommentarer

Denna metod gör att du kan kontrollera signeringscertifikatet med hjälp av OCSP och/eller CRL (certifikatåterkallandelista) för återkallelse. Denna metod kontrollerar inte certifikatkedjan och dess giltighet, men den kontrollerar om slutcertifikatet har återkallats.

### Se Även

* klass [SignatureName](../../signaturename/)
* klass [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* klass [ValidationResult](../../../aspose.pdf.security/validationresult/)
* klass [PdfFileSignature](../)
* namnrum [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)