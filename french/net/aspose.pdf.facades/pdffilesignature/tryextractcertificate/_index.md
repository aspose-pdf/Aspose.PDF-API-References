---
title: "PdfFileSignature.TryExtractCertificate"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "PdfFileSignature méthode. Extrait le certificat X.509 unique d'une signature"
type: docs
weight: 310
url: /fr/net/aspose.pdf.facades/pdffilesignature/tryextractcertificate/
---
## TryExtractCertificate(SignatureName, out X509Certificate2) {#tryextractcertificate_1}

Extrait le certificat X.509 unique de la signature.

```csharp
public bool TryExtractCertificate(SignatureName signName, out X509Certificate2 certificate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| signName | SignatureName | Le nom de la signature. |
| certificat | X509Certificate2& | Si un certificat a été trouvé, renvoie l'objet certificat X.509 unique ; sinon, null. |

### Valeur de retour

Un certificat valide a été trouvé.

### Voir aussi

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtractCertificate(SignatureName, out Stream) {#tryextractcertificate}

Extrait le certificat X.509 unique de la signature sous forme de flux.

```csharp
public bool TryExtractCertificate(SignatureName signName, out Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| signName | SignatureName | Le nom de la signature. |
| stream | Stream& | Si un certificat a été trouvé, renvoie le flux du certificat X.509 unique ; sinon, null. |

### Valeur de retour

Un certificat valide a été trouvé.

### Voir aussi

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


