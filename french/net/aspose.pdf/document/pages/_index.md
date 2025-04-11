---
title: Document.Pages
second_title: Aspose.PDF for .NET API Reference
description: Propriété Document. Obtient ou définit la collection des pages du document. Notez que les pages sont numérotées à partir de 1 dans la collection
type: docs
weight: 470
url: /fr/net/aspose.pdf/document/pages/
---
## Propriété Document.Pages

Obtient ou définit la collection des pages du document. Notez que les pages sont numérotées à partir de 1 dans la collection.

```csharp
public PageCollection Pages { get; }
```

## Exemples

L'exemple ci-dessous démontre comment opérer avec les pages du document : Comment obtenir le nombre de pages et comment obtenir le rectangle de la page de départ du document.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### Voir aussi

* classe [PageCollection](../../pagecollection/)
* classe [Document](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)