---
title: PdfFileSignature.VerifySignature
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature-Methode. Überprüft die Gültigkeit einer Signatur
type: docs
weight: 310
url: /de/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

Überprüft die Gültigkeit einer Signatur.

```csharp
public bool VerifySignature(SignatureName signName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signName | SignatureName | Der Name der Signatur. |

### Rückgabewert

Gibt ein Ergebnis vom Typ bool zurück.

### Siehe auch

* Klasse [SignatureName](../../signaturename/)
* Klasse [PdfFileSignature](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

Überprüft die Gültigkeit einer Signatur.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signName | SignatureName | Der Name der Signatur. |
| options | ValidationOptions | Die Überprüfungsoptionen. |
| validationResult | ValidationResult& | Das Ergebnis der Zertifikatsvalidierung. |

### Rückgabewert

Gibt ein Ergebnis vom Typ bool zurück.

## Anmerkungen

Diese Methode ermöglicht es Ihnen, das Signaturzertifikat mithilfe von OCSP und/oder CRL (Zertifikatswiderrufsliste) auf Widerruf zu überprüfen. Diese Methode überprüft nicht die Zertifikatskette und deren Gültigkeit, sondern prüft, ob das Endzertifikat widerrufen wurde.

### Siehe auch

* Klasse [SignatureName](../../signaturename/)
* Klasse [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* Klasse [ValidationResult](../../../aspose.pdf.security/validationresult/)
* Klasse [PdfFileSignature](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)