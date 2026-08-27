---
title: "Document.Pages"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Document propriété. Obtient ou définit la collection de pages du document. Notez que les pages sont numérotées à partir de 1 dans la collection"
type: docs
weight: 490
url: /fr/net/aspose.pdf/document/pages/
---
## Document.Pages property

Obtient ou définit la collection de pages du document. Notez que les pages sont numérotées à partir de 1 dans la collection.

```csharp
public PageCollection Pages { get; }
```

## Exemples

L'exemple ci-dessous montre comment manipuler les pages du document : comment obtenir le nombre de pages et comment obtenir le rectangle de la première page du document.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### Voir aussi

* class [PageCollection](../../pagecollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


