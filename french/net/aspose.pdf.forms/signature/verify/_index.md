---
title: "Signature.Verify"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Signature. Vérifie le document par rapport à cette signature et renvoie true si le document est valide, sinon false"
type: docs
weight: 170
url: /fr/net/aspose.pdf.forms/signature/verify/
---
## Verify() {#verify}

Vérifie le document par rapport à cette signature et renvoie true si le document est valide, sinon false.

```csharp
public bool Verify()
```

### Valeur de retour

true si le document est valide.

### Voir aussi

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(ValidationOptions, out ValidationResult) {#verify_1}

Vérifie le document par rapport à cette signature et renvoie true si le document est valide, sinon false.

```csharp
public bool Verify(ValidationOptions options, out ValidationResult validationResult)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | ValidationOptions | Les options de vérification. |
| validationResult | ValidationResult& | Le résultat de la validation du certificat. |

### Valeur de retour

true si le document est valide.

### Voir aussi

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(X509Certificate2, ValidationOptions, out ValidationResult) {#verify_2}

Vérifie le document par rapport à cette signature et renvoie true si le document est valide, sinon false. La vérification est effectuée à l'aide du certificat de clé publique externe.

```csharp
public bool Verify(X509Certificate2 publicKeyCertificate, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| publicKeyCertificate | X509Certificate2 | Le certificat de clé publique pour la vérification. |
| options | ValidationOptions | Les options de vérification. |
| validationResult | ValidationResult& | Le résultat de la validation du certificat. |

### Valeur de retour

true si le document est valide.

### Voir aussi

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


