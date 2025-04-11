---
title: PdfXmpMetadata.GetPrefixByNamespaceURI
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfXmpMetadata. Obtient le préfixe par URI de namespace
type: docs
weight: 180
url: /fr/net/aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/
---
## Méthode PdfXmpMetadata.GetPrefixByNamespaceURI

Obtient le préfixe par URI de namespace.

```csharp
public string GetPrefixByNamespaceURI(string namespaceURI)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| namespaceURI | String | URI de namespace. |

### Valeur de retour

La valeur du préfixe.

## Exemples

```csharp
PdfXmpMetadata xmp = new PdfXmpMetadata("input.pdf");
Console.WriteLine(xmp.GetPrefixByNamespaceURI("http://ns.adobe.com/xap/1.0/"));
```

### Voir aussi

* classe [PdfXmpMetadata](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)