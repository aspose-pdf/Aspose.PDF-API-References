---
title: "PdfXmpMetadata.GetPrefixByNamespaceURI"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfXmpMetadata. Obtient le préfixe par URI d'espace de noms"
type: docs
weight: 180
url: /fr/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## PdfXmpMetadata.GetPrefixByNamespaceURI method

Obtient le préfixe par l'URI de l'espace de noms.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| namespaceURI | String | URI d'espace de noms. |

### Valeur de retour

La valeur du préfixe.

## Exemples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### Voir aussi

* class [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


