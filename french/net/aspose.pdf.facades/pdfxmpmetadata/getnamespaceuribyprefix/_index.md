---
title: PdfXmpMetadata.GetNamespaceURIByPrefix
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfXmpMetadata. Obtient l'URI de l'espace de noms par préfixe
type: docs
weight: 170
url: /fr/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## Méthode PdfXmpMetadata.GetNamespaceURIByPrefix

Obtient l'URI de l'espace de noms par préfixe.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | String | Le préfixe. |

### Valeur de retour

URI de l'espace de noms.

## Exemples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### Voir aussi

* classe [PdfXmpMetadata](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)