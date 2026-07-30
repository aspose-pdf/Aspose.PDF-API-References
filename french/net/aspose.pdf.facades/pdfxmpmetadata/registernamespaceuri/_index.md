---
title: "PdfXmpMetadata.RegisterNamespaceURI"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "PdfXmpMetadata méthode. Enregistre l'URI de l'espace de noms"
type: docs
weight: 200
url: /fr/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI method

Enregistre l'URI de l'espace de noms.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| préfixe | String | Le préfixe. |
| namespaceURI | String | L'URI de l'espace de noms. |

## Exemples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### Voir aussi

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


