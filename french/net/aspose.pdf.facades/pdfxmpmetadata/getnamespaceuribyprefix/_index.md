---
title: "PdfXmpMetadata.GetNamespaceURIByPrefix"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfXmpMetadata. Obtient l'URI de l'espace de noms par préfixe"
type: docs
weight: 170
url: /fr/net/aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/
---
## PdfXmpMetadata.GetNamespaceURIByPrefix method

Obtient l'URI de l'espace de noms par préfixe.

```csharp
public string GetNamespaceURIByPrefix(string prefix)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| préfixe | String | Le préfixe. |

### Valeur de retour

URI d'espace de noms.

## Exemples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetNamespaceURIByPrefix("xmp"));
```

### Voir aussi

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


