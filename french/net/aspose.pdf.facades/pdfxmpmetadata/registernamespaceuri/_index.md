---
title: RegisterNamespaceURI
second_title: Référence de l'API Aspose.PDF pour .NET
description: Enregistre lURI de lespace de noms.
type: docs
weight: 200
url: /fr/net/aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/
---
## PdfXmpMetadata.RegisterNamespaceURI method

Enregistre l'URI de l'espace de noms.

```csharp
public void RegisterNamespaceURI(string prefix, string namespaceURI)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| prefix | String | Le préfixe. |
| namespaceURI | String | L'URI de l'espace de noms. |

### Exemples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
xmp.RegisterNamespaceURI("xmp", "http://ns.adobe.com/xap/1.0/");
```

### Voir également

* class [PdfXmpMetadata](../../pdfxmpmetadata)
* espace de noms [Aspose.Pdf.Facades](../../pdfxmpmetadata)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
