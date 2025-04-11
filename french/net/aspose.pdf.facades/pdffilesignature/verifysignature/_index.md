---
title: PdfFileSignature.VerifySignature
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileSignature. Vérifie la validité d'une signature
type: docs
weight: 310
url: /fr/net/aspose.pdf.facades/pdffilesignature/verifysignature/
---
## VerifySignature(SignatureName) {#verifysignature}

Vérifie la validité d'une signature.

```csharp
public bool VerifySignature(SignatureName signName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| signName | SignatureName | Le nom de la signature. |

### Valeur de retour

Retourne un résultat de type bool.

### Voir aussi

* classe [SignatureName](../../signaturename/)
* classe [PdfFileSignature](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, ValidationOptions, out ValidationResult) {#verifysignature_1}

Vérifie la validité d'une signature.

```csharp
public bool VerifySignature(SignatureName signName, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| signName | SignatureName | Le nom de la signature. |
| options | ValidationOptions | Les options de vérification. |
| validationResult | ValidationResult& | Le résultat de validation du certificat. |

### Valeur de retour

Retourne un résultat de type bool.

## Remarques

Cette méthode vous permet de vérifier le certificat de signature en utilisant OCSP et/ou CRL (liste de révocation de certificats) pour la révocation. Cette méthode ne vérifie pas la chaîne de certificats et sa validité, mais elle vérifie si le certificat final a été révoqué.

### Voir aussi

* classe [SignatureName](../../signaturename/)
* classe [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* classe [ValidationResult](../../../aspose.pdf.security/validationresult/)
* classe [PdfFileSignature](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)