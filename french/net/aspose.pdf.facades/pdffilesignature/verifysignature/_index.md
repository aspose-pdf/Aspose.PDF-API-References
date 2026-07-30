---
title: "PdfFileSignature.VerifySignature"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "PdfFileSignature method. Vérifie la validité d'une signature"
type: docs
weight: 320
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

Renvoie un résultat de type bool.

### Voir aussi

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
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
| validationResult | ValidationResult& | Le résultat de la validation du certificat. |

### Valeur de retour

Renvoie un résultat de type bool.

## Remarques

Cette méthode vous permet de vérifier le certificat de signature en utilisant OCSP et/ou CRL (liste de révocation de certificats) pour la révocation. Cette méthode ne vérifie pas la chaîne de certificats ni sa validité, mais elle vérifie si le certificat final a été révoqué.

### Voir aussi

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) {#verifysignature_3}

Vérifie la validité d'une signature. La vérification est effectuée à l'aide du certificat de clé publique externe.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate, 
    ValidationOptions options, out ValidationResult validationResult)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| signName | SignatureName | Le nom de la signature. |
| publicKeyCertificate | X509Certificate2 | Le certificat de clé publique pour la vérification. |
| options | ValidationOptions | Les options de vérification. |
| validationResult | ValidationResult& | Le résultat de la validation du certificat. |

### Valeur de retour

Renvoie un résultat de type bool.

## Remarques

Cette méthode vous permet de vérifier le certificat de signature en utilisant OCSP et/ou CRL (liste de révocation de certificats) pour la révocation. Cette méthode ne vérifie pas la chaîne de certificats ni sa validité, mais elle vérifie si le certificat final a été révoqué.

### Voir aussi

* class [SignatureName](../../signaturename/)
* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## VerifySignature(SignatureName, X509Certificate2) {#verifysignature_2}

Vérifie la validité d'une signature. La vérification est effectuée à l'aide du certificat de clé publique externe.

```csharp
public bool VerifySignature(SignatureName signName, X509Certificate2 publicKeyCertificate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| signName | SignatureName | Le nom de la signature. |
| publicKeyCertificate | X509Certificate2 | Le certificat de clé publique pour la vérification. |

### Valeur de retour

Renvoie un résultat de type bool.

### Voir aussi

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


