---
title: PdfXmpMetadata.RegisterNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfXmpMetadata. Enregistre l'URI de l'espace de noms
type: docs
weight: 200
url: /fr/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## Méthode PdfXmpMetadata.RegisterNamespaceURI

Enregistre l'URI de l'espace de noms.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | String | Le préfixe. |
| namespaceURI | String | L'URI de l'espace de noms. |

## Exemples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### Voir aussi

* classe [PdfXmpMetadata](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)